# OpenCart + Tailwind CSS + Docker Setup

E-commerce project based on OpenCart (ocStore), styled with Tailwind CSS and containerized with Docker.

## 📦 Stack

- OpenCart (ocStore)
- Tailwind CSS
- Docker + Docker Compose
- PHP 7.4 (Apache)
- MySQL 5.7
- Prettier (including Twig plugins)

## 🚀 Run (development)

```bash
docker-compose up -d --build

clear config.php file

localhost:8080/install

set tailwind theme in admin panel (extension/theme)

set Semantic URL in admin panel (settings/settings)

set Seo Pro in admin panel (settings/settings)
```

## To do list

- turn off/on pages
- minifying css/js/html
- create addons for languages like
- auto meta tags
- faq
- show more products
- auto backup
- checkout
- cart
- product page
- check microdata
- check sitemap
- favorite
- compare
- account
- variant products
- points
- md file in admin
- interface admin refactor
- check setup default theme
- lang translates for tailwind
- configure .htaccess
- windows - linux bind dev speed error

## 📝 Changelog

- new theme tailwind
- new structure `layout / head`
- added tailwind
- added prettier
- added controller handler (system/action system/loader)
- added new conroller/model for theme
- added common/microdata
- added extension/feed/sitemap
- added secured admin url
- added library custom/router
- added webp images
- added dev_dump (alt var_dump) func for debug
- added minifier
