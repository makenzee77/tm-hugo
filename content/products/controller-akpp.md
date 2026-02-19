---
title: "Контроллер АКПП"
fullName: "Контроллер АКПП предназначен для обеспечения управления автоматической коробки передач, например фирмы Allison. Контроллер АКПП может работать как с селектором АКПП собственного производства, так и с устройствами
других производителей."
date: 2024-01-06
draft: false
weight: 60

# Технические характеристики
compatibility: "Коробки передач Allison"
interfaces: "CAN1, CAN2"
power: "8-32В"
protection: "IP54"
temperature: "-40...+65°C"

# Категории и теги
categories: ["controllers"]
tags: ["АКПП", "Allison", "CAN", "трансмиссия"]
applications: ["Коммерческий транспорт", "Спецтехника"]

# Изображения
images:
  - "controller_akpp_2.jpg"
  - "controller_akpp_3.jpg"

# SEO
description: "Контроллер АКПП для коробок передач Allison с двумя CAN интерфейсами для коммерческого транспорта и спецтехники."
---

## Описание

 **Контроллер АКПП** предназначен для обеспечения управления автоматической коробки передач, например фирмы
Allison.

Контроллер АКПП может работать как с селектором АКПП собственного производства, так и с устройствами других
производителей.

Габариты контроллера АКПП и его степень защиты позволяют при его компоновке на объекте выбирать место
оптимальное по кабельной сети. 


## Фотографии

<div class="bg-light p-3 rounded mb-4">
  <div id="utudCarousel" class="carousel slide carousel-dark" data-bs-ride="carousel" data-bs-interval="5000" style="cursor: pointer;">
    <div class="carousel-inner rounded" style="height: 250px;">
      <div class="carousel-item active" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/controller_akpp_2.jpg">
        <img src="/tm-hugo/img/products/controller_akpp_2.jpg" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="Контроллер АКПП">
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
      <tr><td><strong>Потребляемая мощность (без включенных нагрузок)</strong></td><td>Не более 10 Вт </td></tr>
      <tr><td><strong>Интерфейс</strong></td><td>CAN1, CAN2 </td></tr>
      <tr><td><strong>Степень защиты</strong></td><td>IP54</td></tr>
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
        <h6 class="fw-bold text-danger mb-2">Независимый CAN интерфейс</h6>
        <p class="small">Наличие дополнительного независимого CAN интерфейса позволяет интегрировать в существующую СУ без дополнительных устройств.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Непрерывная диагностика</h6>
        <p class="small">Ведется непрерывный анализ исправности подключенных датчиков и исполнительных устройств.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Защита IP54</h6>
        <p class="small">Степень защиты IP54, а также устойчивость к механическим воздействиям позволяет размещать его вне кабины.</p>
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