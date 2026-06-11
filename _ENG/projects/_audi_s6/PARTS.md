# _audi_s6 — Parts List

> Project: [`PROJECT.md`](PROJECT.md) · Photos: [`reference/`](reference/)

---

## OEM reference

![Vent trim — OEM reference](reference/vent-trim-oem-reference.png)

**What's in the photo:** rectangular dashboard air vent on Audi S6.  
**Goal:** replace or overlay the **trim surround** in carbon. Keep OEM mechanism.

| Element in photo | Carbon? | Keep OEM? |
|------------------|---------|-----------|
| **Trim surround** — frame around grille (bronze/gunmetal) | **Yes** — primary part | — |
| Horizontal slats | No (for now) | Yes |
| L/R direction slider (chrome) | No | Yes |
| Airflow thumbwheel | No | Yes |
| Upper semi-circular vent + its frame | **Yes** — separate part | OEM mechanism |

---

## Part groups

### A — Vent trim surrounds (priority: from photo)

| ID | Part | Position | Qty | Status | Notes |
|----|------|----------|-----|--------|-------|
| `vent-main` | Rectangular vent trim frame | Dash L / R / center — TBD | ___ | `reference` | See photo; rounded rect, fit to OEM mechanism |
| `vent-upper` | Upper semi-circular vent frame | Dash — TBD | ___ | `planned` | Smaller; edge geometry near windshield |

**Approach:** real part from mold — see [`APPROACH.md`](APPROACH.md) · [`PROCESS.md`](PROCESS.md)

1. Donor OEM frame → **master**
2. Female mold (polyester gelcoat + iso resin + mat/cloth — FGS #16141)
3. Carbon 2x2 twill 200 g/m², vacuum bag
4. **Hybrid back:** carbon shell + donor OEM clips / 3D-print mounts
5. **Satin clear** — not billboard weave, not forged carbon

### B — Door panel overlays

| ID | Part | Position | Qty | Status |
|----|------|----------|-----|--------|
| `door-trim` | Door panel overlay | FL / FR / RL / RR | 4? | `planned` |

*Confirm which panels (armrest zone, pull handle surround, full card).*

### C — Shifter / selector surround

| ID | Part | Position | Qty | Status |
|----|------|----------|-----|--------|
| `shifter-trim` | Gear selector area trim | Center console | 1 | `planned` |

---

## Build order (recommended)

| # | Part | Why |
|---|------|-----|
| 1 | `vent-main` (one side) | Photo in hand; medium size; fast visible result |
| 2 | `vent-upper` | Same style family; test repeatability |
| 3 | `shifter-trim` | Single piece; center console |
| 4 | `door-trim` | Larger area; after finish workflow proven |

---

## Do not make (yet)

| Element | Why |
|---------|-----|
| Small slider inside vent | Functional — risk binding vanes |
| Carbon skinning / film | Rejected — molded part only |
| Forged carbon | Wrong era for C5 |
| Vertical slider insert | Harder — **after** `vent-main` |

## Finish

| | |
|---|---|
| **Weave** | 2x2 twill 200 g/m² |
| **Clear** | **Satin** 2K — OEM+/RS-style |
| **Thickness** | ~1–1.5 mm face; reinforcement at mounts |

---

## Open

- [ ] Exact count of `vent-main` in cabin (2? 4?)
- [ ] Can trim be removed without full module
- [ ] Back-side photos + `TEARDOWN.md`
- [ ] Photos of door panels and selector (add to `reference/`)
