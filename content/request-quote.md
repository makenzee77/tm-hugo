---
title: "Запрос коммерческого предложения"
description: "Сформируйте единый запрос коммерческого предложения по выбранным товарам."
draft: false
menu:
  main:
    name: "Запрос КП"
    weight: 40
---



<div class="row mb-5">
  <div class="col-lg-10 mx-auto">
    <div class="card border-0 shadow-sm">
      <div class="card-body p-4">
        <!-- Выбранные товары -->
        <div class="d-flex justify-content-between align-items-center flex-wrap gap-2 mb-4">
          <h5 class="fw-bold mb-0">
            <i class="fas fa-list text-danger me-2"></i>Выбранные товары
          </h5>
          <button type="button" class="btn btn-outline-secondary btn-sm" id="clear-quote">
            <i class="fas fa-trash-alt me-2"></i>Очистить список
          </button>
        </div>
        <div id="quote-empty-state" class="alert alert-light border">
          <div class="d-flex">
            <i class="fas fa-info-circle text-danger me-3 mt-1"></i>
            <div>
              <strong>Список пока пуст.</strong><br>
              Перейдите в каталог продукции и добавьте нужные позиции в запрос КП.
            </div>
          </div>
        </div>
        <div id="quote-items-wrapper" class="d-none mb-4">
          <div id="quote-items" class="vstack gap-3"></div>
          <hr class="my-4">
          <div class="d-flex justify-content-between align-items-center">
            <span class="text-muted">Всего позиций</span>
            <strong id="quote-total-items">0</strong>
          </div>
        </div>
        <!-- Контактные данные -->
        <h5 class="fw-bold mb-3 mt-4">
          <i class="fas fa-user-circle text-danger me-2"></i>Контактные данные
        </h5>
        <form id="quote-form" action="https://formspree.io/f/mzdkyqbj" method="POST">
          <input type="hidden" name="_subject" value="Запрос КП с сайта Точные машины">
          <input type="hidden" name="form_type" value="quote_request">
          <input type="hidden" name="source_page" value="request-quote">
          <input type="hidden" id="quote-json" name="quote_json">
          <div class="row g-3">
            <div class="col-md-6">
              <label for="company" class="form-label">Компания / ФИО <span class="text-danger">*</span></label>
              <input type="text" class="form-control" id="company" name="company" required>
            </div>
            <div class="col-md-6">
              <label for="contact-person" class="form-label">Контактное лицо</label>
              <input type="text" class="form-control" id="contact-person" name="contact_person">
            </div>
            <div class="col-md-6">
              <label for="email" class="form-label">E-mail <span class="text-danger">*</span></label>
              <input type="email" class="form-control" id="email" name="email" required>
            </div>
            <div class="col-md-6">
              <label for="phone" class="form-label">Телефон <span class="text-danger">*</span></label>
              <input type="tel" class="form-control" id="phone" name="phone" placeholder="+7 (___) ___-__-__" required>
            </div>
            <div class="col-12">
              <label for="comment" class="form-label">Комментарий к запросу</label>
              <textarea class="form-control" id="comment" name="comment" rows="3"
                        placeholder="Например: нужны сроки поставки, условия оплаты, техническая консультация, подбор аналогов"></textarea>
            </div>
            <div class="col-12">
              <label for="quote-summary" class="form-label">Состав запроса</label>
              <textarea class="form-control" id="quote-summary" name="quote_summary" rows="5" readonly></textarea>
              <div class="form-text">Поле заполняется автоматически на основе выбранных товаров.</div>
            </div>
            <div class="col-12">
              <div class="form-check">
                <input class="form-check-input" type="checkbox" id="agree" name="agreement" value="yes" required>
                <label class="form-check-label small" for="agree">
                  Я согласен(на) на
                  <a href="/privacy-policy/" target="_blank" rel="noopener noreferrer">обработку персональных данных</a>
                  и принимаю
                  <a href="/terms/" target="_blank" rel="noopener noreferrer">условия использования</a>
                  <span class="text-danger">*</span>
                </label>
              </div>
            </div>
            <div class="col-12">
              <button type="submit" class="btn btn-danger w-100" id="submit-quote-btn">
                <i class="fas fa-paper-plane me-2"></i>Отправить запрос КП
              </button>
            </div>
          </div>
        </form>
        <div id="quote-form-warning" class="alert alert-warning mt-4 mb-0 d-none">
          <i class="fas fa-exclamation-triangle me-2"></i>
          Нельзя отправить пустой запрос. Сначала добавьте хотя бы один товар.
        </div>
      </div>
    </div>
  </div>
</div>

<script>
document.addEventListener('DOMContentLoaded', function () {
  const STORAGE_KEY = 'tm_quote_cart';

  const quoteItems = document.getElementById('quote-items');
  const quoteItemsWrapper = document.getElementById('quote-items-wrapper');
  const quoteEmptyState = document.getElementById('quote-empty-state');
  const quoteTotalItems = document.getElementById('quote-total-items');
  const quoteSummary = document.getElementById('quote-summary');
  const quoteJson = document.getElementById('quote-json');
  const quoteForm = document.getElementById('quote-form');
  const formWarning = document.getElementById('quote-form-warning');
  const clearBtn = document.getElementById('clear-quote');

  function getCart() {
    try {
      const raw = localStorage.getItem(STORAGE_KEY);
      if (!raw) return [];
      const parsed = JSON.parse(raw);
      return Array.isArray(parsed) ? parsed : [];
    } catch (e) {
      return [];
    }
  }

  function saveCart(cart) {
    localStorage.setItem(STORAGE_KEY, JSON.stringify(cart));
  }

  function buildSummaryLine(item, index) {
    const qty = Number(item.quantity || 1);
    let summaryLine = `${index + 1}. ${item.name || 'Без названия'} — ${qty} шт.`;

    if (item.partNumber) {
      summaryLine += ` (Артикул: ${item.partNumber})`;
    }

    if (item.comment) {
      summaryLine += `; комментарий: ${item.comment}`;
    }

    return summaryLine;
  }

  function renderCart() {
    const cart = getCart();
    quoteItems.innerHTML = '';

    if (!cart.length) {
      quoteItemsWrapper.classList.add('d-none');
      quoteEmptyState.classList.remove('d-none');
      quoteSummary.value = '';
      quoteJson.value = '';
      quoteTotalItems.textContent = '0';
      return;
    }

    quoteItemsWrapper.classList.remove('d-none');
    quoteEmptyState.classList.add('d-none');

    let total = 0;
    const summaryLines = [];

    cart.forEach((item, index) => {
  const qty = Number(item.quantity || 1);
  total += qty;

  const line = document.createElement('div');
  line.className = 'border rounded p-3';

  line.innerHTML = `
    <div class="row g-3 align-items-center">
      <div class="col-md-5">
        <div class="fw-bold">${item.name || 'Без названия'}</div>
      </div>

      <div class="col-md-3">
        <label class="form-label small mb-1">Количество</label>
        <input
          type="number"
          min="1"
          class="form-control form-control-sm quote-qty"
          data-index="${index}"
          value="${qty}">
      </div>

      <div class="col-12 d-flex justify-content-end">
        <button
          type="button"
          class="btn btn-outline-danger btn-sm remove-quote-item"
          data-index="${index}">
          <i class="fas fa-times me-1"></i>Удалить
        </button>
      </div>
    </div>
  `;

  quoteItems.appendChild(line);
  summaryLines.push(buildSummaryLine(item, index));
});

    quoteTotalItems.textContent = total;
    quoteSummary.value = summaryLines.join('\n');
    quoteJson.value = JSON.stringify(cart);
  }

  quoteItems.addEventListener('input', function (e) {
    const cart = getCart();

    if (e.target.classList.contains('quote-qty')) {
      const index = Number(e.target.dataset.index);
      const value = Math.max(1, Number(e.target.value || 1));
      cart[index].quantity = value;
      saveCart(cart);
      renderCart();
    }

    if (e.target.classList.contains('quote-item-comment')) {
      const index = Number(e.target.dataset.index);
      cart[index].comment = e.target.value;
      saveCart(cart);
      renderCart();
    }
  });

  quoteItems.addEventListener('click', function (e) {
    const btn = e.target.closest('.remove-quote-item');
    if (!btn) return;

    const index = Number(btn.dataset.index);
    const cart = getCart();
    cart.splice(index, 1);
    saveCart(cart);
    renderCart();
  });

  clearBtn.addEventListener('click', function () {
    localStorage.removeItem(STORAGE_KEY);
    renderCart();
  });

  quoteForm.addEventListener('submit', function (e) {
    const cart = getCart();

    if (!cart.length) {
      e.preventDefault();
      formWarning.classList.remove('d-none');
      return;
    }

    formWarning.classList.add('d-none');
    quoteSummary.value = cart.map(buildSummaryLine).join('\n');
    quoteJson.value = JSON.stringify(cart);
  });

  renderCart();
});
</script>