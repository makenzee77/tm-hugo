# АО «Точные машины» — Официальный сайт

![Логотип](static/img/logo.svg)

**Точность. Стабильность. Интеллект.**

Добро пожаловать на официальный сайт компании «Точные машины» — ведущего производителя высокоточного промышленного оборудования и систем управления.

## 🚀 О компании

АО «Точные машины» специализируется на разработке и производстве высокотехнологичного промышленного электронного оборудования для:

- **🌾 Сельского хозяйства** — системы точного земледелия
- **🏗️ Строительства** — системы точного нивелирования  
- **⚡ Силовых установок** — векторное управление двигателями до 100 кВт

## 📦 Продукция

### 🎛️ Системы управления и контроля
- **УТУД-ПТЗ** — универсальное устройство обработки данных
- **УТУД-РСМ** — устройство для удаленного мониторинга
- **БКУ-ПТЗ** — блок коммутации универсальный
- **Контроллеры АКПП** — управление автоматическими трансмиссиями

### 📊 Дисплеи и системы индикации
- **Цифровые приборные панели** — современные решения для отображения
- **Промышленные дисплеи** — надежные экраны для тяжелых условий

### 🔧 Датчики и измерительные приборы
- **Инерциальные датчики** — измерение углов и ускорений
- **Датчики скорости** — контроль скорости вращения
- **Энкодеры** — точное измерение положения

### 🚜 Сельскохозяйственное оборудование
- **УТУД для тракторов** — специализированные терминалы
- **УТУД сельхозка** — решения для сельхозтехники
- **Контроллеры секций** — управление опрыскивателями и сеялками

### 🔧 Исполнительные механизмы
- **Электромагнитные клапаны** — быстродействующие клапаны
- **Пульты управления** — эргономичные решения

## 🏆 Наши преимущества

- ✅ **Промышленное качество** — защита IP54–IP67
- ✅ **Широкий температурный диапазон** — работа при -40°C…+70°C  
- ✅ **Точная навигация** — GPS/ГЛОНАСС L1/L2 с RTK
- ✅ **Современные интерфейсы** — CAN, USB, Ethernet, WiFi, Bluetooth

## 🛠️ Технические возможности

### Навигационные системы
- **GPS/ГЛОНАСС L1/L2** с поддержкой RTK
- Точность позиционирования до **2 см**
- Интеграция с различными системами управления

### Интерфейсы и связь
- **CAN 2.0B, J1939** — промышленные протоколы
- **Ethernet 10/100** — сетевые подключения
- **WiFi, Bluetooth 5.2** — беспроводная связь
- **USB 3.0/2.0** — универсальные порты

### Процессорные платформы
- **iMX8M Plus ARM Cortex-A53** — высокая производительность
- **4GB LPDDR4, 16GB eMMC** — достаточно памяти
- Поддержка **Linux** и специализированных ОС

## 📊 Статистика продукции

```
🎛️ Системы управления:     15+ моделей
📊 Дисплеи и панели:       8+ моделей  
🔧 Датчики и приборы:      12+ моделей
🚜 Сельхозоборудование:    10+ моделей
```

## 🏭 Производство и качество

### Сертификация
- **ISO 9001** — система менеджмента качества
- **ТР ТС** — технические регламенты Таможенного союза
- **CE** — европейские стандарты безопасности
- **ГОСТ Р** — российские государственные стандарты

### Испытания
- Климатические испытания (-40°C до +85°C)
- Вибростойкость до 30g
- Защита от пыли и влаги (IP54-IP67)
- Электромагнитная совместимость

## 🌐 Сайт на HUGO

Этот сайт создан с использованием генератора статических сайтов **Hugo** и включает:

- ⚡ **Быструю загрузку** — статическая генерация
- 📱 **Адаптивный дизайн** — работает на всех устройствах
- 🔍 **SEO-оптимизацию** — хорошая индексация поисковиками
- 📝 **Markdown контент** — легкое редактирование продуктов
- 🎨 **Современный дизайн** — Bootstrap 5 + собственные стили

### Структура проекта

```
hugo-site/
├── config.yaml              # Конфигурация HUGO
├── content/                  # Контент сайта
│   ├── _index.md            # Главная страница
│   ├── about.md             # О компании
│   ├── contacts.md          # Контакты
│   └── products/            # Продукты
│       ├── _index.md        # Каталог продуктов
│       ├── utud-ptz.md      # Отдельные страницы продуктов
│       └── ...
├── layouts/                 # Шаблоны
│   ├── _default/
│   ├── index.html
│   └── products/
├── static/                  # Статические файлы
│   ├── css/
│   ├── js/
│   └── img/
└── README.md               # Этот файл
```

## 🚀 Запуск и разработка

### Требования
- Hugo Extended v0.100.0+
- Git

### Локальная разработка
```bash
# Клонировать репозиторий
git clone <repository-url>
cd hugo-site

# Запустить локальный сервер
hugo server -D

# Сайт будет доступен по адресу http://localhost:1313
```

### Сборка для продакшена
```bash
# Собрать статические файлы
hugo --minify

# Файлы будут в папке public/
```

## 📝 Редактирование контента

### Добавление нового продукта

1. Создайте новый файл в `content/products/`
2. Используйте следующий шаблон:

```yaml
---
title: "Название продукта"
fullName: "Полное название"
date: 2024-01-01
draft: false

# Технические характеристики
processor: "Процессор"
memory: "Память"
power: "Питание"
protection: "Защита"
temperature: "Температура"

# Категории и теги
categories: ["category"]
tags: ["tag1", "tag2"]
applications: ["Применение 1", "Применение 2"]

# Изображения
images:
  - "image1.jpg"
  - "image2.jpg"

description: "Описание для SEO"
---

# Содержимое страницы продукта

Подробное описание продукта...
```

### Редактирование существующих страниц

- **Главная страница**: `content/_index.md`
- **О компании**: `content/about.md`  
- **Контакты**: `content/contacts.md`
- **Продукты**: файлы в `content/products/`

## 📞 Контакты

**АО «Точные машины»**
- 📍 **Адрес**: 620078, Свердловская область, г. Екатеринбург, ул. Малышева, стр. 122, литер К
- 📞 **Телефон**: +7(932)617-76-22
- 📧 **Email**: info@precisionmachines.pro
- 🌐 **Сайт**: https://precisionmachines.pro

### Реквизиты
- **ИНН**: 6670518046
- **КПП**: 667001001  
- **ОГРН**: 1236600048937

---

## 🤝 Сотрудничество

Мы открыты для сотрудничества с:
- Производителями техники
- Системными интеграторами
- Дистрибьюторами
- Научными организациями

**Свяжитесь с нами для обсуждения возможностей партнерства!**

---

*© 2024 АО «Точные машины». Все права защищены.*
```
tm-hugo
├─ .hugo_build.lock
├─ config.yaml
├─ content
│  ├─ about.md
│  ├─ contacts.md
│  ├─ products
│  │  ├─ autosteer-tractor.md
│  │  ├─ bku-ptz.md
│  │  ├─ control-panel.md
│  │  ├─ controller-akpp.md
│  │  ├─ controller-fan.md
│  │  ├─ controller-section.md
│  │  ├─ digital-dashboard.md
│  │  ├─ electromagnetic-valve.md
│  │  ├─ encoder-block.md
│  │  ├─ inertial-sensor.md
│  │  ├─ leveling-grader.md
│  │  ├─ rotation-sensor.md
│  │  ├─ selector-akpp.md
│  │  ├─ speed-sensor.md
│  │  ├─ sprayer-automation.md
│  │  ├─ steering-device.md
│  │  ├─ utud-ptz.md
│  │  └─ _index.md
│  ├─ solutions.md
│  └─ _index.md
├─ layouts
│  ├─ categories
│  │  ├─ list.html
│  │  ├─ single.html
│  │  └─ term.html
│  ├─ index.html
│  ├─ partials
│  │  ├─ category-description.html
│  │  ├─ category-icon.html
│  │  ├─ category-title.html
│  │  ├─ product-card.html
│  │  └─ product-specs-brief.html
│  ├─ products
│  │  ├─ list.html
│  │  └─ single.html
│  └─ _default
│     ├─ baseof.html
│     ├─ single.html
│     ├─ solutions.html
│     └─ taxonomy.html
├─ public
│  ├─ about
│  │  └─ index.html
│  ├─ applications
│  │  ├─ index.html
│  │  ├─ index.xml
│  │  ├─ авиация
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ автобусы
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ автоматизация
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ автомобилестроение
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ автопилот
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ вентиляция
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ внесение-удобрений
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ гидросистемы
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ грейдирование
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ грузовики
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ дорожное-строительство
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ защита-растений
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ измерение-скорости
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ измерение-углов-поворота
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ комбайны
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ коммерческий-транспорт
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ контроль-оборотов
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ навигация
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ опрыскивание
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ опрыскиватели
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ планировка
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ посевные-работы
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ профилирование
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ робототехника
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ сельхозтехника
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ сеялки
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ системы-охлаждения
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ системы-позиционирования
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ спецтехника
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ строительная-техника
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ телематика
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ точное-земледелие
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ тракторы
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  └─ транспорт
│  │     ├─ index.html
│  │     └─ index.xml
│  ├─ categories
│  │  ├─ actuators
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ controllers
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ displays
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ index.html
│  │  ├─ index.xml
│  │  ├─ kits
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ processing
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  ├─ sensors
│  │  │  ├─ index.html
│  │  │  └─ index.xml
│  │  └─ switching
│  │     ├─ index.html
│  │     └─ index.xml
│  ├─ contacts
│  │  └─ index.html
│  ├─ css
│  │  └─ style.css
│  ├─ img
│  │  ├─ generated-image.png
│  │  ├─ generated-image1.png
│  │  ├─ logo.svg
│  │  ├─ m-bg.svg
│  │  ├─ outline-tech-heavy.svg
│  │  ├─ outline-tech.svg
│  │  ├─ products
│  │  │  ├─ 2D_scheme.png
│  │  │  ├─ 3D_scheme.png
│  │  │  ├─ bku_2.jpg
│  │  │  ├─ bku_ptz_1.jpg
│  │  │  ├─ BVO.jpg
│  │  │  ├─ controller_akpp_2.jpg
│  │  │  ├─ controller_fan_2.jpg
│  │  │  ├─ controller_section_2.jpg
│  │  │  ├─ control_panel_2.jpg
│  │  │  ├─ digital_dashboard_1.jpg
│  │  │  ├─ digital_dashboard_2.jpg
│  │  │  ├─ display_2.jpg
│  │  │  ├─ display_3.jpg
│  │  │  ├─ encoder_1.jpg
│  │  │  ├─ encoder_2.jpg
│  │  │  ├─ grader.jpg
│  │  │  ├─ image.png
│  │  │  ├─ k6.jpg
│  │  │  ├─ ppu_2.jpg
│  │  │  ├─ rotation.png
│  │  │  ├─ rotation2.png
│  │  │  ├─ rotation3.png
│  │  │  ├─ rotation4.png
│  │  │  ├─ scheme_2D.png
│  │  │  ├─ scheme_3D.png
│  │  │  ├─ selector_akpp_1.jpg
│  │  │  ├─ selector_akpp_2.jpg
│  │  │  ├─ sensor_inertial_1.jpg
│  │  │  ├─ sensor_inertial_2.jpg
│  │  │  ├─ sensor_inertial_3.jpg
│  │  │  ├─ sensor_speed_1.jpg
│  │  │  ├─ sensor_speed_2.jpg
│  │  │  ├─ Speedsensor.png
│  │  │  ├─ sprayer.jpg
│  │  │  ├─ steering_device_1.jpg
│  │  │  ├─ steering_device_2.jpg
│  │  │  ├─ tractor.jpg
│  │  │  ├─ tractor3.png
│  │  │  ├─ utud_agro_2.jpg
│  │  │  ├─ utud_ptz_2.jpg
│  │  │  ├─ utud_ptz_2.png
│  │  │  ├─ utud_ptz_4.jpg
│  │  │  ├─ Valve2.png
│  │  │  ├─ valve_2.jpg
│  │  │  ├─ АКПП.png
│  │  │  ├─ БКУ бок.png
│  │  │  ├─ БКУ фронт.png
│  │  │  ├─ грейдер.jpg
│  │  │  ├─ Группа 1.png
│  │  │  ├─ Дисплей тыл.png
│  │  │  ├─ Дисплей фронт.png
│  │  │  ├─ Инерциальный вектор.png
│  │  │  ├─ Инерциальный.png
│  │  │  ├─ Энкодер.png
│  │  │  └─ Энкодер2.png
│  │  ├─ truck-working-field-sunny-day (3).jpg
│  │  └─ АКПП.png
│  ├─ index.html
│  ├─ index.xml
│  ├─ products
│  │  ├─ autosteer-tractor
│  │  │  └─ index.html
│  │  ├─ bku-ptz
│  │  │  └─ index.html
│  │  ├─ control-panel
│  │  │  └─ index.html
│  │  ├─ controller-akpp
│  │  │  └─ index.html
│  │  ├─ controller-fan
│  │  │  └─ index.html
│  │  ├─ controller-section
│  │  │  └─ index.html
│  │  ├─ digital-dashboard
│  │  │  └─ index.html
│  │  ├─ electromagnetic-valve
│  │  │  └─ index.html
│  │  ├─ encoder-block
│  │  │  └─ index.html
│  │  ├─ index.html
│  │  ├─ index.xml
│  │  ├─ inertial-sensor
│  │  │  └─ index.html
│  │  ├─ leveling-grader
│  │  │  └─ index.html
│  │  ├─ rotation-sensor
│  │  │  └─ index.html
│  │  ├─ selector-akpp
│  │  │  └─ index.html
│  │  ├─ speed-sensor
│  │  │  └─ index.html
│  │  ├─ sprayer-automation
│  │  │  └─ index.html
│  │  ├─ steering-device
│  │  │  └─ index.html
│  │  └─ utud-ptz
│  │     └─ index.html
│  ├─ sitemap.xml
│  ├─ solutions
│  │  └─ index.html
│  └─ tags
│     ├─ 3d
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ allison
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ can
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ gnss
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ gps
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ imu
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ index.html
│     ├─ index.xml
│     ├─ isobus
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ pwm
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ rtk
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ section-control
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ автовождение
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ автоматизация
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ автопилот
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ акпп
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ бку
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ вентилятор
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ вращение
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ гидравлика
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ глонасс
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ грейдер
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ дорожное-строительство
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ инерциальный-датчик
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ клапан
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ коммутация
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ навигация
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ нивелирование
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ опрыскиватель
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ охлаждение
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ панель-приборов
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ подруливающее
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ позиционирование
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ пульт
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ рулевое-управление
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ секции
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ селектор
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ сельхозтехника
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ скорость
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ точное-земледелие
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ точность
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ трансмиссия
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ транспорт
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ угловая-скорость
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ управление
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ ускорение
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ утуд
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ цифровой-дисплей
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ частота
│     │  ├─ index.html
│     │  └─ index.xml
│     ├─ электромагнитный
│     │  ├─ index.html
│     │  └─ index.xml
│     └─ энкодер
│        ├─ index.html
│        └─ index.xml
├─ README.md
└─ static
   ├─ css
   │  └─ style.css
   └─ img
      ├─ generated-image.png
      ├─ generated-image1.png
      ├─ logo.svg
      ├─ m-bg.svg
      ├─ outline-tech-heavy.svg
      ├─ outline-tech.svg
      ├─ products
      │  ├─ 2D_scheme.png
      │  ├─ 3D_scheme.png
      │  ├─ bku_2.jpg
      │  ├─ bku_ptz_1.jpg
      │  ├─ BVO.jpg
      │  ├─ controller_akpp_2.jpg
      │  ├─ controller_fan_2.jpg
      │  ├─ controller_section_2.jpg
      │  ├─ control_panel_2.jpg
      │  ├─ digital_dashboard_1.jpg
      │  ├─ digital_dashboard_2.jpg
      │  ├─ display_2.jpg
      │  ├─ display_3.jpg
      │  ├─ encoder_1.jpg
      │  ├─ encoder_2.jpg
      │  ├─ grader.jpg
      │  ├─ k6.jpg
      │  ├─ ppu_2.jpg
      │  ├─ rotation.png
      │  ├─ rotation2.png
      │  ├─ rotation3.png
      │  ├─ rotation4.png
      │  ├─ scheme_2D.png
      │  ├─ scheme_3D.png
      │  ├─ selector_akpp_1.jpg
      │  ├─ selector_akpp_2.jpg
      │  ├─ sensor_inertial_1.jpg
      │  ├─ sensor_inertial_2.jpg
      │  ├─ sensor_inertial_3.jpg
      │  ├─ sensor_speed_1.jpg
      │  ├─ sensor_speed_2.jpg
      │  ├─ Speedsensor.png
      │  ├─ sprayer.jpg
      │  ├─ steering_device_1.jpg
      │  ├─ steering_device_2.jpg
      │  ├─ tractor.jpg
      │  ├─ tractor3.png
      │  ├─ utud_agro_2.jpg
      │  ├─ utud_ptz_2.jpg
      │  ├─ utud_ptz_2.png
      │  ├─ utud_ptz_4.jpg
      │  ├─ Valve2.png
      │  ├─ valve_2.jpg
      │  ├─ АКПП.png
      │  ├─ БКУ бок.png
      │  ├─ БКУ фронт.png
      │  ├─ грейдер.jpg
      │  ├─ Группа 1.png
      │  ├─ Дисплей тыл.png
      │  ├─ Дисплей фронт.png
      │  ├─ Инерциальный вектор.png
      │  ├─ Инерциальный.png
      │  ├─ Энкодер.png
      │  └─ Энкодер2.png
      ├─ truck-working-field-sunny-day (3).jpg
      └─ АКПП.png

```