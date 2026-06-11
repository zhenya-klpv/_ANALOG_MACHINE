# Поставщики — prepreg

> **Статус Analog Machine:** не для bootstrap · не для `_audi_s6` · рассматривать на этапе AM36 / structural aero.

---

## Что такое prepreg

Carbon (или glass) **предварительно пропитан** epoxy/BMI resin на заводе. Хранится **замороженным** (−18°C / 0°F).

| vs wet layup | Prepreg |
|--------------|---------|
| Resin ratio | Factory controlled ★ | User mixed |
| Void content | Ниже (с oven/autoclave) | Зависит от skill |
| Shelf life | **Frozen** — месяцы | Fabric — годы dry |
| Equipment | **Freezer + oven** (+ autoclave optional) | Vacuum bag достаточно |
| Min buy | Выше | 1 yd fabric |
| Cost | $$$ per part | $ |

---

## Когда имеет смысл для нас

| Этап | Prepreg? |
|------|----------|
| `_audi_s6` trial | **Нет** — wet layup учёба |
| E36 first part (hood) | **Нет** — bootstrap |
| AM36 structural / aero | **Рассмотреть** |
| Production run 10+ parts | **Да** — repeatability |

**Перед prepreg нужно:**
- [ ] Freezer −18°C (dedicated, не kitchen)
- [ ] Oven / hot box с контролем ±5°F
- [ ] Out-life log (часы вне морозилки)
- [ ] Release film / breather / bag consumables
- [ ] Бюджет cap выше wet layup в 2–4×

---

## Поставщики

### Rock West Composites — ★ retail prepreg

[rockwestcomposites.com/prepregs](https://www.rockwestcomposites.com/prepregs)

| | |
|---|---|
| **Формат** | 1 yd+; иногда **expired/clearance** дёшево |
| **Systems** | Newport 301/321 · 250°F cure · 2x2 twill · UD |
| **Пример** | 3k 2x2 twill AS4 ~356 gsm OAW |
| **Ship** | Frozen overnight — **дорого** |
| **Когда** | Prototype prepreg part; clearance deal |

### Fibre Glast

| | |
|---|---|
| **Формат** | Select prepregs + full wet layup range |
| **Когда** | Одна корзина wet + prepreg test |

### Toray Composite Materials America

[toraycma.com](https://www.toraycma.com/products/prepreg/)

| | |
|---|---|
| **Уровень** | Aerospace · T1100 · BMI · 350°F systems |
| **Min order** | Trade / volume — **не bootstrap** |
| **Когда** | AM36 tier если OEM/aero customer |

### Composites One · Hexcel direct

| | |
|---|---|
| **Уровень** | Distributor trade accounts |
| **Когда** | Production shop с NAICS / account |

---

## Cure systems (справка)

| Temp | Typical | Equipment |
|------|---------|-----------|
| **250°F (121°C)** | Newport 301, many retail prepregs | Shop oven, silicone heater blanket |
| **350°F (177°C)** | Aerospace epoxy | Industrial oven |
| **BMI** | 350–450°F | High-temp tooling |

---

## Экономика vs wet layup

| | Wet 2x2 twill | Prepreg same part |
|---|---------------|-------------------|
| Material | ~$5–15/yd fabric + resin | ~$30–80+/yd prepreg |
| Consumables | bag, peel ply | + release film, bleeders |
| Capital | vacuum pump (есть) | + **freezer $500–2000** + oven |
| Scrap learning | Дешевле | **Очень дорого** |

---

## Правило проекта

Prepreg-заказ → отдельная строка в `budget/<id>/BUDGET.md` · категория `MAT` · note: freezer rent / cure equipment.

**Пока:** все проекты — **dry carbon + epoxy**. Обновить этот файл при покупке freezer.
