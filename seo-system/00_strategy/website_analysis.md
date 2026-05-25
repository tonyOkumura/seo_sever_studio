# Sever Studio Website Analysis

Дата анализа: 2026-05-25.

Источники:

- public site: https://sever.studio/
- public site: https://sever.studio/robots.txt
- public site: https://sever.studio/sitemap_index.xml
- public site: https://sever.studio/page-sitemap.xml
- public site: https://sever.studio/post-sitemap.xml
- public site: https://sever.studio/category-sitemap.xml
- WordPress export: `sever_studio_site/severstudio.WordPress.2026-05-25.xml`
- active theme: `sever_studio_site/severstudio_active_theme/`

## 0. Extraction snapshot

### Main navigation and visible sections

- Header uses WordPress menu `header`; footer uses menus `left` and `right`. source: public site.
- Homepage section anchors include home, about, service cards, admin/support services, design services, traffic/marketing services, about text, portfolio and team. source: public site.
- Visible homepage sections include portfolio, happy clients, service cards, contact form, online brief CTA, about block, geography block and team block. source: public site.

TODO: Export actual WordPress menu item labels from admin or database if exact menu order is needed.

### Page titles and metadata

- Homepage Rank Math title: `Создание и продвижение сайтов в Красногорске | Разработка сайтов от SEVER.STUDIO`. source: public site.
- Homepage meta description references site development and promotion and uses phone `+7 925 3333 925`. source: public site.
- Rank Math is present and generates schema/sitemaps. source: public site.

TODO: Request Rank Math export to get all service page meta titles, descriptions, canonicals, robots settings and schema settings safely.

### Headings and page structure

- Service pages exist for key site-development, SEO, SMM, advertising and design services in `page-sitemap.xml`. source: public site.
- Homepage uses sections for portfolio, clients, services, about, geography and team. source: public site.
- Exact H1/H2/H3 map for every service page is TODO unless exported from crawler or confirmed in WordPress admin.

### CTAs and forms

- CTA examples: "Заказать звонок", "оставить заявку", "заполнить бриф на разработку сайта онлайн", WhatsApp, Telegram. source: public site.
- Contact Form 7 forms found in export: "Форма заявки", "Общая форма обратной связи", "Форма обратной связи ближе к подвалу", "Вакансии форма обратной связи". source: public site.
- Online brief page exists at `/brieff/`. source: public site.

### Contact and NAP data

- Header phone: `+7 (967) 066-72-49`. source: public site.
- Footer tel link target: `+79253333925`, while visible footer phone text is `+7 (967) 066-72-49`. source: public site.
- Homepage meta/schema phone references `+7 925 3333 925` / `+79253333925`. source: public site.
- Email: `info@sever.studio`. source: public site.
- Addresses visible in header: Mytishchi, Moscow and Krasnogorsk addresses listed below in Local SEO signals. source: public site.

### Portfolio, clients, team and reviews

- Portfolio block uses TLP Portfolio shortcode `[tlpportfolio id="356" title="portfolio"]`. source: public site.
- Clients block displays logo images under the heading "Счастливые клиенты". source: public site.
- Team section exists and is populated from ACF employee fields. source: public site.
- Review fields exist in ACF; public homepage also references reviews/video reviews and Yell rating blocks. source: public site.

TODO: Confirm which client logos, team names and reviews may be cited in text.

### Technologies and plugins visible

- WordPress, active custom theme based on `seo-inspace`, ACF, Contact Form 7, Rank Math, TLP Portfolio and Yandex.Metrica are visible from theme/export/public code. source: public site.
- Theme assets include Bootstrap, jQuery-like script bundle, Font Awesome/material icons and custom CSS/JS. source: public site.
- Public service stack for client projects is TODO; do not claim WordPress/Laravel/Bootstrap as Sever Studio client-delivery stack without confirmation.

### Sitemap, robots and structured data

- `robots.txt` includes `Sitemap: https://sever.studio/sitemap_index.xml`. source: public site.
- Rank Math sitemap index includes page, post, category, tag and author sitemaps. source: public site.
- Homepage schema graph includes Organization/Person, WebSite and WebPage nodes. source: public site.
- Robots disallow rules include `/portfolio/`, `/audit/`, `/website-audit/*`, `/brief/` and other paths. source: public site.

TODO: Check whether robots restrictions conflict with future audit, portfolio and brief SEO strategy.

## 1. Actual positioning from the website

Sever Studio фактически позиционируется как русскоязычная веб-студия / digital-агентство для бизнеса: создание сайтов, веб-дизайн, разработка, графический дизайн, бренд, онлайн-маркетинг, SEO и SMM. На главной странице указано: студия основана в 2015 году и специализируется на создании веб-сайтов, пользовательском веб-дизайне и разработке, графическом дизайне, разработке бренда, онлайн-маркетинге, SEO и SMM. source: public site.

Старый фокус репозитория на AI Product Design, MVP Development, SaaS UX и startup product strategy не подтверждается как основное позиционирование сайта. Эти темы нужно перевести в archive/future, кроме материалов про нейросети в SEO/дизайне, так как на сайте есть опубликованные страницы/посты о нейросетях. source: public site.

Главная локальная SEO-ось: Красногорск, Москва, Московская область, Мытищи, Королёв и соседние города. Сайт также заявляет работу по всей России и физическое присутствие во многих городах, но конкретные офисные адреса в теме подтверждены только для Мытищ, Москвы и Красногорска. source: public site.

## 2. Confirmed services

| service_category | service_name | public_url | price | timeline | deliverables | notes | confidence |
|---|---|---|---|---|---|---|---|
| Разработка сайтов | Многостраничный сайт | https://sever.studio/razrabotka-mnogostranichnogo-sajta/ | от 45 000 ₽, source: public site | 21 день разработки, source: public site | домен и хостинг, CMS, уникальный дизайн, мобильная адаптация, source: public site | В sitemap есть отдельная страница и карточка на главной | high |
| Разработка сайтов | Корпоративный сайт | https://sever.studio/razrabotka-korporativnogo-sajta/ | от 50 000 ₽, source: public site | 35 дней разработки, source: public site | домен и хостинг, CMS, структура сайта, быстрая загрузка, source: public site | На странице есть H1, преимущества, процесс, цены, CTA | high |
| Разработка сайтов | Landing Page | https://sever.studio/razrabotka-landing-page/ | от 20 000 ₽, source: public site | 12 дней разработки, source: public site | формы обратной связи, ловцы звонков, админ-панель, мобильная версия, source: public site | Ключевая коммерческая услуга | high |
| Разработка сайтов | Сайт-визитка | https://sever.studio/razrabotka-sajta-vizitki/ | от 15 000 ₽, source: public site | 10 дней разработки, source: public site | формы обратной связи, лаконичность, интерактивность, дизайн, source: public site | Хорошая услуга для малого бизнеса | high |
| Разработка сайтов | Интернет-магазин | https://sever.studio/razrabotka-internet-magazina/ | от 80 000 ₽, source: public site | 45 дней разработки, source: public site | карточка товара, корзина, покупка в один клик, фильтрация, безналичная оплата, source: public site | Нужны FAQ и коммерческие факторы | high |
| Разработка сайтов | Квиз-сайт | https://sever.studio/razrabotka-kviz-sajta/ | от 25 000 ₽, source: public site | 15 дней разработки, source: public site | usability, игровой формат, сбор базы контактов, лид-закрытие, source: public site | Подходит для лидогенерации | high |
| Поддержка и администрирование | Поддержка сайта | https://sever.studio/podderzhka-sajta/ | от 15 000 ₽, source: public site | TODO | резервное копирование, контроль 24/7, исправления, CSS, защита от атак, source: public site | Нужно уточнить период: разово или месяц | medium |
| Поддержка и администрирование | Доработка сайта | https://sever.studio/homepage/dorabotka-sajta/ | от 2 000 ₽/ч, source: public site | TODO | функционал, формы, дизайн, контент, незавершенные сайты, source: public site | URL содержит `/homepage/`; нужна проверка структуры | high |
| Поддержка и администрирование | Перенос сайта | TODO | от 40 000 ₽, source: public site | TODO | перенос БД, смена хостинга/домена/CMS, перенос контента, редиректы, сохранение SEO-позиций, source: public site | В карточке есть услуга, но публичная service page не найдена в sitemap | medium |
| Дизайн и брендинг | Бренд | TODO | от 30 000 ₽, source: public site | TODO | имя бренда, фирменный стиль, брендирование, домен, оформление сайта и соцсетей, source: public site | Нужна отдельная посадочная или привязка к фирменному стилю | medium |
| Дизайн и брендинг | Дизайн | https://sever.studio/razrabotka-logotipa/ | от 10 000 ₽, source: public site | TODO | логотип, листовки, визитки, афиши, наружная реклама, source: public site | На сайте есть отдельные страницы логотипа, визиток, типографии, вывесок | high |
| Дизайн и брендинг | Разработка фирменного стиля | https://sever.studio/razrabotka-firmennogo-stilya/ | TODO | TODO | TODO | Страница есть в sitemap; цену/срок подтвердить | medium |
| Дизайн и брендинг | Коммерческое предложение | https://sever.studio/razrabotka-kommercheskogo-predlozheni/ | TODO | TODO | этапы разработки КП, source: public site | Нужны цена/срок | medium |
| Дизайн и брендинг | Презентации | https://sever.studio/razrabotka-prezentaczij/ | TODO | TODO | создание презентаций, source: public site | Страница устаревшая по sitemap lastmod 2021 | low |
| Дизайн и брендинг | Визитки | https://sever.studio/razrabotka-vizitok/ | TODO | TODO | дизайн визиток и афиш, source: public site | Связать с типографией/брендингом | medium |
| Дизайн и брендинг | Типография | https://sever.studio/razrabotka-tipografii/ | TODO | TODO | листовки, визитки, наружная реклама, source: public site | Нужна актуализация оффера | medium |
| Дизайн и брендинг | Вывески и большие буквы | https://sever.studio/vyveski-i-bolshie-bukvy/ | TODO | TODO | вывески, объемные буквы, наружная реклама, source: public site | Обновлено в 2025 по sitemap | high |
| Тексты | Копирайт/рерайт | https://sever.studio/zakazat-kopirajt-teksta/ | от 250 ₽ / от 100 ₽, source: public site | TODO | копирайт, SEO-тексты, рерайт, уникальность, наполнение сайтов, source: public site | Единица измерения цены не указана; проверить | medium |
| Тексты | Рерайт | https://sever.studio/zakazat-rerajt-teksta-2/ | TODO | TODO | рерайт текста, source: public site | Есть отдельная страница | medium |
| Продвижение | SEO-продвижение | https://sever.studio/prodvizhenie-seo/ | от 25 000 ₽, source: public site | TODO | семантика, техническая оптимизация, контент, теги/мета-теги, анкоры и каталоги, source: public site | Ключевая услуга для нового SEO-плана | high |
| Реклама | Яндекс Директ | https://sever.studio/yandeks-direkt/ | от 20 000 ₽, source: public site | TODO | семантика, УТП, креативы, защита от скликивания, оптимизация конверсий, source: public site | Приоритетный рекламный кластер для РФ | high |
| Реклама | Google Adword / Google Ads | TODO | от 20 000 ₽, source: public site | TODO | ключевые запросы, цена клика, геотаргетинг, защита от скликивания, сквозная аналитика, source: public site | Проверить актуальность для РФ и корректное название | low |
| Реклама | Догоняющая реклама | https://sever.studio/dogonyayushhaya-reklama/ | TODO | TODO | ретаргетинг/догоняющая реклама, Яндекс.Директ, Google AdWords, source: public site | Уточнить текущие каналы | medium |
| SMM | Instagram | https://sever.studio/prodvizhenie-instagram/ | от 20 000 ₽, source: public site | TODO | ведение, постинг, оформление профиля, контент-план, привлечение ЦА, площадки, source: public site | Актуальность в РФ проверить | low |
| SMM | ВКонтакте | https://sever.studio/prodvizhenie-vkontakte/ | от 20 000 ₽, source: public site | TODO | визуальная часть, посты, редполитика, модерирование, лидер мнений, source: public site | Приоритетнее Instagram/Facebook для РФ | high |
| SMM | Таргетированная реклама | https://sever.studio/targetirovannaya-reklama/ | от 25 000 ₽, source: public site | TODO | соцдем таргетинг, интересы, геотаргетинг, тизеры/креативы, мониторинг ставок, source: public site | Коммерческий кластер | high |
| SMM | Facebook | https://sever.studio/prodvizhenie-facebook/ | TODO | TODO | продвижение Facebook, source: public site | Устаревающий/низкий приоритет; проверить актуальность для РФ | low |
| Аудит | Аудит сайта | TODO | от 15 000 ₽, source: public site | TODO | юзабилити, формы, структура, код/W3C, уникальность контента, source: public site | Нужна отдельная посадочная или URL | high |
| Аудит | Аудит рекламы | TODO | от 5 000 ₽, source: public site | TODO | аудит Яндекс Директ, Google Adwords, соцсети, стоимость рекламы, сокращение бюджетов, source: public site | Нужна страница и FAQ | medium |
| Аудит | Проверить подрядчика | TODO | от 15 000 ₽, source: public site | TODO | аудит технических изменений, SEO-работ, текстов/ссылок, бюджета, последнего захода на сайт, source: public site | Сильный problem-aware оффер | high |

## 3. Local SEO signals

- Города/география: Красногорск, Москва, Московская область, Мытищи, Королёв; дополнительно на сайте заявлены Санкт-Петербург, Ленинградская область, Ростов-на-Дону, Краснодарский край, Новороссийск, Краснодар, Сочи, Анапа. source: public site.
- Адреса в шапке: МО, Новомытищинский проспект д.30 к.1; Москва, Осташковская улица, д.14 стр.14; МО, Красногорск, Международная улица, 12. source: public site.
- Email: info@sever.studio. source: public site.
- Телефон в header/footer: +7 (967) 066-72-49. source: public site.
- Телефон в meta description / schema / CTA: +7 925 3333 925 / +79253333925. source: public site.
- WhatsApp: ссылка `https://api.whatsapp.com/send?phone=79096938363` в шапке и `https://wa.clck.bar/79253333925` в блоке отзывов. source: public site.
- Telegram: `https://telegram.me/sever_studio`. source: public site.
- Локальный intent: создание сайта в Красногорске, создание сайта в Москве, разработка сайта в Мытищах, SEO-продвижение в Красногорске, Яндекс Директ Москва/МО, поддержка сайта Москва/МО.

TODO: Уточнить главный телефон для NAP-консистентности и список реально обслуживаемых офисов.

## 4. Current site strengths

- Большой список услуг с отдельными service pages и карточками цен. source: public site.
- Видимые цены на главной для многих услуг. source: public site.
- Видимые сроки для ключевых типов сайтов. source: public site.
- Локальные адреса в шапке и локальная привязка к Красногорску/Москве/МО. source: public site.
- Контактные формы Contact Form 7, CTA "оставить заявку", "заказать звонок", "заполнить бриф". source: public site.
- Есть бриф для разработки сайта. source: public site.
- Есть Rank Math, sitemap index, page/post/category sitemaps. source: public site.
- Есть schema graph Organization/Person, WebSite, WebPage. source: public site.
- Есть Yandex.Metrica, yandex-verification, google-site-verification, Mail.ru verification. source: public site.
- Есть портфолио через TLP Portfolio shortcode и блок "Счастливые клиенты" с логотипами. source: public site.
- Есть отзывы/видеоотзывы и рейтинг Yell.ru. source: public site.
- Есть блог/новости с категориями: новости, разработка, SEO, маркетинг, копирайтинг. source: public site.

## 5. Current site weaknesses

- Непоследовательный телефон: meta/schema указывают `+7 925 3333 925`, header/footer показывают `+7 (967) 066-72-49`, WhatsApp ведет на другие номера. Это бьет по доверию и локальному SEO.
- В footer ссылка `tel:+79253333925` подписана как `+7 (967) 066-72-49`; это техническая ошибка.
- Есть устаревшие/спорные каналы: Facebook, Instagram, Google Adwords. Их нужно актуализировать для РФ или перевести в low priority.
- Некоторые тексты содержат ошибки и неестественные формулировки: "Робота со стилями CSS", "Seo продвижени", "Google adword", "робота в it". source: public site.
- В карточках цен не всегда понятно, что означает цена: разовый платеж, месяц, час, 1000 знаков. Например копирайт/рерайт `250/100` требует единиц измерения.
- У части услуг есть карточки, но нет найденной service page в sitemap: перенос сайта, аудит сайта, аудит рекламы, проверка подрядчика, бренд. Это слабые места для коммерческого спроса.
- Сервисные страницы часто тонкие: мало FAQ, сравнений, process blocks, proof blocks, кейсов, schema Service/FAQ.
- В блоге много старых материалов 2021-2023 и есть устаревшие статьи, включая пандемию 2021 и посты с потенциально внешне заимствованной структурой.
- Есть `taxopress_logs` в экспортe с дублями материалов; нужно убедиться, что эти URL не индексируются или не создают мусорные страницы.
- `robots.txt` запрещает `/audit/`, `/website-audit/*`, `/brief/`, хотя на сайте есть бриф `/brieff/`; нужно проверить, нет ли конфликта с будущими посадочными под аудит.
- `robots.txt` запрещает `/portfolio/`, но на главной портфолио заявлено как важный trust block. Нужно проверить, не закрыт ли важный коммерческий proof.
- Schema использует `@type ["Organization","Person"]` одновременно. Для агентства лучше проверить корректность Organization/LocalBusiness/ProfessionalService.
- Нет явной системной локальной landing page сети: "разработка сайта Красногорск", "создание сайта Москва", "SEO-продвижение Красногорск", "Яндекс Директ Москва".
- Внутренняя перелинковка на сервисных страницах слабая и не системная.
- Meta descriptions иногда обещают "гарантируем результат" или "выведет в ТОП"; такие формулировки нужно смягчить, если нет подтвержденных гарантий.

## 6. SEO opportunity map

| priority | opportunity | why_it_matters | affected_pages | next_action |
|---|---|---|---|---|
| high | NAP-консистентность телефона и адресов | Локальное SEO и доверие зависят от единых контактов | header, footer, schema, meta, Contact page | Уточнить главный телефон и обновить все в одном формате |
| high | Создать/усилить pillar "Разработка сайта под ключ" | Главный коммерческий спрос | homepage, service pages, blog | Brief для pillar и links на все типы сайтов |
| high | Локальная landing структура Красногорск/Москва/МО/Мытищи | Захват local commercial intent | homepage, new local pages | Создать briefs без дублирования |
| high | Усилить SEO-продвижение как коммерческий кластер | Сайт уже продает SEO и имеет блоговые материалы | /prodvizhenie-seo/, SEO posts | Добавить FAQ, process, packages, internal links |
| high | Создать посадочные под аудит сайта/рекламы/подрядчика | Эти офферы есть в карточках, но не имеют явных URL | homepage cards | Создать service page briefs |
| high | Обновить service pages с FAQ и Service schema | Улучшит конверсию и GEO/AI-search | все service pages | Создать service improvement tasks |
| high | Перелинковать blog -> service pages | Старые статьи могут поддержать коммерческие страницы | /novosti/* | Составить internal linking map |
| medium | Актуализировать Google Ads/Instagram/Facebook | Услуги видны, но могут быть неактуальны для РФ | service pages/cards | Проверить с админами и пометить low/active |
| medium | Обновить устаревший блог | Старые материалы могут снижать качество | posts 2021-2023 | Разделить на update/archive/redirect |
| medium | Исправить тексты и опечатки в карточках/мета | Влияет на доверие | homepage, service cards, meta | Список правок для WordPress |
| medium | Проверить portfolio robots block | Proof может быть закрыт от индексации | /portfolio/, TLP Portfolio | Проверить реальные portfolio URLs |
| medium | Сформировать FAQ/GEO blocks | AI-search и сниппеты | service pages + blog | Добавить FAQ template в briefs |
| low | AI/нейросети оставить future cluster | На сайте есть посты, но не главный спрос | old AI keywords/posts | Перенести в archive/future |

## 7. Content strategy implications

- Публичный язык по умолчанию: русский.
- Основной поиск: Yandex, Google Russia/CIS, локальная коммерческая выдача.
- Главные intent: service page, local commercial, comparison, problem-aware, FAQ/GEO.
- Главные деньги в системе: разработка сайтов под ключ, landing page, корпоративные сайты, интернет-магазины, SEO, поддержка/доработка, аудит, Яндекс Директ, ВКонтакте/таргет, дизайн/брендинг.
- Старые English-first prompts/skills/templates нужно заменить на Russian-first.
- Старые SaaS/MVP кластеры не удалять, но перевести в archive/low priority.
- Контент-план должен начинаться не со статей "AI product design", а с service-led pillar briefs и локальных материалов.
