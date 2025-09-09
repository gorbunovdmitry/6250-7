# 🎨 Alfa Pay - Стикеры для iPhone

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://gorbunovdmitry.github.io/6250-1/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 📱 Описание

Интерактивный лендинг для создания и предварительного просмотра банковских стикеров для iPhone. Пользователи могут выбрать дизайн, цвет, толщину и форму стикера с живым предварительным просмотром на iPhone.

## 🌐 Демо

**Живая версия**: [https://gorbunovdmitry.github.io/6250-1/](https://gorbunovdmitry.github.io/6250-1/)

## 🚀 Запуск локально

### Способ 1: Python сервер
```bash
cd 6250-1
python3 -m http.server 8000
```

Затем откройте в браузере:
- **Главная страница** (автоперенаправление): http://localhost:8000/
- **Информационная страница**: http://localhost:8000/landing.html
- **Конфигуратор**: http://localhost:8000/designer-advanced.html

### Способ 2: Прямое открытие
Откройте `index.html` в браузере

## 📁 Структура проекта

```
6250-1/
├── landing.html              # Информационная страница
├── designer-advanced.html    # Страница выбора дизайна
├── images/                   # Папка с изображениями
│   ├── iphone.png           # iPhone для отображения
│   ├── cat.png              # Иконки для выбора
│   ├── robocat.png
│   ├── smile.png
│   ├── cookie man.png
│   ├── slider.png
│   ├── own choice (cross).png
│   ├── thin.png, bold.png   # Иконки толщины
│   ├── black.png, red.png, green.png, gradient.png, white.png
│   ├── rectangle.png, square.png, circle.png, small rectangle.png, cut.png
│   └── sticker-*.png        # 459 реальных стикеров
└── README.md                # Этот файл
```

## 🎯 Функциональность

### Страница 1 (landing.html)
- Header картинка
- Информация о стикерах
- Цены и условия
- Черная кнопка "Выбрать дизайн"

### Страница 2 (designer-advanced.html)
- iPhone с живым превью стикеров
- 4 карусели для выбора:
  - **Картинка**: кот, робокот, смайл, пряничный человек, слайдер, своя картинка
  - **Цвет**: черный, белый, красный, зеленый, градиент
  - **Толщина**: тонкий, стандартный
  - **Форма**: прямоугольник, квадрат, круг, маленький прямоугольник, с вырезом

## 🎨 Особенности

- **Mobile-first дизайн** для iOS устройств
- **Touch-friendly** интерфейс
- **Плавные анимации** и переходы
- **Автоматическое позиционирование** стикеров на iPhone
- **Увеличенные размеры** стикеров для лучшей видимости
- **Fallback система** для отображения стикеров

## 📱 Позиционирование стикеров

- **Small rectangle**: справа от камеры iPhone
- **Остальные формы**: в нижней части iPhone
- **Размеры**: rectangle, small-rectangle, cutout - по ширине iPhone с отступами 10px

## 🎉 Готово к использованию!
# GitHub Pages Deploy Fix
