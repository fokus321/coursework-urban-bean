# Макет Figma — Urban Bean

Документ для переноса интерфейса в Figma.

## Фреймы

1. Desktop — 1440 px
2. Tablet — 768 px
3. Mobile — 390 px

## Цвета

- Background: `#fff8ee`
- Surface: `#f4e4cf`
- Cream card: `#fffdf8`
- Text: `#27170f`
- Muted text: `#6d5647`
- Accent: `#9b5c2e`
- Accent dark: `#56321f`
- Border: `rgba(39, 23, 15, 0.16)`

## Типографика

- Logo / headings: Georgia, serif
- Body / UI: Arial, Helvetica, sans-serif
- H1 Desktop: 88 px, line-height 1.05
- H1 Tablet: 58–64 px
- H1 Mobile: 44 px
- Body: 16–21 px, line-height 1.6
- Eyebrow: 13 px, uppercase, letter spacing 0.16em

## Компоненты

### Header
- Sticky header
- Logo слева
- Навигация справа: О нас, Меню, Предзаказ, Контакты
- На планшете/мобиле навигация переносится на вторую строку

### Buttons
- Primary: фон `#56321f`, текст `#fffdf8`, border-radius 999 px
- Secondary: прозрачный фон, border 1 px, текст `#56321f`
- Hover: подъём на 3 px и мягкая тень

### Cards
- Background: `#fffdf8`
- Radius: 28 px
- Border: 1 px `rgba(39, 23, 15, 0.16)`
- Hover: translateY(-6px)

## Страницы

### index.html
1. Header
2. Hero: текст + CTA + большая кофейная иллюстрация
3. Ticker преимуществ
4. О проекте: 2 колонки
5. Блок карточек: меню / предзаказ / мультимедиа
6. Видео-секция
7. Форма предзаказа
8. Footer

### menu.html
1. Header
2. Hero страницы меню
3. Сетка карточек блюд и напитков
4. CTA на форму
5. Footer

### success.html
- Центрированная карточка подтверждения

## Responsive

- Desktop: max-width 1180 px, двухколоночные секции, карточки 3 в ряд
- Tablet до 900 px: секции в 1 колонку, карточки 2 в ряд
- Mobile до 520 px: карточки 1 в ряд, кнопки на всю ширину
