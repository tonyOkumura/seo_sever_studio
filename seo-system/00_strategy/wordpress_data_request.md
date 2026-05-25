# WordPress Data Request

Этот файл нужен, если публичного сайта, sitemap, robots.txt, WordPress export и активной темы недостаточно для точной SEO/GEO-работы. Запрашивать нужно только рабочие данные, без паролей и персональных данных клиентов.

## Minimum safe data request

Ask admins for:

1. WordPress export:
- Tools -> Export -> All content XML file

2. Active theme copy:
- `wp-content/themes/[active-theme-name]/`

3. Custom templates, if separated:
- page templates
- service page templates
- archive templates
- single post templates
- header/footer templates

4. SEO plugin export:
- Yoast SEO export, Rank Math export, or All in One SEO export
- titles
- meta descriptions
- canonical settings
- robots settings
- schema settings

5. Sitemap files:
- `sitemap.xml`
- `page-sitemap.xml`
- `post-sitemap.xml`
- `category-sitemap.xml`
- any custom sitemap files

6. Robots and redirects:
- `robots.txt`
- `.htaccess` redirects
- Redirection plugin export, if used
- 301/302 redirect list

7. Sanitized database tables, only if admins approve:
- `wp_posts`
- `wp_postmeta`
- `wp_terms`
- `wp_term_taxonomy`
- `wp_term_relationships`
- `wp_options`, only SEO/site settings if safe
- do not request user passwords or sensitive user data

8. Media inventory:
- list of media filenames and alt text
- no need to copy all images initially unless needed

9. Analytics exports:
- Yandex Metrica pages report
- Yandex Webmaster search queries
- Google Search Console pages/queries
- GA4 landing pages, if available

10. Existing content docs:
- service descriptions
- price lists
- commercial proposals
- briefs
- brand guidelines
- approved case studies
- approved client names
- approved reviews

## Privacy Warning

Do not request passwords, admin credentials, customer personal data, private orders, payment information, or raw user tables.

## Current Status

- WordPress export is already present locally: `sever_studio_site/severstudio.WordPress.2026-05-25.xml`.
- Active theme copy is already present locally: `sever_studio_site/severstudio_active_theme/`.
- SEO plugin export is not present. TODO.
- Analytics exports are not present. TODO.
- Approved case studies, client names, reviews and service proof documents are not present as separate approved files. TODO.
