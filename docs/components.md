# Components

Компоненты — это независимые UI-блоки без привязки к конкретной странице.

## Правила

- Один компонент — один файл (`_button.scss`, `_card.scss`).
- Не используйте глобальные селекторы внутри компонента.
- Компоненты должны использовать токены и миксины, а не «магические» значения.

## Пример

```scss
@use "../abstracts" as *;

.card {
  padding: var(--space-lg);
  border-radius: var(--radius-lg);
  border: 1px solid var(--color-border);
}
```
