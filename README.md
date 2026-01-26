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

set tailwind extension/theme
```

## To do list
- turn off/on pages
- minifying
- webp images
- languages
- checkout
- cart
- product page
- check microdata
- check sitemap
- favorite
- compare
- account

- check setup default theme
- translates for tailwind

## 📝 Changelog

- new theme tailwind
- new structure `layout / head`
- added tailwind
- added prettier
- added controller handler (system/action system/loader)
- added new conroller/model for theme
- added common/microdata
- added extension/feed/sitemap