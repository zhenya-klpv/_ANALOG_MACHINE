# Material ordering policy

> Links to [`../budget/BUDGET_LAW.md`](../budget/BUDGET_LAW.md) · [`../BOOTSTRAP.md`](../BOOTSTRAP.md).

---

## Before any purchase

1. **Planned $** row in `budget/<project-id>/BUDGET.md`
2. Compare **≥2 sources** if order **>$100**
3. Include **shipping + tax** in total (not subtotal only)
4. Project cap not exceeded
5. Mirror _RU ↔ _ENG if supplier doc changes

---

## Supplier selection (priority)

| # | Rule |
|---|------|
| 1 | **Local first** for <$50 urgent items (TAP) |
| 2 | **One-stop** for first remote mold-kit (FGS / Fibre Glast) |
| 3 | **Specialist** for carbon fabric small yd (Composite Envisions) |
| 4 | **Don't split** order if ship >$60 and second order inevitable |
| 5 | **Prepreg** — only after freezer + oven decision |

---

## Budget categories

| Cat | Examples |
|-----|----------|
| MAT | resin, carbon, gelcoat, clear coat |
| TOOL | wax, PVA, sandpaper, PP sheet |
| MOLD | dedicated tooling (if tracked separately) |
| SHIP | shipping always separate line |

---

## After purchase

1. **Actual $** in `BUDGET.md`
2. Roll-up `budget/OVERVIEW.md`
3. Row in [`MATRIX.md`](MATRIX.md) § Journal
4. Receipt/PDF → `projects/<id>/reference/` if available
5. Update `SHOPPING_LIST.md` status

---

## Bootstrap constraints

- No prepreg / autoclave without cap approval
- No gallon resin if quart enough (except when only gallon — like iso FGS)
- Paid client order → materials from client prepayment (`BOOTSTRAP.md`)
- Personal trial (`_audi_s6`) → personal cap in `BUDGET.md`

---

## Supplier doc maintenance

Update `suppliers/` when:
- New real order with different vendor
- Price/ship differs significantly from table
- New local Bay Area source
- Project moves to prepreg
