# FOCUS

Личная система управления жизнью: финансы, задачи, привычки, дневник. Работает в браузере и как приложение на экране «Домой» (PWA), данные хранятся на устройстве.

- Видение, роли, дорожная карта: [docs/MASTER_PLAN.md](docs/MASTER_PLAN.md)
- Описание того, как приложение работает сейчас: [openspec/specs/](openspec/specs/)
- Задачи в работе: [openspec/changes/](openspec/changes/)
- Правила работы с git: [GIT.md](GIT.md)

## Файлы приложения
`index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`.

## Порядок работы
1. Идея обсуждается и превращается в папку `openspec/changes/<задача>/` (proposal, specs, design, tasks).
2. Собственник утверждает предложение.
3. Реализация по `tasks.md`, проверка по критериям.
4. Слияние в `main`, тег версии, перенос задачи в `openspec/changes/archive/`, обновление `openspec/specs/`.
