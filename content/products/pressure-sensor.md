---
title: "Датчик давления и температуры"
fullName: "Датчик давления и температуры предназначен для измерения и преобразования избыточного
давления газообразных и жидких рабочих сред, а также температуры, в цифровой сигнал
интерфейса CAN. "
date: 2024-01-01
draft: false
weight: 

# Технические характеристики
partNumber:
pressureType: "избыточное"
measurementRange: "2,5; 16; 60 МПа"
overloadPressure: "4; 25; 70 МПа"
accuracy: "±1% или ±0,5%"
tempError: "0,15%/10°C"
temperature: "-40...+85°C"
mediumTemp: "-40...+100°C"
power: "9-33В"
thread: "M12x1,5"
connector: "DT04-6P / AMP Superseal 1,5 (282107-1)"
protection: "IP68"
output: "CAN (SAE J1939)"
emc: "ГОСТ 28751-90, ГОСТ 32141-2013"
material: "нержавеющая сталь, титановый сплав ВТ9"


# Категории и теги
categories: ["sensors"]
tags: ["давление", "температура"]
applications: ["Транспорт", "Сельхозтехника", "Спецтехника", "Телематика"]

# Изображения
images:
  - "/pressure-sensor.png"

# SEO
description: "Датчик давления и температуры предназначен для измерения и преобразования избыточного
давления газообразных и жидких рабочих сред, а также температуры, в цифровой сигнал
интерфейса CAN."
---

## Описание

**Датчик давления и температуры** предназначен для измерения и преобразования избыточного
давления газообразных и жидких рабочих сред, а также температуры, в цифровой сигнал
интерфейса CAN.

Датчик давления и температуры используется в системах управления и автоматики
автотракторной, дорожно-строительной и другой специализированной техники, автомобильного,
железнодорожного транспорта, нефтегазовой отрасли и других отраслях промышленности. 

## Фотографии

<div class="bg-light p-3 rounded mb-4">
  <div id="utudCarousel" class="carousel slide carousel-dark" data-bs-ride="carousel" data-bs-interval="5000" style="cursor: pointer;">
    <div class="carousel-inner rounded" style="height: 250px;">
      <div class="carousel-item active" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/pressure-sensor.png">
        <img src="/tm-hugo/img/products/pressure-sensor.png" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="Датчик давления и температуры">
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
    <tr><td><strong>Вид измеряемого давления</strong></td><td>Избыточное</td></tr>
    <tr><td><strong>Верхний придел измерения (ВПИ), МПа</strong></td><td>2,5; 16; 60</td></tr>
    <tr><td><strong>Давление перегрузки (длительно), МПа</strong></td><td>4; 25; 70</td></tr>
    <tr><td><strong>Предел допустимой основной приведённой погрешности не более, %</strong></td><td>1 или 0,5</td></tr>
    <tr><td><strong>Предел дополнительной приведённой температурной погрешности, %/10 °С</strong></td><td>0,15</td></tr>
    <tr><td><strong>Рабочая температура окружающей среды, °С</strong></td><td>от -40 до +85</td></tr>
    <tr><td><strong>Температура измеряемой среды, °С</strong></td><td>от -40 до +100</td></tr>
    <tr><td><strong>Напряжение электропитания, (однополярное, постоянный ток), В</strong></td><td>от 9 до 33</td></tr>
    <tr><td><strong>Резьба присоединительная к магистрали давления</strong></td><td>M12×1,5</td></tr>
    <tr><td><strong>Электрический соединитель</strong></td><td>Кабель с вилкой DT04-6P/ Кабель с вилкой AMP Superseal 1,5, типа 282107-1 (5 онтактов)</td></tr>
    <tr><td><strong>Класс пылевлагозащиты по ГОСТ 14254</strong></td><td>IP68</td></tr>
    <tr><td><strong>Выходной электрический сигнал</strong></td><td>CAN (SAE J1939)</td></tr>
    <tr><td><strong>ЭМС</strong></td><td>по ГОСТ 28751-90 ГОСТ 32141-2013</td></tr>
    <tr><td><strong>Материалы, контактирующие с рабочей (измеряемой) средой </strong></td><td>нержавеющая сталь, титановые сплав ВТ9</td></tr>
  </tbody>
</table>

</div>

## Преимущества

<div class="row g-4 mb-4">
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Надежность и долговечность</h6>
        <p class="small">Обеспечивается применением высокостабильных отечественных тензопреобразователей и современной микропроцессорной электроники.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Высокая точность в любых условиях</h6>
        <p class="small">Гарантирует стабильные и точные показания даже при экстремальных воздействиях: высоких температурах, вибрациях, механических, пневматических и гидравлических ударах.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Запас прочности</h6>
        <p class="small">Устойчив к значительным длительным и циклическим перегрузкам по давлению.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Надежная защита</h6>
        <p class="small">Обеспечивает надежную защиту приемника давления и температуры от прорыва рабочей среды. Класс защиты IP68.</p>
      </div>
    </div>
  </div>
  <div class="col-md-6 offset-md-3">
    <div class="card h-100 border-0 shadow-sm">
      <div class="card-body">
        <h6 class="fw-bold text-danger mb-2">Простота интеграции</h6>
        <p class="small">Легко встраивается в современные системы управления и автоматизации.</p>
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