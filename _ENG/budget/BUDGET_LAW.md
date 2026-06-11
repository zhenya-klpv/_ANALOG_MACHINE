# Budget Law — Analog Machine

> **Mandatory.** Every spend = budget entry. AI and humans — no exceptions.

---

## Structure

```
budget/                    ← money only
├── BUDGET_LAW.md
├── README.md
├── OVERVIEW.md            ← master budget (all projects)
└── <project-id>/
    └── BUDGET.md          ← planned / actual / notes

projects/                  ← project work (separate!)
└── <project-id>/
    ├── PROJECT.md
    ├── APPROACH.md
    ├── PROCESS.md
    └── ...
```

Mirror: `_ENG/budget/` and `_ENG/projects/` — same layout.

**Budget and project are separate folders.** Linked by `<project-id>` (e.g. `_audi_s6`).

---

## Rules

### 1 — Two levels

| Level | File | What we track |
|-------|------|---------------|
| **Master** | `budget/OVERVIEW.md` | Sum across projects, categories, remainder |
| **Project** | `budget/<id>/BUDGET.md` | Detail for one project |

### 2 — Every spend

Add row to `budget/<id>/BUDGET.md` → **immediately** update roll-up in `budget/OVERVIEW.md`. Both languages.

### 3 — New project

1. Folder `projects/<id>/` in `_RU/` and `_ENG/` — `PROJECT.md` and working files
2. Folder `budget/<id>/` in `_RU/` and `_ENG/` — `BUDGET.md` from zero (even if $0)
3. Row in `budget/OVERVIEW.md` → Projects table
4. Row in `projects/README.md`

### 4 — Approve before buy

Materials — only after **planned** row in `BUDGET.md`. See `BOOTSTRAP.md` (cash rules).

### 5 — Do not delete

Cancel → mark `cancelled`; row stays. Audit trail matters.

### 6 — Categories (shared)

| Code | Category |
|------|----------|
| `MAT` | Materials (carbon, resin, hardener, consumables) |
| `TOOL` | Tools, consumables (sandpaper, gloves, cups) |
| `MOLD` | Tooling, plug, mold materials |
| `LABOR` | Paid time (if tracked) |
| `SHIP` | Shipping |
| `OTHER` | Other |

---

## Line format (BUDGET.md)

| Date | Item | Cat | Part / scope | Planned $ | Actual $ | Δ | Notes |
|------|------|-----|--------------|-----------|----------|---|-------|

**Δ** = Actual − Planned (fill when closing the row).

---

## Projects now

| ID | Type | Project | Budget |
|----|------|---------|--------|
| `_audi_s6` | Trial — carbon practice, Audi trim | [`../projects/_audi_s6/`](../projects/_audi_s6/) | [`_audi_s6/BUDGET.md`](_audi_s6/BUDGET.md) |
| `e36-00` | Brand — AM36 No. 001 | see `builds/e36-00/` | add `budget/e36-00/` when spend starts |

---

Russian: [`../../_RU/budget/BUDGET_LAW.md`](../../_RU/budget/BUDGET_LAW.md)
