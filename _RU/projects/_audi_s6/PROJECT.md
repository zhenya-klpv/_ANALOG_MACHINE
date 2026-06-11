# _audi_s6 — Trial Project

> **Тип:** пробный / carbon practice — **не** бренд Analog Machine.  
> **Цель:** вспомнить работу с карбоном, сделать несколько интерьерных накладок для Audi S6.

---

## Зачем

| | |
|---|---|
| **Практика** | Layup, trim, fitment, finish — без давления AM36 |
| **Продукт** | Несколько видимых деталей в своей машине |
| **Контент** | Опционально — process shots для портфолио (не обязательно публиковать как AM) |
| **Бюджет** | Отдельный учёт — [`../../budget/_audi_s6/BUDGET.md`](../../budget/_audi_s6/BUDGET.md) · общий — [`../../budget/OVERVIEW.md`](../../budget/OVERVIEW.md) |

---

## Платформа

| | |
|---|---|
| **Car** | Audi S6 **C5** (A6/S6/RS6) |
| **Project ID** | `_audi_s6` |
| **Brand** | Личный проект (не AM36) |

---

## Детали (scope)

Полный список с фото: [`PARTS.md`](PARTS.md) · референсы: [`reference/`](reference/)

| # | Группа | Описание | Статус |
|---|--------|----------|--------|
| **A** | **Vent trim surrounds** | Рамка вокруг дефлектора (не ламели) — см. [`reference/vent-trim-oem-reference.png`](reference/vent-trim-oem-reference.png) | **`reference` — старт здесь** |
| A2 | Upper vent trim | Полукруглый верхний дефлектор — рамка | `planned` |
| **B** | Door panel overlays | Накладки на панели дверей | `planned` |
| **C** | Shifter / selector surround | Область селектора КПП | `planned` |

**С OEM механики снимаем только trim frame.** Ламели, слайдер, колесо потока — оставить.

---

## Документация

| Файл | Содержание |
|------|------------|
| [`APPROACH.md`](APPROACH.md) | Решения: molded part, гибрид, satin, C5 |
| [`PROCESS.md`](PROCESS.md) | Фазы 0–5: teardown → mold → carbon |
| [`SHOPPING_LIST.md`](SHOPPING_LIST.md) | Конкретные позиции для формы |
| [`TEARDOWN.md`](TEARDOWN.md) | Лог снятия OEM + крепления |
| [`PARTS.md`](PARTS.md) | Список деталей |
| [`../../budget/_audi_s6/BUDGET.md`](../../budget/_audi_s6/BUDGET.md) | План / факт $ |

## Технический подход

**Master → female mold → carbon part** (не skinning).  
**Форма:** polyester gelcoat + iso resin (FGS #16141). **Деталь:** West 105/206 epoxy + carbon.  
Гибрид: лицо carbon, сзади OEM clips. См. [`APPROACH.md`](APPROACH.md) · [`PROCESS.md`](PROCESS.md).

---

## Статус закупок

| | |
|---|---|
| **FGS #16141** | ✅ 2026-06-10 · **$542.94** · [`reference/order-fgs-16141.pdf`](reference/order-fgs-16141.pdf) |
| **Ожидает** | #11 PP sheet · доставка FGS |

---

## Deliverables

- [x] Mold materials ordered (FGS #16141)
- [ ] Шаблоны / замеры OEM
- [ ] 3 группы деталей (двери, воздуховоды, селектор)
- [ ] Вес каждой детали (опционально)
- [ ] Фото process (для себя / портфолио)
- [x] Mold spend logged — `BUDGET.md` ($542.94)
- [ ] Бюджет финиша (#17–18) после test pull

---

## Связь с Analog Machine

Уроки переносятся в `e36-00` / AM36: материалы, mold discipline, finish standard.  
Этот проект **не** публикуется как Analog Machine build без отдельного решения.

---

## Открыто

- [x] Кузов: **C5**
- [x] Материал: 2x2 twill 200 g/m², epoxy, vacuum bag
- [x] Финиш: **satin clear**
- [ ] Фото **задней стороны** рамки → `reference/` + `TEARDOWN.md`
- [x] Донорская рамка C5 — **есть**
- [x] FGS mold materials — **$542.94** actual
- [ ] Material budget cap (total project): $ _______
