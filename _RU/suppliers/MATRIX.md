# Матрица поставщиков

> Обновлять при реальных заказах (цена + shipping в [`../budget/`](../budget/)).  
> **Δ shipping** — для Bay Area часто решает итог.

---

## Легенда

| Знак | Значение |
|------|----------|
| ★★★ | Лучший выбор для категории (малые заказы) |
| ★★ | Хорошо, с оговорками |
| ★ | Возможно, но не первый выбор |
| — | Не их профиль / не для bootstrap |

| $ | Относительная цена (малый заказ) |
|---|----------------------------------|
| $ | Дешевле среднего |
| $$ | Средний рынок |
| $$$ | Дороже, но quality / range |

---

## 1. Формы (plug & female mold)

| Поставщик | Локация | Mold kit | Release | Tooling gel | Iso/epoxy resin | Cloth/mat | Доки | Ship $ | Итого |
|-----------|---------|----------|---------|-------------|-----------------|-----------|------|--------|-------|
| **[Fiberglass Supply](https://fiberglasssupply.com)** | Burlington, WA | ★★★ | ★★★ | ★★★ poly | ★★★ iso + West | ★★★ | ★★★ | $$$ (~$80) | **★★ all-in-one** |
| **[Fibre Glast](https://www.fibreglast.com)** | Brookville, OH | ★★★ | ★★★ | ★★★ poly + epoxy | ★★★ | ★★★ | ★★★ | $$ | **★★★ quality + learning** |
| **[TAP Plastics](https://www.tapplastics.com)** | **Bay Area** | ★★ | ★★ | ★★ | ★★ TAP 314 / poly | ★★ | ★ | **$0 pickup** | **★★★ local** |
| **[US Composites](https://www.uscomposites.com)** | FL | ★★ | ★★ | ★★ | ★★ | ★★ | ★ | $$ | ★★ бюджет mail-order |
| **Rock West** | CA (Springville UT ops) | ★ | ★ | ★ epoxy focus | ★★★ epoxy | ★★ | ★★ | $$ | ★★ epoxy carbon **molds** |
| West Marine | Bay Area stores | — | ★ | — | ★★★ West only | ★ | ★ | $ pickup | ★ refill 105/206 |
| Home Depot polyester | local | — | — | — | ★ cheap ortho | ★ mat | — | $0 | **✗ не для tooling** |

**Вывод mold:**
- **Первый заказ удалённо:** FGS (подтверждено `_audi_s6` #16141).
- **Дозакупка / PP / срочно:** TAP San Jose.
- **Epoxy mold под carbon production:** Fibre Glast или Rock West, не FGS polyester path.

---

## 2. Сухой carbon (wet layup · vacuum bag)

*Текущие проекты: 2x2 twill ~200 g/m² · epoxy · не prepreg.*

| Поставщик | 2x2 twill 3k | Малые qty (1–5 yd) | Quality tier | Цена | Ship | Заметка |
|-----------|--------------|-------------------|--------------|------|------|---------|
| **[Composite Envisions](https://www.compositeenvisions.com)** | ★★★ | ★★★ | comm → Toray/Hexcel | $ | $$ | **★★★ малые yd, скидки qty** |
| **Fibre Glast** | ★★★ | ★★ | pro | $$ | $$ | Надёжный каталог |
| **FGS** | ★★ | ★★ | comm | $$ | $$$ | Удобно с mold-заказом |
| **Rock West** | ★★★ | ★★ | pro | $$ | $$ | CA; tubes + plate + fabric |
| **Soller Composites** | ★★ | ★★ | comm/pro | $ | $$ | Альт CE |
| **TAP Plastics** | ★★ | ★★★ pickup | comm | $$ | $0 | Проверить наличие в store |
| Alibaba / direct CN | ★ | roll only | varies | $ | $$$$ slow | Только при volume 50+ m |

**Типичные цены (2026, ориентир):**
- Commercial 2x2 twill 3k 6oz: **~$4–8/linear yd** (CE, qty discounts).
- Toray T300 2x2: **~$10–20/yd** малые qty.
- 1k weave aesthetic: **$30–145/yd** — overkill для interior trim.

**Вывод carbon:** для `_audi_s6` и AM bootstrap → **Composite Envisions** или **TAP** (если есть нужный weave). FGS — если уже объединяешь с mold-заказом.

---

## 3. Prepreg

| Поставщик | Розница | Мин. заказ | Freezer | Цена | Для нас сейчас |
|-----------|---------|------------|---------|------|----------------|
| **[Rock West](https://www.rockwestcomposites.com/prepregs)** | ★★★ | 1 yd+ | **Да −18°C** | $$ clearance | **Позже** |
| **Fibre Glast** | ★★ | varies | Да | $$$ | Позже |
| **Toray CMA** | — trade | высокий | Да | $$$$ | AM36 / aerospace tier |
| **Composites One** | trade | bulk | Да | — | Нет аккаунта |

**Bootstrap / `_audi_s6`:** prepreg **не сейчас** — нужен freezer, oven/autoclave, короткий out-life. См. [`PREPREG.md`](PREPREG.md).

---

## 4. Расходники (все проекты)

| Категория | Лучше | Альт |
|-----------|-------|------|
| West System 105/206/406/403 | FGS · West Marine · TAP | Aircraft Spruce |
| Vacuum bag film / sealant tape | FGS · Fibre Glast · Amazon (осторожно) | US Composites |
| Peel ply | FGS · Fibre Glast | — |
| IPA / acetone | Costco · hardware | TAP |
| Sandpaper 3M | Auto paint · Amazon | TAP |
| 2K satin clear | TCP Global · local paint | — |
| PP sheet / sign board | **TAP · Home Depot** | — |
| Gloves, cups, brushes | Amazon · hardware | TAP |

---

## 5. Сценарии по типу проекта

### Trial / practice (`_audi_s6` тип)

```
Mold kit (remote)     → FGS
PP flange, мелочь     → TAP San Jose
Carbon refill         → Composite Envisions или уже есть
Clear coat            → paint supply (после test pull)
```

### AM interior trim (wet layup, satin)

```
Mold                  → FGS или Fibre Glast (по epoxy/poly решению)
Carbon 2x2 200g       → Composite Envisions
Epoxy                 → West System (West Marine / TAP)
Finish                → 2K satin automotive
```

### AM structural / aero (будущее)

```
Mold                  → Fibre Glast / Rock West (epoxy tooling)
Carbon                → Rock West / Toray tier
Prepreg               → Rock West clearance + freezer setup
```

---

## 6. Чего избегать

| | Почему |
|---|--------|
| Home Depot polyester в **carbon** layup | Несовместимость, слабый bond |
| Cheap eBay «carbon» без specs | Fake weave, weight, resin starvation |
| Prepreg без freezer | Отход; shelf life |
| Один поставщик «навсегда» | Shipping съедает выгоду на мелочи |
| Заказ без строки в `budget/` | [`BUDGET_LAW.md`](../budget/BUDGET_LAW.md) |

---

## 7. Журнал реальных заказов

| Date | Project | Supplier | Total $ | Ship $ | Вердикт |
|------|---------|----------|---------|--------|---------|
| 2026-06-10 | `_audi_s6` | FGS #16141 | 542.94 | 80.87 | ✅ OK для первого mold-kit; ship дорого |

*Добавлять строку после каждого заказа.*
