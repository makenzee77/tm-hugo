---
title: "Контроллер секции гидрораспределителя"
fullName: "Предназначен для управления потоком жидкости через
секцию в соответствии с полученными по CAN интерфейсу командами."
date: 2024-01-09
draft: false
weight: 

# Технические характеристики
interface: "CAN"
accuracy: "0.05 сек"
power: "8-32В"
temperature: "-40...+65°C"

# Категории и теги
categories: ["controllers"]
tags: ["секции", "CAN", "сельхозтехника", "точность"]
applications: ["Опрыскиватели", "Сеялки", "Сельхозтехника"]

# Изображения
images:
  - "controller_section_2.jpg"

# SEO
description: "Контроллер секции с точностью 0.05 сек и CAN интерфейсом для опрыскивателей, сеялок и сельхозтехники."
---

## Описание

**Контроллер секции гидрораспределителя** предназначен для управления ПОТОКОМ ЖИДКОСТИ через секцию
в соответствии с полученными по CAN интерфейсу командами.

Контроллер секции гидрораспределителя позволяет контролировать исправность подключенных к нему
элементов с коррекцией алгоритма функционирования в зависимости от их состояния.

Контроллер секции гидрораспределителя имеет минимальные габариты, укомплектован датчиком
линейного перемещения, что позволяет устанавливать его в широкий спектр уже готовых конструкторских решений.

## Фотографии

<div class="bg-light p-3 rounded mb-4">
  <div id="utudCarousel" class="carousel slide carousel-dark" data-bs-ride="carousel" data-bs-interval="5000" style="cursor: pointer;">
    <div class="carousel-inner rounded" style="height: 250px;">
      <div class="carousel-item active" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/controller_section_2.jpg">
        <img src="/tm-hugo/img/products/controller_section_2.jpg" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="Контроллер секции">
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
      <tr><td><strong>Потребляемая мощность (без учета мощности на управление
пропорциональными клапанами) </strong></td><td>Не более 2 Вт </td></tr>
      <tr><td><strong>Сигнал управления</strong></td><td>CAN</td></tr>
      <tr><td><strong>Точность датчика линейных перемещений</strong></td><td>±0.05мм</td></tr>
      <tr><td><strong>Количество каналов управления пропорциональными клапанами</strong></td><td>2</td></tr>
      <tr><td><strong>Максимальный выходной ток</strong></td><td>3А</td></tr>
      <tr><td><strong>Температура окружающий среды рабочая</strong></td><td>-40 оС до +65 оС </td></tr>
      <tr><td><strong>Масса (вместе с датчиком линейного перемещения) </strong></td><td>Не более 0,3 кг</td></tr>
    </tbody>
  </table>
</div>

## Преимущества

<div class="row g-4 mb-4">
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Цифровой CAN интерфейс</h6>
        <p class="small">Цифровой CAN интерфейс позволяет исключить наводки и помехи при работе.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Полная диагностика</h6>
        <p class="small">Полная диагностика элементов управления с выдачей сообщений о ошибках.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Датчик линейных перемещений</h6>
        <p class="small">Наличие датчика линейных перемещений позволяет контролировать положение золотника и более точно регулировать поток жидкости.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Широкий диапазон питания</h6>
        <p class="small">Питание от бортовой сети с широким диапазоном напряжения.</p>
      </div>
    </div>
  </div>
</div>

<!--
## Видеопрезентация
<div class="ratio ratio-16x9 mb-4">
  <iframe src="https://www.youtube.com/embed/VIDEO_ID_HERE" title="УТУД - Видеопрезентация" allowfullscreen></iframe>
</div>
-->
---
**Для получения подробной информации, технических консультаций или оформления заказа свяжитесь с нашими специалистами:**

📞 **Телефон**: +7 (932) 617-76-22  
📧 **Email**: [info@precisionmachines.pro](mailto:info@precisionmachines.pro)
<!--
## Документация
- [Тех. паспорт (PDF)](/docs/BKU-datasheet.pdf)
- [Руководство (PDF)](/docs/BKU-manual.pdf)
-->