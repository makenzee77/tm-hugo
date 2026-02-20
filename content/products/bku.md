---
title: "Блок контроля и управления"
fullName: "Предназначен для применения в системах управления строительной и сельскохозяйственной техникой в качестве устройства сбора информации от датчиков и выдачи управляющих сигналов различного назначения."
date: 2024-01-01
draft: false
weight: 20

# Технические характеристики
partNumber: 
power: "7-32В"
protection: "IP54"
interfaces: "CAN, USB, RS-485"
temperature: "-40...+70°C"
dimensions: "150x100x50 мм"
prodweight: "0.8 кг"

categories: ["processing"]
tags: ["БКУ", "CAN", "коммутация"]
applications: ["Транспорт", "Сельхозтехника"]

images:
  - "БКУ фронт.png"
  - "БКУ бок.png"

description: "БКУ-ПТЗ для систем управления техникой. IP54, -40...+70°C, CAN/USB/RS-485."
---

## Описание

**Блок контроля и управления** предназначен для применения в системах управления автотракторной техникой в качестве устройства сбора информации от датчиков и выдачи управляющих сигналов различного назначения. 

Он имеет как цифровые каналы связи с внешними объектами, так и возможность подключения широкого спектра аналоговых датчиков, что упрощает его интеграцию в уже существующие решения, значительно расширяя их функциональные возможности при минимальных затратах. 

Также имеет прочный металлический корпус, компактную конструкцию и степень защиты IP54 что позволяет интегрировать в существующие проекты без значительных изменений их дизайна.

## Фотографии

<div class="bg-light p-3 rounded mb-4">
  <div id="utudCarousel" class="carousel slide carousel-dark" data-bs-ride="carousel" data-bs-interval="5000" style="cursor: pointer;">
    <div class="carousel-inner rounded" style="height: 250px;">
      <div class="carousel-item active" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/БКУ фронт.png">
        <img src="/tm-hugo/img/products/БКУ фронт.png" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="БКУ">
      </div>
      <div class="carousel-item" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/БКУ бок.png">
        <img src="/tm-hugo/img/products/БКУ бок.png" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="БКУ">
      </div>
      <div class="carousel-item" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/bku.jpg">
        <img src="/tm-hugo/img/products/bku.jpg" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="БКУ">
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
      <tr><td><strong>Напряжение питания</strong></td><td>7–32 В</td></tr>
      <tr><td><strong>Потребляемая мощность (без включенных нагрузок)</strong></td><td>Не более 20 Вт </td></tr>
      <tr><td><strong>Поддерживаемые цифровые интерфейсы</strong></td><td>CAN 4 шт.</td></tr>
      <tr><td><strong>Универсальные входы (напр., сопротивление)</strong></td><td>20 шт.</td></tr>
      <tr><td><strong>Частотные входы</strong></td><td>10 шт.</td></tr>
      <tr><td><strong>Релейные входы (масса/питание)</strong></td><td>40 шт.</td></tr>
      <tr><td><strong>Релейные выходы (до 3 А)</strong></td><td>4 шт.</td></tr>
      <tr><td><strong>Выходы ШИМ (до 3 А)</strong></td><td>28 шт.</td></tr>
      <tr><td><strong>RS-485</strong></td><td>1 шт.</td></tr>
      <tr><td><strong>Защита</strong></td><td>IP65 (при подключенных разъемах)</td></tr>
      <tr><td><strong>Температура окружающей среды рабочая</strong></td><td>от -40°С до +70°С </td></tr>
      <tr><td><strong>Масса</strong></td><td>Не более 1.5 кг</td></tr>
    </tbody>
  </table>
</div>

<div class="alert alert-danger bg-danger bg-opacity-10 border-danger mt-4" role="alert">
  <strong class="text-danger">Индивидуальные решения:</strong> Возможны другие исполнения по количеству входов и выходов.
</div>

## Преимущества

<div class="row g-4 mb-4">
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Три процессора</h6>
        <p class="small">Реализация затратных алгоритмов обработки данных для обеспечения помехоустойчивости каналов измерения и управления.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">4 независимых CAN интерфейса</h6>
        <p class="small">Гибкая интеграция в существующие СУ и масштабируемость решений в широком диапазоне задач.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Множество входов</h6>
        <p class="small">20 универсальных аналоговых входов и 40 универсальных дискретных входов.</p>
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
- [Тех. паспорт (PDF)](/docs/BKU.pdf)
- [Руководство (PDF)](/docs/BKU-manual.pdf)
-->