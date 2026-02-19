---
title: "Селектор АКПП"
fullName: "Предназначен для обеспечения управления контроллером автоматической коробки передач
возможна адаптация к используемым у потребителя, например фирмы Allison или контроллера АКПП
собственного производства."
date: 2024-01-07
draft: false
weight: 70

# Технические характеристики
compatibility: "Коробки Allison"
durability: "1 млн циклов переключения"
interface: "CAN"
protection: "IP54"
temperature: "-40...+65°C"

# Категории и теги
categories: ["controllers"]
tags: ["селектор", "АКПП", "Allison", "CAN"]
applications: ["Автобусы", "Грузовики", "Спецтехника"]

# Изображения
images:
  - "АКПП.png"
  - "selector_akpp_2.jpg"
  - "selector_akpp_3.jpg"

# SEO
description: "Селектор АКПП для коробок Allison с ресурсом 1 млн циклов и CAN интерфейсом для автобусов, грузовиков и спецтехники."
---

## Описание

**Селектор АКПП** предназначен для обеспечения управления контроллером автоматической коробки передач
возможна адаптация к используемым у потребителя, например фирмы Allison или контроллера АКПП собственного
производства.

Габариты селектора АКПП позволяют вписывать его в существующие дизайн решения с минимальной доработкой
последних, а в ряде случаев и без. 


## Фотографии

<div class="bg-light p-3 rounded mb-4">
  <div id="utudCarousel" class="carousel slide carousel-dark" data-bs-ride="carousel" data-bs-interval="5000" style="cursor: pointer;">
    <div class="carousel-inner rounded" style="height: 250px;">
      <div class="carousel-item active" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/АКПП.png">
        <img src="/tm-hugo/img/products/АКПП.png" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="Селектор АКПП">
      </div>
      <div class="carousel-item" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/selector_akpp_2.jpg">
        <img src="/tm-hugo/img/products/selector_akpp_2.jpg" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="Селектор АКПП">
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
      <tr><td><strong>Напряжение питания</strong></td><td>От 8 до 32 В</td></tr>
      <tr><td><strong>Потребляемая мощность</strong></td><td>Не более 2 Вт </td></tr>
      <tr><td><strong>Интерфейс</strong></td><td>CAN</td></tr>
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
        <h6 class="fw-bold text-danger mb-2">Встроенный индикатор</h6>
        <p class="small">Наличие встроенного индикатора на который выводится информация о текущих режимах работы и, в случае возникновения при работе АКПП аварийных ситуаций, соответствующих сообщений. Это позволяет использовать данное устройство автономно с контроллером АКПП без подключения в внешней СУ.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Высокий ресурс</h6>
        <p class="small">Органы управления имеют ресурс нажатия более 1 000 000.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Защита IP54</h6>
        <p class="small">Степень защиты IP54 позволяет использовать его в открытом варианте.</p>
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