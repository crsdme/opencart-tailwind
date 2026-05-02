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

## Components Preview

```bash
http://localhost:8080/index.php?route=common/components
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
- accordion https://ui.shadcn.com/docs/components/radix/accordion
- button-group https://ui.shadcn.com/docs/components/radix/button-group
- collapsible https://ui.shadcn.com/docs/components/radix/collapsible
- checkbox https://ui.shadcn.com/docs/components/radix/checkbox
- table https://ui.shadcn.com/docs/components/radix/data-table
- hover https://ui.shadcn.com/docs/components/radix/hover-card
- tooltip https://ui.shadcn.com/docs/components/radix/tooltip
- input group https://ui.shadcn.com/docs/components/radix/input-group
- input https://ui.shadcn.com/docs/components/radix/input
- nav https://ui.shadcn.com/docs/components/radix/navigation-menu
- progress https://ui.shadcn.com/docs/components/radix/progress
- popover https://ui.shadcn.com/docs/components/radix/popover
- radio https://ui.shadcn.com/docs/components/radix/radio-group
- select https://ui.shadcn.com/docs/components/radix/select
- sonner https://ui.shadcn.com/docs/components/radix/sonner
- switch https://ui.shadcn.com/docs/components/radix/switch
- tabs https://ui.shadcn.com/docs/components/radix/tabs
- typography https://ui.shadcn.com/docs/components/radix/typography

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
