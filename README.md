# reglament-to

Универсальный репозиторий публичных страниц **регламента ТО** по маркам/моделям. Один каркас — много брендов.

## Ссылки

| | |
|---|---|
| **Пример (демо)** | [EXEED RX — регламент ТО](https://puholet-sketch.github.io/reglament-to/brands/exeed-rx/) |
| **Заказать такое же** | TODO: ссылка Max / контакт (`https://max.ru/…` или иной канал) |

## Структура

```text
brands/<slug>/     # сайт марки (index.html + assets + docs + .ai)
docs/              # playbook и шаблон бренда
marketing/         # материалы для Stories / рассылок
```

Сейчас: `brands/exeed-rx/` — рабочий демо-сайт.

## Для агента Cursor

1. [docs/CURSOR_PLAYBOOK.md](docs/CURSOR_PLAYBOOK.md) — пошагово: СТС → исследование → сайт → деплой  
2. [docs/BRAND_TEMPLATE.md](docs/BRAND_TEMPLATE.md) — обязательные файлы и секции каждой марки  

## Деплой

- GitHub Pages: корень репо → редирект на `brands/exeed-rx/`  
- SourceCraft: зеркало `sorvanovon/reglament-to`
