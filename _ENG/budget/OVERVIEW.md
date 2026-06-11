# Budget — Master Overview

> **Last updated:** 2026-06-10  
> Law: [`BUDGET_LAW.md`](BUDGET_LAW.md)

---

## Totals

| | Planned $ | Actual $ | Δ |
|---|-----------|----------|---|
| **All projects** | 424 | **542.94** | +118.94 |
| **Personal cap (bootstrap)** | _______ | — | — |

*Personal cap — max out-of-pocket without project revenue. See `BOOTSTRAP.md`.*

---

## By project

| Project ID | Name | Type | Planned $ | Actual $ | Δ | Status | Detail |
|------------|------|------|-----------|----------|---|--------|--------|
| `_audi_s6` | Audi S6 carbon trim trial | Trial / practice | 424 | **542.94** | +118.94 | **Active** | [`../projects/_audi_s6/`](../projects/_audi_s6/) · [`_audi_s6/BUDGET.md`](_audi_s6/BUDGET.md) |
| `e36-00` | AM36 No. 001 | Brand build | — | — | — | Not started (spend) | `builds/e36-00/` |

---

## By category (all projects)

| Cat | Planned $ | Actual $ |
|-----|-----------|----------|
| MAT | 424 | **430.83** |
| TOOL | 0 | 0 |
| MOLD | 0 | 0 |
| LABOR | 0 | 0 |
| SHIP | 0 | **80.87** |
| OTHER | 0 | **31.24** |

*Recalculate on every project `BUDGET.md` update.*

---

## Event log (major)

| Date | Event | Project | Amount $ | Notes |
|------|-------|---------|----------|-------|
| 2026-06-10 | FGS order **#16141** confirmed | `_audi_s6` | **542.94** | mold + training; UPS → San Jose |
| | Project `_audi_s6` opened | `_audi_s6` | 0 | Carbon practice trial |

---

## Update rule

1. Spend or plan → row in `budget/<id>/BUDGET.md`
2. Recalculate project totals
3. Update tables **here** (projects + categories + totals)
4. Mirror in `_RU/budget/OVERVIEW.md`
