---
title: "Дисплей универсальный транспортный управляющий"
fullName: "Предназначен для управления строительной и сельскохозяйственной техникой, прецизионного вождения, нивелирования и реализации прочих интеллектуальных функций."
date: 2024-01-01
draft: false
weight: 10

# Технические характеристики
partNumber:
processor: "iMX8M Plus ARM Cortex-A53, 1.6GHz"
memory: "4GB LPDDR4, 16GB eMMC"
video: "1920x1080, 1280x720"
gnss: "GPS/ГЛОНАСС L1/L2, RTK"
interfaces: "USB 3.0, USB 2.0, Ethernet, 3xCAN, WiFi, Bluetooth 5.2"
power: "7-36В"
protection: "IP65"
temperature: "-40...+65°C"
dimensions: "265x173x52 мм"
prodweight: "1.5 кг"

# Категории и теги
categories: ["displays"]
tags: ["УТУД", "GPS", "ГЛОНАСС", "CAN"]
applications: ["Транспорт", "Сельхозтехника", "Спецтехника", "Телематика"]

# Изображения
images:
  - "/tractor3.png"

# SEO
description: "Дисплей универсальный транспортный управляющий УТУД с GPS/ГЛОНАСС навигацией, процессором iMX8M Plus и множественными интерфейсами для транспорта и сельхозтехники."
---

## Общее описание

**Дисплей универсальный транспортный управляющий** предназначен для управления строительной и сельскохозяйственной техникой, прецизионного вождения, нивелирования и интеллектуальных функций.

**Общие преимущества всех исполнений:**
- Экран высокой яркости с тач-скрином и автонастройкой
- Мощный процессор iMX8M Plus 1.6 GHz, 4 GB RAM
- Множество интерфейсов: 3×CAN, USB, Ethernet, Wi-Fi, 4G, Bluetooth
- GNSS L1/L2 (опция RTK), 4 видеовхода
- IP65, -40...+65°C, обновление ПО удалённо

## Фотографии

<div class="bg-light p-3 rounded mb-4">
  <div id="utudCarousel" class="carousel slide carousel-dark" data-bs-ride="carousel" data-bs-interval="5000" style="cursor: pointer;">
    <div class="carousel-inner rounded" style="height: 250px;">
      <div class="carousel-item active" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/tractor3.png">
        <img src="/tm-hugo/img/products/tractor3.png" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="УТУД">
      </div>
      <div class="carousel-item" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/utud_back.png">
        <img src="/tm-hugo/img/products/utud_back.png" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="УТУД">
      </div>
      <div class="carousel-item" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/grader.jpg">
        <img src="/tm-hugo/img/products/grader.jpg" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="УТУД">
      </div>
      <div class="carousel-item" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/tractor.jpg">
        <img src="/tm-hugo/img/products/tractor.jpg" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="УТУД">
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

## Варианты исполнения
Выберите конфигурацию для просмотра технических характеристик:



<ul class="nav nav-pills mb-4 gap-2 flex-wrap" id="variantTabs" role="tablist">
  <li class="nav-item" role="presentation">
    <button class="btn btn-outline-danger active" id="grader2d-tab" data-bs-toggle="pill" data-bs-target="#grader2d" type="button" role="tab">2D Грейдер</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="btn btn-outline-danger" id="grader3d-tab" data-bs-toggle="pill" data-bs-target="#grader3d" type="button" role="tab">3D Грейдер</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="btn btn-outline-danger" id="tractor-tab" data-bs-toggle="pill" data-bs-target="#tractor" type="button" role="tab">Трактор</button>
  </li>
  <li class="nav-item" role="presentation">
    <button class="btn btn-outline-danger" id="sprayer-tab" data-bs-toggle="pill" data-bs-target="#sprayer" type="button" role="tab">Опрыскиватель</button>
  </li>
</ul>


<div class="tab-content" id="configTabContent">
  
  <!-- 2D Грейдер -->
  <div class="tab-pane fade show active" id="grader2d" role="tabpanel" aria-labelledby="grader2d-tab">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title fw-bold text-danger mb-3">2D Грейдер</h5>
        <p class="card-text mb-4">Базовая конфигурация для 2D-нивелирования грейдеров. GNSS L1, 2×CAN, видео с камер.</p>
        <h6 class="mt-3 mb-3">Технические характеристики:</h6>
        <table class="table table-sm table-striped">
          <tbody>
            <tr><td><strong>Артикул</strong></td><td>РСДТ.453891.001-19</td></tr>
            <tr><td><strong>GNSS</strong></td><td>L1 (GPS/ГЛОНАСС/BeiDou)</td></tr>
            <tr><td><strong>CAN</strong></td><td>1 канал</td></tr>
            <tr><td><strong>Видео</strong></td><td>2 канала CVBS</td></tr>
            <tr><td><strong>4G модем</strong></td><td>SIM7600 + внешняя SIM</td></tr>
            <tr><td><strong>Защита</strong></td><td>IP65</td></tr>
            <tr><td><strong>Инерциальный датчик</strong></td><td>Да</td></tr>
          </tbody>
        </table>
        <div class="mt-4 p-3 bg-light rounded">
          <h6><i class="fas fa-check-circle text-success me-2"></i>Применение:</h6>
          <ul class="small">
            <li>2D-нивелирование с постоянным уклоном</li>
            <li>Планировка площадок</li>
            <li>Профилирование откосов</li>
          </ul>
        </div>
      </div>
    </div>
  </div>

  <!-- 3D Грейдер -->
  <div class="tab-pane fade" id="grader3d" role="tabpanel" aria-labelledby="grader3d-tab">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title fw-bold text-danger mb-3">3D Грейдер</h5>
        <p class="card-text mb-4">Расширенная версия для 3D-профилирования. Двойной GNSS L1/L2 + RTK, 3×CAN.</p>
        <h6 class="mt-3 mb-3">Технические характеристики:</h6>
        <table class="table table-sm table-striped">
          <tbody>
            <tr><td><strong>Артикул</strong></td><td>РСДТ.453891.001-04</td></tr>
            <tr><td><strong>GNSS</strong></td><td>2×L1/L2 UM982 + RTK модем</td></tr>
            <tr><td><strong>CAN</strong></td><td>3 канала</td></tr>
            <tr><td><strong>Видео</strong></td><td>4 канала CVBS</td></tr>
            <tr><td><strong>Ethernet</strong></td><td>Да</td></tr>
            <tr><td><strong>Защита</strong></td><td>IP65</td></tr>
            <tr><td><strong>Точность RTK</strong></td><td>±2 см</td></tr>
          </tbody>
        </table>
        <div class="mt-4 p-3 bg-light rounded">
          <h6><i class="fas fa-check-circle text-success me-2"></i>Применение:</h6>
          <ul class="small">
            <li>3D-профилирование по цифровой модели</li>
            <li>Строительство дорог по проекту</li>
            <li>Сложные инженерные поверхности</li>
          </ul>
        </div>
      </div>
    </div>
  </div>

  <!-- Трактор -->
  <div class="tab-pane fade" id="tractor" role="tabpanel" aria-labelledby="tractor-tab">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title fw-bold text-danger mb-3">Трактор</h5>
        <p class="card-text mb-4">Специальное исполнение для тракторов. GNSS L2, инерциальный датчик.</p>
        <h6 class="mt-3 mb-3">Технические характеристики:</h6>
        <table class="table table-sm table-striped">
          <tbody>
            <tr><td><strong>Артикул</strong></td><td>РСДТ.453891.001-10</td></tr>
            <tr><td><strong>GNSS</strong></td><td>L2 UBLOX (1 антенна)</td></tr>
            <tr><td><strong>CAN</strong></td><td>2 канала</td></tr>
            <tr><td><strong>Защита</strong></td><td>IP65</td></tr>
            <tr><td><strong>Инерциальный датчик</strong></td><td>Да</td></tr>
            <tr><td><strong>Аудио</strong></td><td>Внутреннее + внешнее</td></tr>
            <tr><td><strong>FM-радио</strong></td><td>Да</td></tr>
          </tbody>
        </table>
        <div class="mt-4 p-3 bg-light rounded">
          <h6><i class="fas fa-check-circle text-success me-2"></i>Применение:</h6>
          <ul class="small">
            <li>Параллельное вождение тракторов</li>
            <li>Точное земледелие</li>
            <li>Контроль секций навесного оборудования</li>
          </ul>
        </div>
      </div>
    </div>
  </div>

  <!-- Опрыскиватель -->
  <div class="tab-pane fade" id="sprayer" role="tabpanel" aria-labelledby="sprayer-tab">
    <div class="card">
      <div class="card-body">
        <h5 class="card-title fw-bold text-danger mb-3">Опрыскиватель</h5>
        <p class="card-text mb-4">Для точного земледелия и опрыскивателей. Двойной GNSS L2 + RTK, IP65.</p>
        <h6 class="mt-3 mb-3">Технические характеристики:</h6>
        <table class="table table-sm table-striped">
          <tbody>
            <tr><td><strong>Артикул</strong></td><td>РСДТ.453891.001-08 (18, 03)</td></tr>
            <tr><td><strong>GNSS</strong></td><td>2×L2 GNSS + RTK модем</td></tr>
            <tr><td><strong>CAN</strong></td><td>3 канала</td></tr>
            <tr><td><strong>Видео</strong></td><td>4 канала CVBS + CSI камера</td></tr>
            <tr><td><strong>Защита</strong></td><td>IP65</td></tr>
            <tr><td><strong>Аудио</strong></td><td>Внутреннее + внешнее</td></tr>
            <tr><td><strong>Масса</strong></td><td>2 кг</td></tr>
          </tbody>
        </table>
        <div class="mt-4 p-3 bg-light rounded">
          <h6><i class="fas fa-check-circle text-success me-2"></i>Применение:</h6>
          <ul class="small">
            <li>Секционное отключение опрыскивателей</li>
            <li>Дифференцированное внесение</li>
            <li>Параллельное вождение ±2 см</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="alert alert-danger bg-danger bg-opacity-10 border-danger mt-4" role="alert">
  <strong class="text-danger">Индивидуальные решения:</strong> Возможно изготовление других исполнений под ваши требования.
</div>




## Преимущества

<div class="row mt-4 mb-4">
  <div class="col-md-6">
    <div class="card h-100">
      <div class="card-body">
        <h5 class="card-title">Мощная платформа</h5>
        <p class="card-text">Процессор iMX8M Plus с частотой 1.6 GHz и 4 GB оперативной памяти обеспечивает высокую производительность для выполнения сложных алгоритмов управления и обработки данных в реальном времени.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100">
      <div class="card-body">
        <h5 class="card-title">Универсальная связность</h5>
        <p class="card-text">Множество интерфейсов (3×CAN, USB, Ethernet, Wi-Fi, Bluetooth, 4G) обеспечивает интеграцию с любым оборудованием и возможность удаленного мониторинга и управления.</p>
      </div>
    </div>
  </div>
</div>

<div class="row mb-4">
  <div class="col-md-6">
    <div class="card h-100">
      <div class="card-body">
        <h5 class="card-title">Мультикамерная система</h5>
        <p class="card-text">Одновременное отображение видео с 4 аналоговых камер обеспечивает полный обзор вокруг техники. Опциональная фронтальная камера для видеофиксации и распознавания объектов.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100">
      <div class="card-body">
        <h5 class="card-title">Работа в экстремальных условиях</h5>
        <p class="card-text">Диапазон рабочих температур от -40°C до +65°C, степень защиты до IP65 и яркий дисплей с автоподстройкой обеспечивают надежную работу в любых условиях.</p>
      </div>
    </div>
  </div>
</div>

## Видеопрезентация

<div class="ratio ratio-16x9 mb-4">
  <iframe src="https://www.youtube.com/embed/VIDEO_ID_HERE" title="УТУД - Видеопрезентация" allowfullscreen></iframe>
</div>

---

**Для получения подробной информации, технических консультаций или оформления заказа свяжитесь с нашими специалистами:**

📞 **Телефон**: +7 (932) 617-76-22  
📧 **Email**: [info@precisionmachines.pro](mailto:info@precisionmachines.pro)

<!--
## Документация

- [Тех. паспорт (PDF)](/docs/BKU-datasheet.pdf)
- [Руководство (PDF)](/docs/BKU-manual.pdf)
-->