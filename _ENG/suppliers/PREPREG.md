# Suppliers — prepreg

> **Analog Machine status:** not for bootstrap · not for `_audi_s6` · consider at AM36 / structural aero stage.

---

## What prepreg is

Carbon (or glass) **pre-impregnated** with epoxy/BMI resin at factory. Stored **frozen** (−18°C / 0°F).

| vs wet layup | Prepreg |
|--------------|---------|
| Resin ratio | Factory controlled ★ | User mixed |
| Void content | Lower (with oven/autoclave) | Depends on skill |
| Shelf life | **Frozen** — months | Fabric — years dry |
| Equipment | **Freezer + oven** (+ autoclave optional) | Vacuum bag enough |
| Min buy | Higher | 1 yd fabric |
| Cost | $$$ per part | $ |

---

## When it makes sense for us

| Stage | Prepreg? |
|-------|----------|
| `_audi_s6` trial | **No** — wet layup learning |
| E36 first part (hood) | **No** — bootstrap |
| AM36 structural / aero | **Consider** |
| Production run 10+ parts | **Yes** — repeatability |

**Before prepreg need:**
- [ ] Freezer −18°C (dedicated, not kitchen)
- [ ] Oven / hot box ±5°F control
- [ ] Out-life log (hours outside freezer)
- [ ] Release film / breather / bag consumables
- [ ] Budget cap 2–4× wet layup

---

## Vendors

### Rock West Composites — ★ retail prepreg

[rockwestcomposites.com/prepregs](https://www.rockwestcomposites.com/prepregs)

| | |
|---|---|
| **Format** | 1 yd+; sometimes **expired/clearance** cheap |
| **Systems** | Newport 301/321 · 250°F cure · 2x2 twill · UD |
| **Example** | 3k 2x2 twill AS4 ~356 gsm OAW |
| **Ship** | Frozen overnight — **expensive** |
| **When** | Prototype prepreg part; clearance deal |

### Fibre Glast

| | |
|---|---|
| **Format** | Select prepregs + full wet layup range |
| **When** | One cart wet + prepreg test |

### Toray Composite Materials America

[toraycma.com](https://www.toraycma.com/products/prepreg/)

| | |
|---|---|
| **Tier** | Aerospace · T1100 · BMI · 350°F systems |
| **Min order** | Trade / volume — **not bootstrap** |
| **When** | AM36 tier if OEM/aero customer |

### Composites One · Hexcel direct

| | |
|---|---|
| **Tier** | Distributor trade accounts |
| **When** | Production shop with account |

---

## Cure systems (reference)

| Temp | Typical | Equipment |
|------|---------|-----------|
| **250°F (121°C)** | Newport 301, many retail prepregs | Shop oven, silicone heater blanket |
| **350°F (177°C)** | Aerospace epoxy | Industrial oven |
| **BMI** | 350–450°F | High-temp tooling |

---

## Economics vs wet layup

| | Wet 2x2 twill | Prepreg same part |
|---|---------------|-------------------|
| Material | ~$5–15/yd fabric + resin | ~$30–80+/yd prepreg |
| Consumables | bag, peel ply | + release film, bleeders |
| Capital | vacuum pump (have) | + **freezer $500–2000** + oven |
| Learning scrap | Cheaper | **Very expensive** |

---

## Project rule

Prepreg order → separate row in `budget/<id>/BUDGET.md` · category `MAT` · note: freezer rent / cure equipment.

**For now:** all projects — **dry carbon + epoxy**. Update this file when freezer is purchased.
