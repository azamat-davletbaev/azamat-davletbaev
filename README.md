# Азамат Давлетбаев

Senior Backend Engineer, C#/.NET. 13 лет commercial experience. Уфа, работаю удалённо.

**Финтех (последние полтора года):** микросервисная платформа e-commerce —
Kafka, transactional outbox, saga-оркестрация на Temporal, прод в Kubernetes.
**До этого — 12 лет:** промышленные системы в нефтегазе и ГИС — фонд скважин,
пространственные данные, Oracle.

Специализация: event-driven архитектура, распределённые системы, интеграция
легаси с современным стеком. Переношу системы в прод, а не «закрываю тикеты»:
постановка → проектирование → реализация → приёмка → документация.

## GeoPulse — открытый проект, работает в проде

Мониторинг добычи нефти на открытых данных месторождения Volve (Equinor):
тысячи скважин, миллионы суточных измерений.

- Event-driven пайплайн: Kafka → идемпотентные обработчики → PostgreSQL + ClickHouse
- Прогноз добычи: CatBoost → ONNX, инференс в .NET без Python-рантайма
- CI/CD: GitHub Actions → VPS, health-check, автоматический откат
- Полная документация: architecture.md, runbook, журнал архитектурных решений (ADR)

**Живое демо:** https://geopulse-demo.duckdns.org
**Код:** https://github.com/azamat-davletbaev/GeoPulse

## Контакт

Telegram: [@Azamat_dav](https://t.me/Azamat_dav) · azamat.davletbaev@gmail.com
