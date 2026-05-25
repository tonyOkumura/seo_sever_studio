# Existing Content Refresh Plan

## 1. Summary

Аудит построен на локальном WordPress export `sever_studio_site/severstudio.WordPress.2026-05-25.xml` и новой SEO/GEO-стратегии Sever Studio.

В `existing_content_inventory.csv` включены только основные published материалы:

- 33 pages
- 36 blog posts / новости
- 69 audited rows total

Отдельно в export найдены:

- 27 published portfolio items: не включены в CSV как основные строки; использовать как trust/proof inventory после проверки разрешений на публичное цитирование.
- 49 published `taxopress_logs`: не считать нормальными статьями; это SEO-risk / duplicate-noise candidates для технической проверки индексации, noindex или redirects.

Главная картина:

- Сильная база service pages уже есть, но большинство страниц тонкие и требуют FAQ, process, уточнения цен/сроков, перелинковки и schema.
- Старые SEO-посты можно частично обновить и привязать к услугам SEO, аудита, поддержки и разработки сайтов.
- Часть материалов 2020/2021 и общих тем не поддерживает реальные услуги и должна уйти в archive / no promotion.
- CMS, SEO-аудит, нейросети и некоторые SEO-темы пересекаются; там нужны merge decisions перед созданием новых статей.

## 2. Highest Priority Updates

1. https://sever.studio/
- Почему важен: homepage влияет на локальное доверие, сервисную навигацию и NAP.
- Keyword target: создание сайта Красногорск.
- Что исправить: конфликт телефонов, локальное позиционирование, связи с core services, schema phone.
- Внутренние ссылки: `/razrabotka-landing-page/`, `/prodvizhenie-seo/`, `/yandeks-direkt/`, `/kontakty/`.
- CTA: оставить заявку / заполнить бриф.

2. https://sever.studio/razrabotka-landing-page/
- Почему важен: confirmed high-intent service with price and timeline.
- Keyword target: landing page под ключ.
- Что исправить: добавить process, FAQ, отличие от многостраничного сайта, связь с рекламой.
- Внутренние ссылки: `/yandeks-direkt/`, `/razrabotka-kviz-sajta/`, TODO URL аудит сайта.
- CTA: оставить заявку.

3. https://sever.studio/prodvizhenie-seo/
- Почему важен: главный SEO service page.
- Keyword target: SEO продвижение сайта.
- Что исправить: опечатку в названии, Yandex/local focus, FAQ, отчетность, безопасные формулировки без гарантий ТОПа.
- Внутренние ссылки: TODO URL аудит сайта, `/zakazat-kopirajt-teksta/`, `/podderzhka-sajta/`.
- CTA: заказать аудит / оставить заявку.

4. https://sever.studio/razrabotka-korporativnogo-sajta/
- Почему важен: high-value website service.
- Keyword target: корпоративный сайт под ключ.
- Что исправить: структура, FAQ, process, сравнение с многостраничным сайтом и landing page.
- Внутренние ссылки: `/razrabotka-mnogostranichnogo-sajta/`, `/prodvizhenie-seo/`, `/podderzhka-sajta/`.
- CTA: заполнить бриф / оставить заявку.

5. https://sever.studio/razrabotka-internet-magazina/
- Почему важен: high-value e-commerce service.
- Keyword target: разработка интернет магазина.
- Что исправить: platform/integration TODO, каталог, фильтры, оплата, доставка, FAQ.
- Внутренние ссылки: `/prodvizhenie-seo/`, `/podderzhka-sajta/`, `/yandeks-direkt/`.
- CTA: оставить заявку.

6. https://sever.studio/podderzhka-sajta/
- Почему важен: recurring support offer.
- Keyword target: поддержка сайта.
- Что исправить: период цены, SLA, типовые задачи, CMS scope, FAQ.
- Внутренние ссылки: `/homepage/dorabotka-sajta/`, TODO URL перенос сайта, TODO URL аудит сайта.
- CTA: описать задачу.

7. https://sever.studio/homepage/dorabotka-sajta/
- Почему важен: problem-aware traffic after failed contractors.
- Keyword target: доработка сайта.
- Что исправить: странный URL, блок "после подрядчика", диагностика, FAQ.
- Внутренние ссылки: `/podderzhka-sajta/`, TODO URL аудит сайта, TODO URL перенос сайта.
- CTA: описать проблему / заказать аудит.

8. https://sever.studio/yandeks-direkt/
- Почему важен: confirmed paid traffic service.
- Keyword target: Яндекс Директ под ключ.
- Что исправить: бюджет vs fee, process, FAQ, landing page connection, audit link.
- Внутренние ссылки: `/razrabotka-landing-page/`, TODO URL аудит рекламы, `/prodvizhenie-seo/`.
- CTA: заказать настройку / аудит рекламы.

9. https://sever.studio/zakazat-kopirajt-teksta/
- Почему важен: supports SEO and service page refreshes.
- Keyword target: копирайт для сайта.
- Что исправить: единицу цены, scope, examples, SEO-text distinction, FAQ.
- Внутренние ссылки: `/prodvizhenie-seo/`, `/zakazat-rerajt-teksta-2/`, TODO URL аудит сайта.
- CTA: заказать текст / обсудить страницы.

10. https://sever.studio/novosti/kak-sdelat-seo-audit-sajta-poshagovaya-instrukcziya-dlya-nachinayushhih/
- Почему важен: strongest existing blog support for audit cluster.
- Keyword target: SEO аудит сайта.
- Что исправить: добавить service CTA, убрать учебную абстрактность, проверить дубли с другим SEO-аудит постом.
- Внутренние ссылки: TODO URL аудит сайта, `/prodvizhenie-seo/`, `/podderzhka-sajta/`.
- CTA: заказать аудит.

## 3. Service Page Updates

Усилить в первую очередь:

- Homepage: NAP consistency, service links, local positioning, schema phone.
- Contacts: единый телефон, адреса, карта, NAP, local trust.
- Prices: подтвердить актуальность цен, единицы измерения, связи с service pages.
- Landing Page: FAQ, process, price/timeline clarification, link to Yandex Direct and quiz.
- SEO: Yandex/local blocks, FAQ, process, reporting, no-guarantee wording.
- Corporate site: process, FAQ, comparison with multi-page and landing.
- Internet store: catalog, payment, delivery, integration TODO, FAQ.
- Support: SLA, monthly/one-time clarification, CMS scope, FAQ.
- Refinement: URL check, after-contractor angle, diagnostic process.
- Yandex Direct: budget vs fee, audit, landing page readiness.
- Copywriting/Rewriting: unit price, SEO text rules, links to SEO and audit.
- VK/Target: active platforms, examples, links to landing and branding.
- Branding pages: deliverables, source files, number of concepts, print vs design.

For every priority service page add:

- FAQ
- process
- prices/timelines clarification
- internal links
- Service schema / FAQ schema recommendation
- CTA

## 4. Blog Post Refreshes

- `kommercheskie-faktory-ranzhirovaniya-v-yandekse-chek-list`
  - Старый angle: checklist about Yandex ranking factors.
  - Новый angle: commercial factors for service pages and local SEO.
  - Target keyword: коммерческие факторы сайта.
  - Добавить: current Yandex/local checklist, examples as TODO, service page links.
  - Link: `/prodvizhenie-seo/`, TODO URL аудит сайта, `/kontakty/`.

- `iteraczionnyj-podhod-v-seo-pochemu-nelzya-navsegda-stat-liderom-topa`
  - Старый angle: why TOP is not permanent.
  - Новый angle: realistic SEO work without fake guarantees.
  - Target keyword: SEO продвижение сайта.
  - Добавить: process, reporting, no-guarantee explanation.
  - Link: `/prodvizhenie-seo/`, TODO URL аудит сайта.

- `neyavnye-seo-oshibki-99-sajtov-meshayushhie-rostu`
  - Старый angle: hidden SEO mistakes.
  - Новый angle: audit checklist for websites that do not grow.
  - Target keyword: аудит сайта.
  - Добавить: remove unsupported `99%`, add diagnostic steps.
  - Link: TODO URL аудит сайта, `/prodvizhenie-seo/`, `/podderzhka-sajta/`.

- `kak-i-zachem-seo-speczialist-pomogaet-v-razrabotke-sajtov`
  - Старый angle: SEO specialist in site development.
  - Новый angle: why SEO should be considered before website launch.
  - Target keyword: что входит в разработку сайта.
  - Добавить: structure, meta, indexation, internal linking.
  - Link: `/prodvizhenie-seo/`, `/razrabotka-korporativnogo-sajta/`, `/razrabotka-landing-page/`.

- `optimizacziya-sajta`
  - Старый angle: broad optimization.
  - Новый angle: technical and content optimization before SEO.
  - Target keyword: техническая оптимизация сайта.
  - Добавить: Yandex Webmaster, GSC, sitemap, robots, forms, speed.
  - Link: `/prodvizhenie-seo/`, TODO URL аудит сайта, `/podderzhka-sajta/`.

- `seo-vash-pomoshhnik-v-prodvizhenii-sajta-i-biznesa`
  - Старый angle: generic SEO explainer.
  - Новый angle: what SEO promotion includes for a business website.
  - Target keyword: что входит в SEO продвижение.
  - Добавить: services, expectations, links, FAQ.
  - Link: `/prodvizhenie-seo/`, TODO URL аудит сайта.

- `kak-popast-v-top-yandeksa`
  - Старый angle: get into Yandex TOP.
  - Новый angle: what affects Yandex visibility without guarantees.
  - Target keyword: продвижение сайта в Яндексе.
  - Добавить: no-guarantee wording, local/commercial factors.
  - Link: `/prodvizhenie-seo/`, TODO URL аудит сайта.

- `kak-sdelat-seo-audit-sajta-poshagovaya-instrukcziya-dlya-nachinayushhih`
  - Старый angle: beginner SEO-audit instruction.
  - Новый angle: site audit before SEO and ads.
  - Target keyword: SEO аудит сайта.
  - Добавить: CTA, deliverables, what report includes TODO.
  - Link: TODO URL аудит сайта, `/prodvizhenie-seo/`, `/podderzhka-sajta/`.

- `kak-vybrat-cms-dlya-svoego-sajta-sravnenie-gotovyh-i-samopisnyh-reshenij`
  - Старый angle: CMS comparison.
  - Новый angle: how business should choose CMS before ordering a site.
  - Target keyword: как выбрать CMS для своего сайта.
  - Добавить: maintenance, SEO, support tradeoffs.
  - Link: `/razrabotka-mnogostranichnogo-sajta/`, `/podderzhka-sajta/`.

- `dizajn-sajtov-pochemu-on-vazhen-i-kak-on-vliyaet-na-uspeh-biznesa`
  - Старый angle: why design matters.
  - Новый angle: website design as trust and conversion factor.
  - Target keyword: дизайн для бизнеса.
  - Добавить: usability, visual style, CTA, confirmed service links.
  - Link: `/razrabotka-logotipa/`, `/razrabotka-firmennogo-stilya/`, `/razrabotka-landing-page/`.

## 5. Merge / Redirect Candidates

Merge candidates:

- CMS group:
  - `/novosti/vidy-cms/`
  - `/novosti/cms-konstruktor-dlya-vashego-sajta-bez-kodirovaniya-i-slozhnostej/`
  - `/novosti/kak-vybrat-cms-dlya-svoego-sajta-sravnenie-gotovyh-i-samopisnyh-reshenij/`
  - Recommended canonical: CMS choice article.

- SEO audit group:
  - `/novosti/kak-sdelat-seo-audit-sajta-poshagovaya-instrukcziya-dlya-nachinayushhih/`
  - `/novosti/masterstvo-seo-audita-izbegaya-chastyh-oshibok/`
  - Recommended canonical: SEO audit step-by-step article or future audit service page.

- Neural network group:
  - `/novosti/iskusstvennyj-intellekt-i-nejroseti/`
  - `/novosti/primenenie-nejrosetej-kak-oni-pomogayut-reshat-raznye-zadachi/`
  - `/novosti/kak-nejroseti-pomogayut-sozdavat-dizajn-sajta/`
  - `/nejroseti-novyj-trend-dlya-seo/`
  - Recommended canonical: one future low-priority applied AI article if needed.

- Generic site value group:
  - `/novosti/kak-sajt-mozhet-sdelat-vash-biznes-uspeshnym/`
  - `/novosti/sam-sebe-razrabotchik/`
  - `/novosti/privet-mir/`
  - Recommended canonical: future practical article about choosing website format.

Redirect / technical cleanup candidates:

- `taxopress_logs` URLs: 49 duplicate/noise entries found in export. Check indexation. If indexed, map to canonical posts or noindex/redirect after technical review.
- Portfolio URLs: 27 published portfolio items are trust assets. Do not redirect blindly because `/portfolio/` is disallowed in robots; first decide whether portfolio should be indexable or only embedded on homepage.

## 6. Archive / Low Priority

Do not promote now:

- `/novosti/kak-pandemiya-izmenila-onlajn-obrazovanie-i-na-kogo-pojti-uchitsya-v-2021-godu/`
- `/novosti/50-ottenkov-krizisa-kak-vedushhie-agentstva-perezhili-2020-god-i-chto-planiruyut-delat-v-sleduyushhem/`
- `/novosti/kak-vladelczam-sajtov-zarabotat-na-partnerskih-programmah/`
- `/novosti/kuda-pojti-uchitsya-vazhnye-seo-instrumenty-i-trendy-veb-razrabotki/`
- `/novosti/5-knig-ot-eksperta-bill-gejts-microsoft-podborka-za-2020-god/`
- `/novosti/istoriya-seo/`
- `/novosti/bootstrap-kak-sozdat-krasivyj-i-udobnyj-sajt-bez-lishnih-usilij/`
- `/crypto/`
- `/prodvizhenie-facebook/` until active service is confirmed.
- `/prodvizhenie-instagram/` until active service is confirmed.
- Google Ads-related offers until active service and geography are confirmed.

## 7. New Articles Still Needed

После refresh-аудита старый контент не закрывает все priority gaps. Новые briefs все равно нужны для:

1. Разработка сайта под ключ: что входит и как выбрать формат.
2. Создание сайта в Красногорске для локального бизнеса.
3. Landing Page под ключ: когда лендинг лучше сайта.
4. Корпоративный сайт под ключ: структура и этапы.
5. Разработка интернет-магазина: что подготовить до старта.
6. Поддержка сайта: какие задачи отдавать подрядчику.
7. Доработка сайта после подрядчика.
8. Аудит сайта перед SEO и рекламой.
9. Яндекс Директ под ключ: настройка и посадочная.
10. Локальное SEO для Москвы / МО / Красногорска / Мытищ.

Не писать эти статьи до завершения refresh-аудита, подтверждения NAP и проверки service facts.
