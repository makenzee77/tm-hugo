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
      <div class="carousel-item active" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/controller_fan_2.jpg">
        <img src="/tm-hugo/img/products/controller_fan_2.jpg" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="Контроллер вентилятора">
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

## Видеопрезентация

<div class="ratio ratio-16x9 mb-4">
  <iframe src="https://www.youtube.com/embed/VIDEO_ID_HERE" title="УТУД - Видеопрезентация" allowfullscreen></iframe>
</div>

---

## Документация
- [Тех. паспорт (PDF)](/docs/BKU-datasheet.pdf)
- [Руководство (PDF)](/docs/BKU-manual.pdf)