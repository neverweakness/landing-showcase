# Landing Showcase

Подборка демо-лендингов с рабочими калькуляторами, формами записи и бронирования, анимациями и адаптивной вёрсткой. Каждый сайт — самостоятельная папка без зависимостей и сборки. Репозиторий пополняется новыми работами.

**Галерея с живыми демо (можно нажимать):** https://neverweakness.github.io/landing-showcase/

> Все бренды, цены, адреса и отзывы вымышлены. Это демо-проекты для портфолио, а не работы для клиентов.

## Работы

| # | Проект | Тема | Что внутри | Демо |
| --- | --- | --- | --- | --- |
| 01 | [Skyline Residence](skyline-residence) | Жилой комплекс | Сумеречный город в SVG с параллаксом, планировки квартир с фильтрами и сортировкой, «вид с этажа» (этаж и время суток меняют сцену), ипотечный калькулятор, бронирование с маской телефона | [открыть](https://neverweakness.github.io/landing-showcase/skyline-residence/) |
| 02 | [Aurora Dental](aurora-dental) | Стоматология | Пошаговая онлайн-запись (услуга, врач, время, контакты), календарь со слотами, экспорт в `.ics`, калькулятор плана лечения, слайдер «до/после», отзывы | [открыть](https://neverweakness.github.io/landing-showcase/aurora-dental/) |
| 03 | [Roastery 04](roastery-coffee) | Кофе по подписке | Конфигуратор подписки с живым пересчётом цены, иллюстрации в SVG, `@layer`, контейнерные запросы, scroll-driven анимации, оформление с проверкой | [открыть](https://neverweakness.github.io/landing-showcase/roastery-coffee/) |
| 04 | [SkillForge](skillforge-course) | Онлайн-курс | Тёмный дизайн, canvas-анимация, программа курса, таймер скидки, тарифы и демо-окно оплаты | [открыть](https://neverweakness.github.io/landing-showcase/skillforge-course/) |
| 05 | [Fluxo Watch](fluxo-watch) | Продукт (предзаказ) | 3D-рендеры часов из Blender в 4 цветах, вращение по ракурсам, светлая и тёмная темы, форма предзаказа | [открыть](https://neverweakness.github.io/landing-showcase/fluxo-watch/) |
| 06 | [EMBER](ember-restaurant) | Ресторан | Меню с фильтрами и добавками, корзина с промокодами, баллами и чаевыми, доставка/самовывоз/в зале, демо-касса с чеком и трекером статуса, бронь стола с `.ics`, клуб лояльности, повтор заказа | [открыть](https://neverweakness.github.io/landing-showcase/ember-restaurant/) |

Фото в EMBER — [Unsplash](https://unsplash.com) (бесплатная лицензия).

## Технологии

- Чистые HTML, CSS и JavaScript. Без фреймворков, без сборщиков, один `index.html` на сайт.
- Современный CSS: `@layer`, `:has()`, контейнерные запросы, `scroll-snap`, `<dialog>`, `color-mix()`, `clamp()`, анимации с учётом `prefers-reduced-motion`.
- Нативные возможности браузера: `IntersectionObserver`, `localStorage`, `Blob` и скачивание файлов (`.ics`), Canvas 2D, SVG.
- 3D-ассеты Fluxo Watch отрендерены в Blender и сжаты в WebP.
- Формы работают как заглушки с комментарием, куда подключить Telegram, CRM (amoCRM, Bitrix24) или почту; оплата подключается через ЮKassa или CloudPayments по их официальным API.

## Запуск

Сборка не нужна. Откройте `index.html` нужного сайта или поднимите простой сервер:

```bash
git clone https://github.com/neverweakness/landing-showcase.git
cd landing-showcase
python -m http.server 8000   # затем http://localhost:8000
```

## Как добавить новую работу

1. Положите папку с сайтом рядом (например, `my-site/index.html`).
2. Добавьте превью `previews/my-site.jpg` (16:10, около 960×600).
3. Допишите объект в массив `SITES` в корневом `index.html`.

## Автор

[@neverweakness](https://github.com/neverweakness). Разрабатываю лендинги, сайты, браузерные игры, Telegram-боты и парсеры. Заказать работу: [профиль на Kwork](https://kwork.ru/user/neverhoodsky). См. также [Polar Ark](https://github.com/neverweakness/polar-ark) (HTML5-игра) и [Frontend History](https://github.com/neverweakness/frontend-history) (мои первые учебные лендинги).

## Лицензия

Все права защищены. Код опубликован для ознакомления, перепубликация и перепродажа без разрешения не допускаются. См. [LICENSE](LICENSE).
