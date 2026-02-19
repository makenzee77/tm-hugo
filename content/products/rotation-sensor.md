---
title: "Датчик угла поворота"
fullName: "Датчик угла поворота"
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
  - "rotation2.png"

# SEO
description: ""
---

## Описание

**Датчик скорости вращения** — надежное решение для измерения скорости вращения валов, колес и других вращающихся элементов.

## Фотографии

<div class="bg-light p-3 rounded mb-4">
  <div id="utudCarousel" class="carousel slide carousel-dark" data-bs-ride="carousel" data-bs-interval="5000" style="cursor: pointer;">
    <div class="carousel-inner rounded" style="height: 250px;">
      <div class="carousel-item active" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/rotation2.png">
        <img src="/tm-hugo/img/products/rotation2.png" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="Датчик угла">
      </div>
      <div class="carousel-item" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/rotation3.png">
        <img src="/tm-hugo/img/products/rotation3.png" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="Датчик угла">
      </div>
      <div class="carousel-item" style="height: 250px;" data-bs-toggle="modal" data-bs-target="#imageModal" data-img="/tm-hugo/img/products/rotation4.png">
        <img src="/tm-hugo/img/products/rotation4.png" class="d-block w-100 h-100 rounded" style="object-fit: contain;" alt="Датчик угла">
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



## Преимущества



## Видеопрезентация

<div class="ratio ratio-16x9 mb-4">
  <iframe src="https://www.youtube.com/embed/VIDEO_ID_HERE" title="УТУД - Видеопрезентация" allowfullscreen></iframe>
</div>

---

## Документация
- [Тех. паспорт (PDF)](/docs/BKU-datasheet.pdf)
- [Руководство (PDF)](/docs/BKU-manual.pdf)

