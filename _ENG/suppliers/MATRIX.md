# Supplier matrix

> Update after real orders (price + shipping in [`../budget/`](../budget/)).  
> **Δ shipping** — for Bay Area often decides the total.

---

## Legend

| Symbol | Meaning |
|--------|---------|
| ★★★ | Best pick for category (small orders) |
| ★★ | Good, with caveats |
| ★ | Possible, not first choice |
| — | Not their profile / not for bootstrap |

| $ | Relative price (small order) |
|---|------------------------------|
| $ | Below average |
| $$ | Market average |
| $$$ | Higher, but quality / range |

---

## 1. Molds (plug & female mold)

| Supplier | Location | Mold kit | Release | Tooling gel | Iso/epoxy resin | Cloth/mat | Docs | Ship $ | Overall |
|----------|----------|----------|---------|-------------|-----------------|-----------|------|--------|---------|
| **[Fiberglass Supply](https://fiberglasssupply.com)** | Burlington, WA | ★★★ | ★★★ | ★★★ poly | ★★★ iso + West | ★★★ | ★★★ | $$$ (~$80) | **★★ all-in-one** |
| **[Fibre Glast](https://www.fibreglast.com)** | Brookville, OH | ★★★ | ★★★ | ★★★ poly + epoxy | ★★★ | ★★★ | ★★★ | $$ | **★★★ quality + learning** |
| **[TAP Plastics](https://www.tapplastics.com)** | **Bay Area** | ★★ | ★★ | ★★ | ★★ TAP 314 / poly | ★★ | ★ | **$0 pickup** | **★★★ local** |
| **[US Composites](https://www.uscomposites.com)** | FL | ★★ | ★★ | ★★ | ★★ | ★★ | ★ | $$ | ★★ budget mail-order |
| **Rock West** | CA | ★ | ★ | ★ epoxy focus | ★★★ epoxy | ★★ | ★★ | $$ | ★★ epoxy carbon **molds** |
| West Marine | Bay Area | — | ★ | — | ★★★ West only | ★ | ★ | $ pickup | ★ 105/206 refill |
| Home Depot polyester | local | — | — | — | ★ cheap ortho | ★ mat | — | $0 | **✗ not for tooling** |

**Mold conclusion:**
- **First remote order:** FGS (confirmed `_audi_s6` #16141).
- **Top-up / PP / urgent:** TAP San Jose.
- **Epoxy mold for carbon production:** Fibre Glast or Rock West, not FGS polyester path.

---

## 2. Dry carbon (wet layup · vacuum bag)

*Current projects: 2x2 twill ~200 g/m² · epoxy · not prepreg.*

| Supplier | 2x2 twill 3k | Small qty (1–5 yd) | Quality tier | Price | Ship | Note |
|----------|--------------|-------------------|--------------|-------|------|------|
| **[Composite Envisions](https://www.compositeenvisions.com)** | ★★★ | ★★★ | comm → Toray/Hexcel | $ | $$ | **★★★ small yd, qty discounts** |
| **Fibre Glast** | ★★★ | ★★ | pro | $$ | $$ | Reliable catalog |
| **FGS** | ★★ | ★★ | comm | $$ | $$$ | Convenient with mold order |
| **Rock West** | ★★★ | ★★ | pro | $$ | $$ | CA; tubes + plate + fabric |
| **Soller Composites** | ★★ | ★★ | comm/pro | $ | $$ | CE alternative |
| **TAP Plastics** | ★★ | ★★★ pickup | comm | $$ | $0 | Check in-store stock |
| Alibaba / direct CN | ★ | roll only | varies | $ | $$$$ slow | Volume 50+ m only |

**Price guide (2026, approximate):**
- Commercial 2x2 twill 3k 6oz: **~$4–8/linear yd** (CE, qty discounts).
- Toray T300 2x2: **~$10–20/yd** small qty.
- 1k aesthetic weave: **$30–145/yd** — overkill for interior trim.

**Carbon conclusion:** for `_audi_s6` and AM bootstrap → **Composite Envisions** or **TAP** (if weave in stock). FGS — when bundling with mold order.

---

## 3. Prepreg

| Supplier | Retail | Min order | Freezer | Price | For us now |
|----------|--------|-----------|---------|-------|------------|
| **[Rock West](https://www.rockwestcomposites.com/prepregs)** | ★★★ | 1 yd+ | **Yes −18°C** | $$ clearance | **Later** |
| **Fibre Glast** | ★★ | varies | Yes | $$$ | Later |
| **Toray CMA** | — trade | high | Yes | $$$$ | AM36 / aerospace tier |
| **Composites One** | trade | bulk | Yes | — | No account |

**Bootstrap / `_audi_s6`:** prepreg **not now** — freezer, oven/autoclave, short out-life. See [`PREPREG.md`](PREPREG.md).

---

## 4. Consumables (all projects)

| Category | Best | Alt |
|----------|------|-----|
| West System 105/206/406/403 | FGS · West Marine · TAP | Aircraft Spruce |
| Vacuum bag film / sealant tape | FGS · Fibre Glast · Amazon (careful) | US Composites |
| Peel ply | FGS · Fibre Glast | — |
| IPA / acetone | Costco · hardware | TAP |
| Sandpaper 3M | Auto paint · Amazon | TAP |
| 2K satin clear | TCP Global · local paint | — |
| PP sheet / sign board | **TAP · Home Depot** | — |
| Gloves, cups, brushes | Amazon · hardware | TAP |

---

## 5. Scenarios by project type

### Trial / practice (`_audi_s6` type)

```
Mold kit (remote)     → FGS
PP flange, small bits → TAP San Jose
Carbon refill         → Composite Envisions or on hand
Clear coat            → paint supply (after test pull)
```

### AM interior trim (wet layup, satin)

```
Mold                  → FGS or Fibre Glast (epoxy/poly decision)
Carbon 2x2 200g       → Composite Envisions
Epoxy                 → West System (West Marine / TAP)
Finish                → 2K satin automotive
```

### AM structural / aero (future)

```
Mold                  → Fibre Glast / Rock West (epoxy tooling)
Carbon                → Rock West / Toray tier
Prepreg               → Rock West clearance + freezer setup
```

---

## 6. Avoid

| | Why |
|---|-----|
| Home Depot polyester in **carbon** layup | Incompatible, weak bond |
| Cheap eBay «carbon» no specs | Fake weave, wrong weight |
| Prepreg without freezer | Waste; shelf life |
| Single supplier forever | Shipping kills small orders |
| Order without `budget/` row | [`BUDGET_LAW.md`](../budget/BUDGET_LAW.md) |

---

## 7. Real order log

| Date | Project | Supplier | Total $ | Ship $ | Verdict |
|------|---------|----------|---------|--------|---------|
| 2026-06-10 | `_audi_s6` | FGS #16141 | 542.94 | 80.87 | ✅ OK first mold-kit; ship expensive |

*Add a row after each order.*
