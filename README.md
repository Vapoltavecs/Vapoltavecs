# Привет, я Слава

Пишу фронтенд на React и TypeScript. В коммерческой разработке с 2022 года.

За это время делал интерфейсы для сервисов путешествий и аналитики встреч, таблицы для работы с маркетплейсами, Telegram-приложения и игры. Кроме самого интерфейса, занимался архитектурой, сборкой и деплоем. Иногда писал бэкенд на Node.js.

### Мои самые интересные проекты

[**APPSS SDK**](https://github.com/engagementlabs/appss-sdk-js) — SDK для сбора событий из веб-приложений, Telegram Mini Apps и Node.js. Здесь я спроектировал архитектуру и написал реализацию.

Внутри три пакета: общее ядро, браузерная и серверная части. Есть очередь событий, повторная отправка при ошибках и сохранение очереди в браузере. Пакеты опубликованы в npm, примеры использования есть в репозитории.
| Package | Description | npm |
|---------|-------------|-----|
| [`@appss/sdk-core`](./packages/core) | Shared abstractions: abstract client, batching, retry, transport ports | [![npm](https://img.shields.io/npm/v/@appss/sdk-core)](https://www.npmjs.com/package/@appss/sdk-core) |
| [`@appss/sdk-browser`](./packages/browser) | Browser SDK with TMA support, localStorage persistence, sendBeacon transport | [![npm](https://img.shields.io/npm/v/@appss/sdk-browser)](https://www.npmjs.com/package/@appss/sdk-browser) |
| [`@appss/sdk-node`](./packages/node) | Node.js SDK for server-side tracking, Telegram bot helpers (Telegraf, grammY) | [![npm](https://img.shields.io/npm/v/@appss/sdk-node)](https://www.npmjs.com/package/@appss/sdk-node) |

### С чем работал

В основном **React, TypeScript и Next.js**. Ещё — Node.js, MobX, Vitest, Jest, GitHub Actions. Для игр и анимаций использовал Pixi.js, Canvas и Lottie.

Сейчас ищу работу во фронтенде, рассматриваю удалёнку. Связаться со мной можно в [Telegram — @vapoltavecs](https://t.me/vapoltavecs).
