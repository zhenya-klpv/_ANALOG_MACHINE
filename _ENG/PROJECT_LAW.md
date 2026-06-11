# Project Law — Bilingual Mirror

> **Mandatory for everyone.** Violation = technical debt. AI and humans follow without exception.

---

## The law

**Every new or substantially changed documentation file exists in two languages:**

| Language | Path |
|----------|------|
| **Russian** | `_RU/` — same folder structure, same filename |
| **English** | `_ENG/` — same folder structure, same filename |

### Rule 1 — RU → EN

You add or update a file **in `_RU/`** → **translate and sync** to `_ENG/`.

### Rule 2 — EN → RU

You add or update a file **in `_ENG/`** → **translate and sync** to `_RU/`.

### Rule 3 — One change, two languages

One logical change = **both files** updated in the same session. Never leave the mirror stale.

### Rule 4 — Same structure

```
_RU/brand/BRAND.md          ↔  _ENG/brand/BRAND.md
_RU/builds/e36-00/BUILD_BRIEF.md  ↔  _ENG/builds/e36-00/BUILD_BRIEF.md
_RU/budget/OVERVIEW.md           ↔  _ENG/budget/OVERVIEW.md
_RU/budget/_audi_s6/BUDGET.md     ↔  _ENG/budget/_audi_s6/BUDGET.md
_RU/projects/_audi_s6/PROJECT.md  ↔  _ENG/projects/_audi_s6/PROJECT.md
```

### Rule 5 — Budget

Every spend or planned purchase → `budget/<id>/BUDGET.md` **and** `budget/OVERVIEW.md` in **both** languages. Project work lives in `projects/<id>/`. See [`budget/BUDGET_LAW.md`](budget/BUDGET_LAW.md) · `.cursor/rules/budget-tracking.mdc`.

**Project root** holds only `README.md`, `.gitignore`, `.cursor/`. **Do not** put doc `.md` files at root.

---

## What to sync

| Yes | No |
|-----|-----|
| `.md` in `_RU/` ↔ `_ENG/` | `.gitignore`, `.cursor/` (root only) |
| Checklists, briefs | `private/` — by agreement |

**Images:** copy to `_RU/...` and `_ENG/...`. Translate `INDEX.md`.

---

## Process

1. Edit a file → identify language (`_RU` or `_ENG`)
2. Sync the mirror
3. Links: inside `_RU/` — `_RU` paths; inside `_ENG/` — `_ENG` paths
4. Structure changed → `AI_CONTEXT.md` in **both** languages

---

## Done checklist

- [ ] `_RU/...` exists?
- [ ] `_ENG/...` exists?
- [ ] Content equivalent?

**Otherwise the task is not complete.**

---

Russian: [`../_RU/PROJECT_LAW.md`](../_RU/PROJECT_LAW.md)
