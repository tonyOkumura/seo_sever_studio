# Sever Studio SEO/GEO System

Рабочая система для SEO, GEO/AI-search, контент-плана, vc.ru-адаптаций и внутренней перелинковки сайта https://sever.studio/.

Главная коррекция: проект больше не строится вокруг English/SaaS/MVP-гипотезы. Базовая стратегия теперь русскоязычная и локальная: разработка сайтов, SEO, поддержка и доработка сайтов, реклама, SMM, дизайн, тексты, аудит, Москва / Московская область / Красногорск / Мытищи.

Главное правило: не выдумывать факты о Sever Studio. Если данных нет, писать `TODO` и запрашивать подтверждение.

## Folder Guide

- `seo-system/00_strategy/` - анализ сайта, позиционирование, аудитории, услуги, офферы, tone of voice и запрос данных у админов.
- `seo-system/01_semantics/` - русскоязычная семантика, кластеры, интенты и сущности.
- `seo-system/02_competitors/` - план SERP-исследования и список конкурентов. Анализировать, но не копировать.
- `seo-system/03_content_plan/` - roadmap, календарь публикаций, pillar pages и карта перелинковки.
- `seo-system/04_article_templates/` - шаблоны SEO-статей, FAQ, GEO-блоков, metadata и vc.ru.
- `seo-system/05_prompts/` - промпты для briefs, статей, review, metadata, FAQ, GEO и vc.ru.
- `seo-system/06_articles/` - рабочий поток статей: drafts, ready, published, vc_ru_versions.
- `seo-system/07_assets/` - скриншоты, диаграммы, иллюстрации и featured images.
- `seo-system/08_tracking/` - индексация, позиции, трафик, конверсии и winning articles.
- `seo-system/09_distribution/` - адаптации и планы репостов.
- `seo-system/10_ai_context/` - brand context, SEO rules, writing rules и forbidden patterns.

## Repo-Specific Codex Skills

Repo-specific skills live in `.agents/skills/`.

Use them by naming the skill or asking for the job:

- `article-brief-writer` - создать подробный SEO/GEO brief перед написанием статьи.
- `seo-article-writer` - написать статью только по утвержденному brief.
- `geo-optimizer` - улучшить существующий текст для AI-search/LLM answer engines.
- `internal-linking-builder` - построить логичную перелинковку между service pages, pillar pages и articles.
- `vc-ru-adapter` - сделать короткую русскоязычную vc.ru-адаптацию с ссылкой на полную статью.
- `seo-reviewer` - проверить материал перед публикацией.

Recommended workflow:

1. `article-brief-writer`
2. `seo-article-writer`
3. `geo-optimizer`
4. `internal-linking-builder`
5. `seo-reviewer`
6. `vc-ru-adapter` only after the full article is ready or published.

## Working Order

1. Проверить `seo-system/00_strategy/website_analysis.md`.
2. Уточнить у админов телефоны, адреса, активные услуги, цены, сроки и proof points.
3. Обновить `brand_context.md`, `services.md` и `offers.md`, если появились подтвержденные факты.
4. Валидировать семантику в Яндексе и Google Russia/CIS.
5. Создавать сначала briefs, а не финальные статьи.
6. Улучшать service pages параллельно с блогом.
7. Строить внутренние ссылки от блога к service pages.
8. Делать vc.ru-адаптации только после готовности полной статьи.
9. Отслеживать индексацию, позиции, трафик и заявки.

## First Week Checklist

- Подтвердить главный телефон и исправить NAP-конфликт.
- Подтвердить активные адреса и географию.
- Подтвердить цены, сроки и единицы измерения.
- Проверить актуальность Google Ads, Instagram и Facebook.
- Собрать 10-20 SERP-конкурентов в Яндексе/Google.
- Создать первые 5 article briefs.
- Составить список service page improvements.
- Не писать финальные статьи до проверки brief.

## Before Generating Each Article

Собрать:

- target keyword;
- search intent;
- audience;
- funnel stage;
- Sever Studio service page URL;
- confirmed facts with source;
- missing facts as `TODO`;
- semantic entities;
- internal link targets;
- local angle if relevant;
- CTA;
- meta title and meta description draft.

Public-facing article language: Russian by default unless English is explicitly requested.

## Article Quality Check

Перед публикацией проверить:

- search intent match;
- target keyword and semantic coverage;
- Yandex/local SEO relevance;
- clear H1/H2/H3;
- short paragraphs;
- FAQ section;
- internal links to service pages;
- CTA to Sever Studio;
- meta title and description;
- no fake facts, metrics, cases, reviews or clients;
- no keyword stuffing;
- no generic AI filler;
- no copied competitor structure.

Use `seo-system/05_prompts/08_article_quality_check.txt` before moving an article to `ready/`.
