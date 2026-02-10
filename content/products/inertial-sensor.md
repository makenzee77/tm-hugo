---
title: "Модуль инерциальный"
fullName: "Считывает измерения с векторных датчиков, преобразует их в цифровой формат и обеспечивает вывод оцифрованных измерений из модуля через какой-либо стандартный цифровой интерфейс передачи данных."
date: 2024-01-01
draft: false
weight: 30

# Технические характеристики
partNumber: ""
accuracy: "±0.05°"
stability: "1°/час"
power: "24В"
protection: "IP67"
interfaces: "CAN"
temperature: "-60...+60°C"
dimensions: "116x60x28 мм"
prodweight: "0.45 кг"

# Категории и теги
categories: ["sensors"]
tags: ["IMU", "инерциальный датчик", "навигация", "угловая скорость", "ускорение"]
applications: ["Навигация", "Сельхозтехника", "Авиация", "Робототехника", "Автомобилестроение"]

# Изображения
images:
  - "/Инерциальный.png"

# SEO
description: "Инерциальный измерительный модуль (IMU) с высокой точностью ±0.05° и стабильностью 1°/час. Для навигационных систем, сельхозтехники и промышленной автоматики."
---

## Описание

**Инерциальный измерительный модуль** состоит из векторных датчиков угловой скорости и линейного ускорения, а также электронной схемы управления, жёстко смонтированных на общем основании. Схема считывает измерения с векторных датчиков, преобразует их в цифровой формат и обеспечивает вывод оцифрованных измерений через стандартный цифровой интерфейс передачи данных CAN.

Оси чувствительности каждого векторного датчика образуют базис механической сборки модуля. С модулем связана правая ортогональная измерительная система координат, начало которой называется измерительным центром. При сборке модуля номинальные направления осей чувствительности векторных датчиков устанавливают сонаправлено с одноимёнными осями измерительной системы координат.

## Фотографии

<div class="bg-light p-3 rounded mb-4">
  <div id="imuCarousel" class="carousel slide carousel-dark" data-bs-ride="carousel" data-bs-interval="5000">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#imuCarousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Слайд 1"></button>
      <button type="button" data-bs-target="#imuCarousel" data-bs-slide-to="1" aria-label="Слайд 2"></button>
    </div>
    <div class="carousel-inner rounded">
      <div class="carousel-item active">
        <img src="/tm-hugo/img/products/Инерциальный.png" class="d-block w-100 rounded" alt="Инерциальный датчик - общий вид">
      </div>
      <div class="carousel-item">
        <img src="/tm-hugo/img/products/Инерциальный вектор.png" class="d-block w-100 rounded" alt="Инерциальный датчик - установка">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#imuCarousel" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Предыдущий</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#imuCarousel" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Следующий</span>
    </button>
  </div>
</div>

## Характеристики

<div class="table-responsive">
  <table class="table table-sm table-striped">
    <tbody>
      <tr><td><strong>Принцип измерений</strong></td><td>Инерциальные измерения</td></tr>
      <tr><td><strong>Обмен данными</strong></td><td>CAN</td></tr>
      <tr><td><strong>Питание, В</strong></td><td>24</td></tr>
      <tr><td><strong>Защита</strong></td><td>IP67</td></tr>
      <tr><td><strong>Габариты (ДхШхВ), не более, мм</strong></td><td>116х60х28</td></tr>
      <tr><td><strong>Масса, не более, кг</strong></td><td>0,45</td></tr>
      <tr><td><strong>Материал корпуса модуля</strong></td><td>Д16</td></tr>
      <tr><td><strong>Диапазон температур эксплуатации, оС</strong></td><td>от – 60 до +60 
</td></tr>
      <tr><td><strong>Кратковременная стабильность</strong></td><td>1 °/час</td></tr>
      <tr><td><strong>Погрешность измерения </strong></td><td>±0,05 ⁰</td></tr>
    </tbody>
  </table>
</div>

## Преимущества

<div class="row g-4 mb-4">
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Высокая точность</h6>
        <p class="small">Погрешность измерения ±0,05° позволяет получать очень точные данные о положении и ориентации, что особенно важно в приложениях, требующих высокой точности, таких как навигация, робототехника и в сельхозтехнике.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Надежность в динамичных условиях</h6>
        <p class="small">Кратковременная стабильность 1°/час обеспечивает стабильные измерения даже при изменениях в окружающей среде или во время движения, что критично для приложений в реальном времени.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Широкий диапазон применения</h6>
        <p class="small">Такие датчики могут быть использованы в различных областях, включая авиацию, автомобилестроение, судостроение и мобильные технологии, где необходима высокая точность и надежность.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Снижение ошибок при долгосрочных измерениях</h6>
        <p class="small">Высокая стабильность позволяет минимизировать накопление ошибок при длительных замерах, что особенно важно в навигационных системах.</p>
      </div>
    </div>
  </div>
</div>

---

## Видеопрезентация

<div class="ratio ratio-16x9 mb-4">
  <iframe src="https://www.youtube.com/embed/VIDEO_ID_HERE" title="УТУД - Видеопрезентация" allowfullscreen></iframe>
</div>

---

## Документация
- [Тех. паспорт (PDF)](/docs/BKU-datasheet.pdf)
- [Руководство (PDF)](/docs/BKU-manual.pdf)
