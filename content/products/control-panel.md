---
title: "Пульт управления сельскохозяйственной техникой"
fullName: "Позволяет контролировать исправность подключенных к нему
элементов с коррекцией алгоритма функционирования в зависимости от их состояния."
date: 2024-01-13
draft: false
weight: 130

# Технические характеристики
functions: "45 программируемых функций"
interface: "CAN-интерфейс"
power: "9-36В"
protection: "IP65"
dimensions: "213x175x113 мм"

# Категории и теги
categories: ["controllers"]
tags: ["пульт", "управление", "CAN", "сельхозтехника"]
applications: ["Тракторы", "Комбайны", "Сельхозтехника"]

# Изображения
images:
  - "control_panel_2.jpg"

# SEO
description: "Подрулька - пульт управления сельхозтехникой с 45 программируемыми функциями и CAN интерфейсом для тракторов и комбайнов."
---

## Описание

**Пульт управления сельскохозяйственной техникой** предназначен для формирования сигналов, управляющих
функционированием узлов и агрегатов.

Пульт управления сельскохозяйственной позволяет контролировать исправность подключенных к нему
элементов с коррекцией алгоритма функционирования в зависимости от их состояния.

Пульт управления сельскохозяйственной имеет габариты позволяющие устанавливать его в уже существующие
конструкторские решения. 
 
## Фотографии

<div class="bg-light p-3 rounded mb-4">
  <div id="utudCarousel" class="carousel slide carousel-dark" data-bs-ride="carousel" data-bs-interval="5000" style="cursor: pointer;">
    <div class="carousel-inner rounded" style="height: 250px;">
      <div class="carousel-item active" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/control_panel_2.jpg">
        <img src="/tm-hugo/img/products/control_panel_2.jpg" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="Пульт управления">
      </div>
    </div>
  </div>
  <p class="text-muted small text-center mt-2 mb-0"><i class="fas fa-search-plus me-1"></i>Нажмите на изображение для увеличения</p>
</div>

<div class="modal fade" id="imageModal" tabindex="-1" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered modal-xl">
    <div class="modal-content bg-dark">
      <div class="modal-header border-0">
        <button type="button" class="btn-close btn-close-white" data-bs-dismiss="modal" aria-label="Закрыть"></button>
      </div>
      <div class="modal-body text-center p-0">
        <img id="modalImage" src="" class="img-fluid" alt="Увеличенное изображение">
      </div>
    </div>
  </div>
</div>

<script>
  const imageModal = document.getElementById('imageModal');
  imageModal.addEventListener('show.bs.modal', function (event) {
    const button = event.relatedTarget;
    const imgSrc = button.getAttribute('data-img');
    document.getElementById('modalImage').src = imgSrc;
  });
</script>

## Характеристики

<div class="table-responsive">
  <table class="table table-sm table-striped">
    <tbody>
      <tr><td><strong>Напряжение питания</strong></td><td>От 8 до 32 В</td></tr>
      <tr><td><strong>Потребляемая мощность (без учета мощности на управление пропорциональными клапанами)</strong></td><td>Не более 2 Вт</td></tr>
      <tr><td><strong>Сигнал управления</strong></td><td>CAN</td></tr>
      <tr><td><strong>Количество релейных входов</strong></td><td>13</td></tr>
      <tr><td><strong>Количество универсальных аналоговых входов</strong></td><td>2</td></tr>
      <tr><td><strong>Количество ШИМ каналов управления</strong></td><td>26</td></tr>
      <tr><td><strong>Максимальный выходной ток каналов управления</strong></td><td>3 А</td></tr>
      <tr><td><strong>Температура окружающей среды рабочая</strong></td><td>-40 °С до +65 °С</td></tr>
      <tr><td><strong>Масса</strong></td><td>Не более 1 кг</td></tr>
    </tbody>
  </table>
</div>


## Преимущества

<div class="row g-4 mb-4">
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Цифровой CAN интерфейс</h6>
        <p class="small">Цифровой CAN интерфейс позволяет интегрировать в СУ других производителей.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Полная диагностика</h6>
        <p class="small">Полная диагностика элементов управления с выдачей сообщений о ошибках в CAN интерфейс.</p>
      </div>
    </div>
  </div>
  <div class="col-md-12">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Индивидуальная трехцветная подсветка</h6>
        <p class="small">Индивидуальная регулируемая трехцветная подсветка клавиш управления обеспечивает индикацию текущих режимов и аварийных ситуаций.</p>
      </div>
    </div>
  </div>
</div>

## Видеопрезентация

<div class="ratio ratio-16x9 mb-4">
  <iframe src="https://www.youtube.com/embed/VIDEO_ID_HERE" title="УТУД - Видеопрезентация" allowfullscreen></iframe>
</div>

---

## Документация
- [Тех. паспорт (PDF)](/docs/BKU-datasheet.pdf)
- [Руководство (PDF)](/docs/BKU-manual.pdf)