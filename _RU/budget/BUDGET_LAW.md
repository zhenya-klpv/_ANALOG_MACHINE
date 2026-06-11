# Закон бюджета — Analog Machine

> **Обязательно.** Любая трата = запись в бюджете. AI и люди — без исключений.

---

## Структура

```
budget/                    ← только деньги
├── BUDGET_LAW.md
├── README.md
├── OVERVIEW.md            ← общий бюджет (все проекты)
└── <project-id>/
    └── BUDGET.md          ← план / факт / заметки

projects/                  ← работа над проектами (отдельно!)
└── <project-id>/
    ├── PROJECT.md
    ├── APPROACH.md
    ├── PROCESS.md
    └── ...
```

Зеркало: `_ENG/budget/` и `_ENG/projects/` — та же структура.

**Бюджет и проект — разные папки.** Связь по `<project-id>` (например `_audi_s6`).

---

## Правила

### 1 — Два уровня

| Уровень | Файл | Что считаем |
|---------|------|-------------|
| **Общий** | `budget/OVERVIEW.md` | Сумма по всем проектам, категории, остаток |
| **Проект** | `budget/<id>/BUDGET.md` | Детализация по одному проекту |

### 2 — Каждая трата

Добавил строку в `budget/<id>/BUDGET.md` → **сразу** обнови roll-up в `budget/OVERVIEW.md`. Оба языка.

### 3 — Новый проект

1. Папка `projects/<id>/` в `_RU/` и `_ENG/` — `PROJECT.md` и рабочие файлы
2. Папка `budget/<id>/` в `_RU/` и `_ENG/` — `BUDGET.md` с нуля (даже если $0)
3. Строка в `budget/OVERVIEW.md` → таблица Projects
4. Строка в `projects/README.md`

### 4 — Одобрение до покупки

Материалы — только после строки **planned** в `BUDGET.md`. См. `BOOTSTRAP.md` (cash rules).

### 5 — Не удалять

Отмена → пометка `cancelled`, строка остаётся. История важна.

### 6 — Категории (единые)

| Код | Категория |
|-----|-----------|
| `MAT` | Материалы (carbon, resin, hardener, consumables) |
| `TOOL` | Инструмент, расходники (sandpaper, gloves, cups) |
| `MOLD` | Оснастка, plug, mold materials |
| `LABOR` | Оплата времени (если считаем) |
| `SHIP` | Доставка |
| `OTHER` | Прочее |

---

## Формат строки (BUDGET.md)

| Date | Item | Cat | Part / scope | Planned $ | Actual $ | Δ | Notes |
|------|------|-----|--------------|-----------|----------|---|-------|

**Δ** = Actual − Planned (заполнять при закрытии строки).

---

## Проекты сейчас

| ID | Тип | Проект | Бюджет |
|----|-----|--------|--------|
| `_audi_s6` | Trial — carbon practice, Audi trim | [`../projects/_audi_s6/`](../projects/_audi_s6/) | [`_audi_s6/BUDGET.md`](_audi_s6/BUDGET.md) |
| `e36-00` | Brand — AM36 No. 001 | см. `builds/e36-00/` | добавить `budget/e36-00/` при старте трат |

---

English: [`../../_ENG/budget/BUDGET_LAW.md`](../../_ENG/budget/BUDGET_LAW.md)
