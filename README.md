# Excalibur-2-Cloud

Чистый агентный пайплайн блога для **Cursor Cloud**: Scout → Research →
Title → Writer → Sol → Cover/Schema → Indexer → Publish.

В репозитории **нет** чужого слога, лица, CTA и статей. При первом запуске
агент **Setup** спрашивает вас и заполняет настройки.

## Быстрый старт

1. Склонируйте **private** репозиторий в Cursor / подключите Cloud Environment.
2. Прочитайте [`CLOUD-FIRST-RUN.md`](CLOUD-FIRST-RUN.md) — Secrets, MCP,
   **Memories OFF**.
3. Запустите First-run automation / чат с промптом Setup.
4. Ответьте на вопросы (стиль, примеры, обложки, ссылки, сайт, автор).
5. Когда `memory/setup/status.json` → `complete: true`, включайте Daily
   automation из [`CLOUD-AUTOMATION.md`](CLOUD-AUTOMATION.md).

Карта анкеты: [`SETUP.md`](SETUP.md). Канон агентов: [`AGENTS.md`](AGENTS.md).

## Что внутри

| Путь | Роль |
|------|------|
| `agents/` + `.cursor/agents/` | Director, Setup, Sol, Cover, Publish… |
| `skills/` | Runbook'и субагентов |
| `shared/` | Контракты, SOUL (после setup), tenant-config |
| `memory/setup/` | Статус онбординга, inbox примеров |
| `scripts/` | Гейты, publish, cover split (инфраструктура) |

## Чего здесь нет

- Личных промптов и корпуса слога другого автора
- Референс-фото чужого ведущего
- Готовых статей и published ledger с чужими URL
- GUI-приложения — только агенты и Markdown

## Лицензия / доступ

Репозиторий **закрытый**. Владелец открывает доступ сам.

<!-- SAIFER_REPO_PASSPORT_BEGIN: #435 -->
## Паспорт

- **Что это:** Чистый агентный пайплайн блога для **Cursor Cloud**: Scout → Research →.
- **Статус:** не знаю (работает / пауза / заморожено ❄️ / брошено — нет runtime-проверки).
- **Где работает:** не знаю (сервер/ПК/сайт/облако не подтверждены).
- **Как запустить или открыть:** [репозиторий](https://github.com/SaiferSMART/my-Excalibur-2-Cloud); запуск приложения — не знаю (ищите инструкции в README).
- **Связанные открытые PR:** [актуальный список](https://github.com/SaiferSMART/my-Excalibur-2-Cloud/pulls?q=is%3Apr+is%3Aopen).
- **Связанные открытые Issue:** [актуальный список](https://github.com/SaiferSMART/my-Excalibur-2-Cloud/issues?q=is%3Aissue+is%3Aopen).
- **Дата последнего изменения GitHub:** 2026-11-16T11:44:53Z (поле `pushed_at`, любая ветка; не равно проверке эксплуатации).
- **Кто ведёт:** не знаю; владелец репозитория GitHub — `SaiferSMART`.
- **Вопрос к владелице:** подтвердить статус, площадку, точку входа и фактического ведущего.
- **Задание:** [Issue №435](https://github.com/SaiferSMART/saifer-ai-ops/issues/435).
<!-- SAIFER_REPO_PASSPORT_END -->
