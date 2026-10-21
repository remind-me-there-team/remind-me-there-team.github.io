# RMW — Remind Me There

Приложение-напоминалка: напоминания по времени, по датам и по местам на карте, плюс шаблоны.

- Веб-версия (Telegram Mini App): https://remind-me-there-team.github.io
- Telegram-бот: [@rmw_my_bot](https://t.me/rmw_my_bot)
- Дальше: App Store и Google Play (Expo / EAS)

## Что лежит в этом репозитории

Собранная веб-версия (`expo export -p web`), которую публикует GitHub Pages.
Исходного кода Expo-проекта здесь пока нет.

## Подключение Mini App к боту

1. [@BotFather](https://t.me/BotFather) → `/mybots` → `@rmw_my_bot`.
2. **Bot Settings → Configure Mini App → Enable Mini App**, URL: `https://remind-me-there-team.github.io`.
3. При желании: **Bot Settings → Menu Button**, тот же URL, чтобы приложение открывалось кнопкой рядом с полем ввода.

## Безопасность

Токен бота от BotFather **никогда не коммитить** — репозиторий публичный.
Когда понадобится сервер для отправки напоминаний от бота, токен хранится только в секретах (GitHub Secrets / переменные окружения хостинга).
