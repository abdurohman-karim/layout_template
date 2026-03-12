# Styles

## Главные правила

- Используем только `@use` и `@forward`.
- Никаких глобальных `@import`.
- SCSS делится по слоям и подключается через индексные файлы.

## Токены

Файл `styles/abstracts/_tokens.scss` содержит дизайн‑токены:

- цвета (`--color-*`)
- отступы (`--space-*`)
- радиусы (`--radius-*`)
- базовые параметры контейнера и шрифтов

Менять палитру и базовые размеры следует здесь.

## Миксины

`styles/abstracts/_mixins.scss` включает:

- `flex` — гибкая настройка flex-контейнеров
- `grid` — простая CSS-grid сетка
- `respond` — медиазапросы на основе брейкпоинтов
- `font-face` — генерация `@font-face`

Пример использования внутри модуля:

```scss
@use "../abstracts" as *;

.header {
  @include flex(row, space-between, center);
}

.title {
  @include respond(lg) {
    font-size: 2.5rem;
  }
}
```

## Шрифты

Шрифты описаны в `styles/base/_fonts.scss`. При добавлении новых файлов подключайте их через `@include font-face`.

## Порядок подключения

`styles/main.scss` подключает слои в порядке: abstracts → base → layout → components → pages → utilities.
