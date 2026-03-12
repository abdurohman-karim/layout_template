# Conventions

## Нейминг

- SCSS partials: `_file-name.scss`.
- Классы: `block`, `block__element`, `block--modifier`.
- Утилиты: `u-` префикс при необходимости.

## Рекомендовано

- Использовать токены из `abstracts/_tokens.scss`.
- Разделять стили по слоям (base / layout / components / pages).
- Держать компоненты самодостаточными.

## Anti‑patterns

- Глобальные стили в `components/`.
- Сложные каскады и чрезмерная вложенность.
- Жестко прописанные цвета и размеры без токенов.
- Использование `@import`.
