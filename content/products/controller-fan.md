---
title: "Контроллер вентилятора"
fullName: "Предназначен для управления оборотами вентилятора охлаждения охлаждающей
жидкости ДВС."
date: 2024-01-08
draft: false
weight: 80

# Технические характеристики
control: "PWM управление"
power: "8-32В"
protection: "IP54"
temperature: "-40...+65°C"

# Категории и теги
categories: ["controllers"]
tags: ["вентилятор", "PWM", "охлаждение"]
applications: ["Системы охлаждения", "Вентиляция"]

# Изображения
images:
  - "controller_fan_2.jpg"
  - "controller_fan_3.jpg"

# SEO
description: "Контроллер вентилятора с PWM управлением для систем охлаждения и вентиляции с защитой IP54."
---

## Описание

**Контроллер вентилятора** предназначен для управления оборотами вентилятора охлаждения охлаждающей жидкости
ДВС.

Контроллер вентилятора позволяет контролировать исправность подключенных к нему элементов с коррекцией
алгоритма функционирования в зависимости от их состояния.

Контроллер вентилятора имеет степень защиты IP54, что, в сочетании с минимальными габаритами, позволяет
устанавливать его в широкий спектр уже готовых конструкторских решений. 

## Фотографии

<div class="bg-light p-3 rounded mb-4">
  <div id="utudCarousel" class="carousel slide carousel-dark" data-bs-ride="carousel" data-bs-interval="5000" style="cursor: pointer;">
    <div class="carousel-inner rounded" style="height: 250px;">
      <div class="carousel-item active" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/fan.jpg">
        <img src="/tm-hugo/img/products/fan.jpg" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="Контроллер вентилятора">
      </div>
      <div class="carousel-item" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/fancontrollr-paln.png">
          <img src="/tm-hugo/img/products/fancontrollr-paln.png" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="Контроллер вентилятора">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#utudCarousel" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Назад</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#utudCarousel" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Вперёд</span>
      </button>
  </div>
  <p class="text-muted small text-center mt-2 mb-0"><i class="fas fa-search-plus me-1"></i>Нажмите на изображение для увеличения</p>
</div>

<div class="modal fade" id="imageModal" tabindex="-1" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered modal-xl">
    <div class="modal-content bg-dark">
      <div class="modal-header border-0">
        <button type="button" class="btn-close btn-close-white" data-bs-dismiss="modal" aria-label="Закрыть"></button>
      </div>
      <div class="modal-body text-center p-4" style="display: flex; align-items: center; justify-content: center; min-height: 400px;">
        <img id="modalImage" src="" class="img-fluid" style="max-height: 75vh; max-width: 100%; object-fit: contain;" alt="Увеличенное изображение">
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
      <tr><td><strong>Потребляемая мощность (без учета коммутируемой мощности
исполнительного устройства</strong></td><td>Не более 2 Вт </td></tr>
      <tr><td><strong>Сигнал управления исполнительным устройством</strong></td><td>PWM 
</td></tr>
      <tr><td><strong>Тип датчика температуры охлаждающей жидкости</strong></td><td>Аналоговый резистивный</td></tr>
      <tr><td><strong>Температура окружающий среды рабочая</strong></td><td>-40 оС до +65 оС </td></tr>
      <tr><td><strong>Масса</strong></td><td>Не более 0,3 кг</td></tr>
    </tbody>
  </table>
</div>

## Преимущества

<div class="row g-4 mb-4">
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Устойчивость к экстремальным условиям</h6>
        <p class="small">Возможность эксплуатации в условиях значительных вибраций и широком спектре климатических исполнений конечного устройства.</p>
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