# _audi_s6 — Approach (decisions)

> Parts: [`PARTS.md`](PARTS.md) · shopping: [`SHOPPING_LIST.md`](SHOPPING_LIST.md) · process: [`PROCESS.md`](PROCESS.md)

---

## Platform

| | |
|---|---|
| **Car** | Audi S6 **C5** (A6/S6/RS6 family) |
| **Interior** | Black leather + bronze/gunmetal trim (dated look) |
| **Exterior** | Black — carbon trim fits well inside |

---

## What gets carbon — priority

| # | Element | Decision | Priority |
|---|---------|----------|----------|
| 1 | **Vent frame** (`vent-main`) | **Real molded carbon part** | **Start** |
| 2 | Vertical side insert with slider/wheel | Later — narrow, relief; overlay or full part | Defer |
| 3 | Small slider inside vent | **Do not touch** — functional, high risk | No |
| 4 | Upper semi-circular vent (`vent-upper`) | After `vent-main` | 2 |
| 5 | Door inserts, ashtray, selector frame | Set after first part success | 3+ |

---

## Not skinning — real part

**Rejected:** carbon film / skinning over OEM.

**Selected:**

```
OEM frame (master) → female mold → carbon part
```

| Layer | Material |
|-------|----------|
| Face | 2x2 twill carbon 200 g/m², epoxy, vacuum bag |
| Back | **Hybrid:** carbon shell + OEM clips / 3D-print mounting features |
| Finish | **Satin clear** (2K automotive) — OEM+, not show gloss |
| Face thickness | ~1–1.5 mm; local reinforcement at mounts |

**Avoid:** forged carbon (wrong era for C5), **cheap polyester for carbon layup**, silicone mold for this job.

---

## Materials: mold vs part (FGS #16141)

| | Mold (female) | Carbon part |
|---|---------------|-------------|
| Face | Orange **polyester** Tooling Gelcoat + MEKP | 2x2 twill 200 g/m² |
| Body | Isophthalic tooling resin + 6 oz cloth + 1.5 oz mat + MEKP | West **105 + 206** epoxy |
| Master / fillets | Tooling clay, **406 + 403** (epoxy paste) | — |
| Release | Partall wax + PVA | Wax + PVA on mold face before each pull |
| Consolidation | — | Vacuum bag (on hand) |
| Finish | — | Satin 2K clear (#17 — after test pull) |

Order: **2026-06-10** · $542.94 · [`reference/order-fgs-16141.pdf`](reference/order-fgs-16141.pdf)

---

## Main difficulty

Beautiful face plate — easy. **OEM fit** — engineering:

- inner opening for vent module
- thin edges
- rear clips / mounts
- gaps to dashboard

**Rule:** photo **back side** of OEM frame first → then mold.

---

## Donor parts

Buy **1–2 spare C5 A6/S6 frames** — don't ruin your own on first mold.

After success — full set in **one weave direction:**
L / center / R vents · door inserts · ashtray · selector frame.

---

## Already on hand

- [x] Vacuum bag film
- [x] Carbon cloth
- [x] Vacuum tape / fittings / connectors / hoses
- [x] Brushes, nitrile gloves, digital scale 0.1 g
- [x] **Donor C5 vent frame** — mold master
- [x] Paper cups for mixing (#12)
- [x] **IPA 99%** — degrease
- [x] **FGS #16141** — mold materials (#1–10, except #7) · [`SHOPPING_LIST.md`](SHOPPING_LIST.md)

**Still to buy:** #11 PP sheet (mold flange).
