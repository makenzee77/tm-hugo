---
title: "Датчик скорости"
fullName: "Принцип действия данного датчика скорости вращения – бесконтактное магнитное сканирование. Благодаря бесконтактному измерению вращения датчик скорости не требует постоянного технического
обслуживания и износоустойчив."
date: 2024-01-11
draft: false
weight: 110

# Технические характеристики
frequency: "0-25 кГц"
voltage: "10-30В"
temperature: "0...25°C"
protection: "IP68"

# Категории и теги
categories: ["sensors"]
tags: ["скорость", "вращение", "частота"]
applications: ["Измерение скорости", "Контроль оборотов"]

# Изображения
images:
  - "Speedsensor.png"
  - "sensor_speed_2.jpg"
  - "sensor_speed_3.jpg"

# SEO
description: "Датчик скорости вращения с частотным диапазоном 0-25 кГц и защитой IP68 для измерения скорости и контроля оборотов."
---

## Описание

Принцип действия данного датчика скорости вращения – бесконтактное магнитное сканирование.

Встроенное магнитное поле датчика изменяется при вращении целевого колеса. Сенсорная система датчика
записывает изменения в магнитном поле. Далее сигнал трансформируется в одиночный или двойной сигнал напряжения
прямоугольной или синусоидальной формы. Далее сигналы передаются к усиливающим устройствам через
специальный кабель.

Благодаря бесконтактному измерению вращения датчик скорости не требует постоянного технического
обслуживания и износоустойчив. 

## Фотографии

<div class="bg-light p-3 rounded mb-4">
  <div id="utudCarousel" class="carousel slide carousel-dark" data-bs-ride="carousel" data-bs-interval="5000" style="cursor: pointer;">
    <div class="carousel-inner rounded" style="height: 250px;">
      <div class="carousel-item active" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/Speedsensor.png">
        <img src="/tm-hugo/img/products/Speedsensor.png" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="Датчик скорости
">
      </div>
      <div class="carousel-item" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/sensor_speed_2.jpg">
        <img src="/tm-hugo/img/products/sensor_speed_2.jpg" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="Датчик скорости
">
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
      <tr><td><strong>Напряжение питания (Uв), В</strong></td><td>От 10 до 30</td></tr>
      <tr><td><strong>Номинальное потребление, мА</strong></td><td>≤25</td></tr>
      <tr><td><strong>Верхний порог выходного сигнала, В</strong></td><td>≥ Uв - 1.0</td></tr>
      <tr><td><strong>Нижний порог выходного сигнала, В</strong></td><td>≤ 1.0</td></tr>
      <tr><td><strong>Выходной ток (на канал), мА</strong></td><td>≤ 20</td></tr>
      <tr><td><strong>Диапазон частоты, кГц</strong></td><td>От 0 до 25</td></tr>
      <tr><td><strong>Скважность, %</strong></td><td>50 ± 20</td></tr>
      <tr><td><strong>Сдвиг фазы, град.</strong></td><td>90</td></tr>
      <tr><td><strong>Материал корпуса</strong></td><td>Нержавеющая сталь</td></tr>
      <tr><td><strong>Степень защиты корпуса со стороны сенсора, по ГОСТ 14254</strong></td><td>IP 68</td></tr>
      <tr><td><strong>Степень защиты корпуса со стороны кабеля, по ГОСТ 14254</strong></td><td>IP 68</td></tr>
      <tr><td><strong>Вибростойкость</strong></td><td>Категория 3 по ГОСТ 33787-2019</td></tr>
      <tr><td><strong>Ударостойкость</strong></td><td>Категория 3 по ГОСТ 33787-2019</td></tr>
      <tr><td><strong>Температура эксплуатации, °C</strong></td><td>От -40 оС до +105 оС</td></tr>
      <tr><td><strong>Материал целевой шестерни</strong></td><td>Ферромагнитная сталь</td></tr>
      <tr><td><strong>Ширина шестерни, мм</strong></td><td>≥10</td></tr>
      <tr><td><strong>Модуль шестерни</strong></td><td>1,5</td></tr>
      <tr><td><strong>Номинальный воздушный зазор, мм</strong></td><td>0,7</td></tr>
    </tbody>
  </table>
</div>


## Преимущества

<div class="row g-4 mb-4">
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Безопасное измерение скорости</h6>
        <p class="small">Определяет очень медленное вращение от 0 Гц без потери импульса, а также высокоскоростное до 25 кГц.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Защита IP68</h6>
        <p class="small">Полная герметичность для работы в агрессивной среде (пыль, влага, грязь).</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Широкий диапазон питания</h6>
        <p class="small">10–30 В — совместимо с бортовыми сетями тракторов и спецтехники.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Бесконтактный</h6>
        <p class="small">Износостойкий, не требует механического контакта с валом.</p>
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