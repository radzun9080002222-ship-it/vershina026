# Вершина — доступный клининг в Кирове

Самостоятельный городской лендинг на React, Vite, TypeScript и Tailwind CSS.

## Публикация

- Домен: https://vershina43.ru/
- Репозиторий: https://github.com/radzun9080002222-ship-it/vershina43
- Публикация: Yandex Cloud Object Storage, workflow deploy-yandex-cloud.yml из ветки `main`.
- CNAME, canonical, Open Graph, robots.txt и sitemap настроены на `vershina43.ru`.
- Текущее состояние DNS/SSL/аналитики — в начале MEMORY.md. Пока финальная проверка не завершена, рекламную готовность не считать подтверждённой.

## Запуск

```bash
pnpm install
pnpm run dev
pnpm run build
```

## Структура

- `src/data.ts` — контакты, тарифы, чек-листы, кейсы и FAQ.
- `src/components/` — секции страницы.
- `public/images/` — оптимизированные production-изображения.
- `source-assets/images/GPT/voronezh/` — исходные PNG генераций.
- `MEMORY.md` — принятые решения и правила продолжения работы.

Телефон, MAX, Telegram и WhatsApp общие с брендом «Вершина». Для Воронежа используются отдельные рекламный кабинет, счётчик Метрики и сайт в Яндекс Вебмастере; чужие счётчики и verification-файлы в этот проект не переносятся.
