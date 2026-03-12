# Layout Template Starter Kit

Современный стартовый шаблон для верстки на HTML + SCSS с аккуратной структурой стилей, минимальным набором инструментов и понятным DX.

## Что внутри

- HTML + SCSS (Dart Sass)
- Чистая модульная архитектура стилей
- Готовые миксины, токены, базовые утилиты
- Prettier для форматирования
- Stylelint для качества SCSS

## Быстрый старт

1. Установить зависимости:

```bash
npm install
```

2. Запустить режим разработки (watch):

```bash
npm run dev
```

3. Открыть `index.html` в браузере.

## Скрипты

- `npm run dev` — watch-компиляция SCSS в `styles/main.css`
- `npm run build` — production-компиляция (минификация)
- `npm run lint:styles` — проверка SCSS
- `npm run format` — автоформатирование файлов
- `npm run format:check` — проверка форматирования

## Структура проекта

```
assets/           # Шрифты и прочие статические файлы
js/               # JS-скрипты
styles/           # SCSS-архитектура и главный entry
index.html        # Точка входа
```

Подробно:
- `docs/architecture.md` — общая архитектура
- `docs/styles.md` — SCSS-структура и правила
- `docs/getting-started.md` — установка и запуск
- `docs/workflow.md` — рабочий процесс
- `docs/components.md` — добавление компонентов
- `docs/conventions.md` — нейминг и лучшие практики

## Принципы

- Минимум зависимости, максимум читаемости.
- Никакого legacy `@import` — только `@use`/`@forward`.
- Масштабируемость без усложнения.
