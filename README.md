# Tailwind Plus Components

This repository contains a full catalog of the HTML UI components that make up Tailwind Plus, courtesy of [tailwindui-crawler](https://github.com/kiliman/tailwindui-crawler).

This repo *should* be self-updated via Github Actions. However, `tailwindui-crawler` has issues and may need to be forked to get that working.

## Overview

This repository contains **657+ production-ready HTML components** built with Tailwind CSS, organized into a comprehensive component library. All components are stored as standalone HTML files that you can copy and paste directly into your projects.

### What's Included

The component library is divided into three main categories:

#### 1. Application UI (`html/ui-blocks/application-ui/`)
Components for building web applications and admin dashboards:
- **Application Shells** - Multi-column, sidebar, and stacked layouts
- **Data Display** - Calendars, description lists, stats
- **Elements** - Avatars, badges, buttons, button groups, dropdowns
- **Feedback** - Alerts, empty states
- **Forms** - Action panels, checkboxes, comboboxes, form layouts, input groups, radio groups, select menus, sign-in forms, textareas, toggles
- **Headings** - Card headings, page headings, section headings
- **Layout** - Cards, containers, dividers, list containers, media objects
- **Lists** - Feeds, grid lists, stacked lists, tables
- **Navigation** - Breadcrumbs, command palettes, navbars, pagination, progress bars, sidebar navigation, tabs, vertical navigation
- **Overlays** - Drawers, modal dialogs, notifications
- **Page Examples** - Detail screens, home screens, settings screens

#### 2. E-commerce (`html/ui-blocks/ecommerce/`)
Complete e-commerce components and full page examples:
- **Components** - Category filters, category previews, checkout forms, incentives, order history, order summaries, product features, product lists, product overviews, product quickviews, promo sections, reviews, shopping carts, store navigation
- **Page Examples** - Category pages, checkout pages, order detail pages, order history pages, product pages, shopping cart pages, storefront pages

#### 3. Marketing (`html/ui-blocks/marketing/`)
Marketing website components and landing page sections:
- **Elements** - Banners, flyout menus, headers
- **Feedback** - 404 pages
- **Page Examples** - About pages, landing pages, pricing pages
- **Sections** - Bento grids, blog sections, contact sections, content sections, CTA sections, FAQ sections, feature sections, footers, headers, heroes, logo clouds, newsletter sections, pricing, stats sections, team sections, testimonials

### Finding Components

All components follow a consistent path structure:

```
html/ui-blocks/{category}/{subcategory}/{component-type}/{variant}.html
```

**Examples:**

- **404 Page**: `html/ui-blocks/marketing/feedback/404-pages/simple.html`
- **Login Form**: `html/ui-blocks/application-ui/forms/sign-in-forms/`
- **Product Grid**: `html/ui-blocks/ecommerce/components/product-lists/`
- **Hero Section**: `html/ui-blocks/marketing/sections/heroes/`
- **Navigation Bar**: `html/ui-blocks/application-ui/navigation/navbars/`
- **Shopping Cart**: `html/ui-blocks/ecommerce/components/shopping-carts/`

Each component type typically includes multiple variants (simple, with icons, split layout, etc.) to choose from.

