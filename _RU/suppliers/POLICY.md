# Политика заказа материалов

> Связь с [`../budget/BUDGET_LAW.md`](../budget/BUDGET_LAW.md) · [`../BOOTSTRAP.md`](../BOOTSTRAP.md).

---

## Перед любой покупкой

1. Строка **planned $** в `budget/<project-id>/BUDGET.md`
2. Сравнить **≥2 источника** если заказ **>$100**
3. Учитывать **shipping + tax** в total (не только subtotal)
4. Cap проекта не превышен
5. Зеркало _RU ↔ _ENG если меняется supplier doc

---

## Выбор поставщика (приоритет)

| # | Правило |
|---|---------|
| 1 | **Local first** для <$50 срочных позиций (TAP) |
| 2 | **One-stop** для первого mold-kit удалённо (FGS / Fibre Glast) |
| 3 | **Specialist** для carbon fabric малые yd (Composite Envisions) |
| 4 | **Не дробить** заказ если ship >$60 и второй заказ неизбежен |
| 5 | **Prepreg** — только после freezer + oven decision |

---

## Категории бюджета

| Cat | Примеры |
|-----|---------|
| MAT | resin, carbon, gelcoat, clear coat |
| TOOL | wax, PVA, sandpaper, PP sheet |
| MOLD | dedicated tooling (если отдельно учитываем) |
| SHIP | доставка всегда отдельной строкой |

---

## После покупки

1. **Actual $** в `BUDGET.md`
2. Roll-up `budget/OVERVIEW.md`
3. Строка в [`MATRIX.md`](MATRIX.md) § Journal
4. Чек/PDF → `projects/<id>/reference/` если есть
5. Обновить `SHOPPING_LIST.md` статус

---

## Bootstrap ограничения

- Не prepreg / autoclave без cap approval
- Не gallon resin если хватит quart (кроме если только gallon — как iso FGS)
- Paid client order → материалы с предоплаты клиента (`BOOTSTRAP.md`)
- Personal trial (`_audi_s6`) → личный cap в `BUDGET.md`

---

## Supplier doc maintenance

Обновлять `suppliers/` когда:
- Новый реальный заказ с другим поставщиком
- Цена/ship сильно отличается от таблицы
- Новый локальный source Bay Area
- Переход проекта на prepreg
