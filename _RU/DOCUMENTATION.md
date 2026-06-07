# Documentation Standard — Analog Machine

> Каждая машина — не «гаражный проект», а **коллекционный объект** с полным досье.  
> Это наше конкурентное преимущество: trust через процесс.

---

## Deliverables per build

| Документ | Содержание |
|----------|------------|
| **Build sheet** | Spec, packages, options, timeline, hours |
| **Process photography** | Ключевые этапы, не только before/after |
| **Weight log** | Stock vs new для каждой заменённой детали |
| **Torque specs** | Критические болты, subframe, suspension |
| **Materials log** | Композит: resin, weave, layup schedule, batch |
| **VIN dossier** | Donor history, title, smog, ownership chain |
| **Before / after** | Baseline + final, consistent angles |
| **Dyno sheet** | Baseline + final (если engine package) |
| **Alignment sheet** | Camber, caster, toe — before + after |
| **Corner balance** | Cross-weight, если chassis package |
| **Paint / body log** | Prep, primer, color code, clear, defects |
| **Certificate of build** | Numbered (для limited edition), signed |

---

## Internal (не всегда публично)

- Cost sheet (materials + labor hours)
- Problems & resolutions log
- CAD / mold references
- Test drive notes
- Client communication archive

Хранить: `builds/<build-id>/log/`

---

## Публичный слой (L3 Brand)

Для hero car и клиентских билдов — curated version:

1. **Build book** (PDF / web) — story + highlights
2. **Gallery** — process + final
3. **Spec card** — one page: weight, power, packages, number
4. **Video** — hero film, process episodes, canyon drive

Фото/видео стандарт: [`brand/CONTENT.md`](brand/CONTENT.md) · лог: `builds/<id>/content/CONTENT_LOG.md`

Не raw dump — **museum curation** (как SAAB Viggen dossier).

---

## С первого дня (e36-00)

Даже на demo build вести:

- [ ] Baseline photo set (150+)
- [ ] Weight baseline
- [ ] Hours log (по категориям: composites, chassis, interior, engine)
- [ ] Cost sheet (internal)
- [ ] Decision log (почему выбрали X, не Y)

Шаблон hours log: `builds/e36-00/log/HOURS.md` (создать при старте работ)
