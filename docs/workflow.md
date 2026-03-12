# Workflow

## Добавление нового компонента

1. Создайте файл в `styles/components/`, например `_card.scss`.
2. Подключите его в `styles/components/_index.scss` через `@forward "card";`.
3. Используйте токены и миксины из `abstracts`.

## Добавление новой страницы

1. Создайте файл `styles/pages/_about.scss`.
2. Подключите его в `styles/pages/_index.scss` через `@forward "about";`.
3. Старайтесь держать стили страницы локальными и не плодить глобальные селекторы.

## Проверка качества

- Перед коммитом запускайте `npm run lint:styles`.
- Форматируйте код `npm run format`.

## Обновление токенов

Все базовые цвета, отступы и системные параметры лежат в `styles/abstracts/_tokens.scss`.
