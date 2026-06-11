# _audi_s6 — Процесс (`vent-main`)

> Подход: [`APPROACH.md`](APPROACH.md) · закупка: [`SHOPPING_LIST.md`](SHOPPING_LIST.md)

---

## Фаза 0 — Снять и задокументировать

- [ ] Снять рамку дефлектора (или модуль — зафиксировать как)
- [ ] Фото **лицо** — есть: [`reference/vent-trim-oem-reference.png`](reference/vent-trim-oem-reference.png)
- [ ] Фото **зад** — clips, bosses, толщина, посадочные
- [ ] Фото **сбоку** — кромки, зазоры с торпедой
- [ ] Замерить зазор OEM (gap) — цель сохранить при carbon part
- [x] Донорская рамка C5 — **есть**

→ Записать в `reference/` + [`TEARDOWN.md`](TEARDOWN.md) когда снято

---

## Фаза 1 — Master

На **донорской** детали (не на единственной в машине):

1. Мойка, обезжиривание (IPA)
2. Заполнить царапины (лёгкий filler), отшлифовать P240+
3. Полировка master — от этого зависит лицо формы
4. Проверить: все кромки чистые, без сколов

---

## Фаза 2 — Форма (female mold)

**Система (FGS #16141):** **polyester** mold · **epoxy** carbon part.  
Форма: Orange Tooling Gelcoat + iso resin + mat/cloth. Деталь: West 105/206 — см. [`SHOPPING_LIST.md`](SHOPPING_LIST.md).

| Шаг | Действие | Материал |
|-----|----------|----------|
| 1 | Parting line / фланец | PP sheet (#11) + tooling clay |
| 2 | Fillets на master (до формы) | clay + epoxy paste (**406 + 403**) |
| 3 | Release на master | Partall wax 5–7 слоёв → PVA |
| 4 | Лицо формы ~20 mil wet | Orange Tooling Gelcoat + **MEKP** |
| 5 | Первый слой ламината | **6 oz cloth** (Style 7580) + iso resin + MEKP |
| 6 | Жёсткость mold body | **1.5 oz chop mat** × 5–6 слоёв + iso resin + MEKP *(вместо 10 oz #7)* |
| 7 | Отверждение, демонтаж master | — |
| 8 | Шлифовка формы P240→P800 | проверка поверхности |

*Разъёмная форма — только если undercuts не дают вынуть; решить после фото задней стороны.*

---

## Фаза 3 — Test pull

- [ ] Первый pull: **стеклоткань** или **carbon scrap** — проверка формы, не жечь хороший carbon
- [ ] Посадка в машину — зазоры, clips, скрипы
- [ ] Корректировка формы или mounting plan

---

## Фаза 4 — Carbon part (production)

| Параметр | Значение |
|----------|----------|
| Fabric | 2x2 twill, 200 g/m² |
| Resin | West 105 + **206** (epoxy) |
| Release перед layup | Wax + PVA на лице **polyester** формы |
| Consolidation | **Vacuum bag** (плёнка и фитинги — в наличии) |
| Толщина лицо | ~1–1.5 mm |
| Задняя сторона | Hybrid: вклейка **OEM clips** с донора или 3D-print mounts |
| Clear | **Satin** 2K automotive |
| Шлифовка | P800 → P1500 → P2000 → polish |

---

## Фаза 5 — Комплект (после успеха `vent-main`)

Один weave, одно направление, satin finish:

- [ ] Левый дефлектор
- [ ] Центральный (если есть)
- [ ] Правый дефлектор
- [ ] `vent-upper`
- [ ] Дверные вставки
- [ ] Пепельница / зона селектора

*Потенциальный микро-продукт для C5/S6/RS6 community.*

---

## Статус

| Фаза | Статус |
|------|--------|
| 0 Teardown | `waiting` — нужно фото задней стороны |
| 1 Master | `not started` |
| 2 Mold | `materials ordered` — FGS #16141; ждём доставку + #11 PP |
| 3 Test pull | `not started` |
| 4 Carbon part | `not started` |
