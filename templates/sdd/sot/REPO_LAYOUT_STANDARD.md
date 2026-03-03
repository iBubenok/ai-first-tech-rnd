# REPO_LAYOUT_STANDARD (SoT‑0)

> **Статус:** шаблон

Стандарт структуры репозитория и расположения артефактов SDD.

## Базовая структура (пример)

```text
repo/
  sot/           # SoT‑0
  policy/        # policy‑as‑code
  templates/     # шаблоны документов
  specs/         # требования (AR)
  decisions/     # решения (ADR)
  design/        # модульный дизайн (MOD)
  plans/         # декомпозиция (PLAN/TASK)
  verification/  # тест‑спеки, runbooks, security checks
  reports/       # отчёты gate’ов и релизов
  tools/         # утилиты контроля
```

## Правила

- Нормы SoT меняются редко и только через ревью.
- Для каждого изменения должна быть трассируемость: AR → ADR → MOD → тесты/отчёты.
