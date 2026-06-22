# ChatRadar Landing

Одностраничный сайт-витрина для Telegram-бота ChatRadar.

## Запуск локально

```bash
npm install
npm run dev
```

Откройте `http://localhost:4321`.

## Сборка

```bash
npm run build
npm run preview
```

## Деплой через Docker

```bash
docker compose up -d --build
```

## Где менять контент

- `src/data/site.ts` — ссылки, навигация, базовые настройки.
- `src/data/pricing.ts` — тарифы.
- `src/data/faq.ts` — вопросы и ответы.
- `src/data/examples.ts` — примеры сообщений.
- `src/data/features.ts` — возможности.
- `src/data/useCases.ts` — сферы применения.
