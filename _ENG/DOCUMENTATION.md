# Documentation Standard — Analog Machine

> Every car — not a "garage project," but a **collectible object** with full dossier.  
> Our competitive advantage: trust through process.

---

## Deliverables per build

| Document | Contents |
|----------|------------|
| **Build sheet** | Spec, packages, options, timeline, hours |
| **Process photography** | Key stages, not just before/after |
| **Weight log** | Stock vs new for every replaced part |
| **Torque specs** | Critical bolts, subframe, suspension |
| **Materials log** | Composite: resin, weave, layup schedule, batch |
| **VIN dossier** | Donor history, title, smog, ownership chain |
| **Before / after** | Baseline + final, consistent angles |
| **Dyno sheet** | Baseline + final (if engine package) |
| **Alignment sheet** | Camber, caster, toe — before + after |
| **Corner balance** | Cross-weight, if chassis package |
| **Paint / body log** | Prep, primer, color code, clear, defects |
| **Certificate of build** | Numbered (for limited edition), signed |

---

## Internal (not always public)

- Cost sheet (materials + labor hours)
- Problems & resolutions log
- CAD / mold references
- Test drive notes
- Client communication archive

Store in: `builds/<build-id>/log/`

---

## Public layer (L3 Brand)

For hero car and client builds — curated version:

1. **Build book** (PDF / web) — story + highlights
2. **Gallery** — process + final
3. **Spec card** — one page: weight, power, packages, number
4. **Video** — hero film, process episodes, canyon drive

Photo/video standard: [`brand/CONTENT.md`](brand/CONTENT.md) · log: `builds/<id>/content/CONTENT_LOG.md`

Not raw dump — **museum curation** (like SAAB Viggen dossier).

---

## From day one (e36-00)

Even on demo build, maintain:

- [ ] Baseline photo set (150+)
- [ ] Weight baseline
- [ ] Hours log (by category: composites, chassis, interior, engine)
- [ ] Cost sheet (internal)
- [ ] Decision log (why X, not Y)

Hours log template: `builds/e36-00/log/HOURS.md` (create when work starts)
