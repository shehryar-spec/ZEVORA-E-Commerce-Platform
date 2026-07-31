<div align="center">

# ✨ ZEVORA — The Curated Marketplace

[![Live Demo](https://img.shields.io/badge/🔗-LIVE%20DEMO-00ffd5?style=for-the-badge)](https://shehryar-spec.github.io/ZEVORA-E-Commerce-Platform/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-7b6bff?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shehryar-spec/ZEVORA-E-Commerce-Platform)
[![Made with Love](https://img.shields.io/badge/Built%20with-HTML5%20%7C%20CSS3%20%7C%20JavaScript-ff4a8d?style=for-the-badge)]
[![License: MIT](https://img.shields.io/badge/License-MIT-ffd864?style=for-the-badge)](LICENSE)

**A fully-responsive single-page e-commerce platform built from scratch with pure HTML, CSS & JavaScript — zero dependencies, zero frameworks.**

[View Demo](https://shehryar-spec.github.io/ZEVORA-E-Commerce-Platform/) · [Report Bug](../../issues) · [Request Feature](../../issues)

<br>

![ZEVORA Hero](screenshots/hero.png)

<br>

</div>

---

## 📋 Table of Contents

- [About The Project](#-about-the-project)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Tech Stack](#️-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Demo Credentials](#-demo-credentials)
- [Design System](#-design-system)
- [Key Implementations](#-key-implementations)
- [Roadmap](#-roadmap)
- [Author](#-author)
- [License](#-license)

---

## 🚀 About The Project

ZEVORA is a production-quality multi-department marketplace simulation that showcases what's possible with **vanilla web technologies**. No React, no npm, no build tools — just one `index.html` file that works the second you open it.

Built as a demonstration that modern web experiences (routing, state management, animations, i18n, admin panels) don't require heavy frameworks.

> ⚡ **One file. Zero dependencies. Opens everywhere.**

---

## ✨ Features

### 🛍️ Shopping Experience
| Feature | Status |
| :--- | :---: |
| **Product Catalog** — 28 real products with Unsplash imagery across 5 departments | ✅ |
| **Product Categories** — Fashion, Electronics, Home, Beauty, Sport | ✅ |
| **Advanced Filtering** — Department, price range, size, color | ✅ |
| **Sorting Options** — Featured, Price (asc/desc), Rating, Newest | ✅ |
| **Product Detail Pages** — Gallery, size/color picker, quantity selector | ✅ |
| **Shopping Cart** — Full add/remove/quantity, localStorage persistence | ✅ |
| **Wishlist** — Save favorites for later | ✅ |
| **Live Search** — Instant search across all products | ✅ |

### 💳 Checkout & Accounts
| Feature | Status |
| :--- | :---: |
| **Multi-step Checkout** — Contact, shipping, payment | ✅ |
| **Payment Methods** — Credit Card, Cash on Delivery, JazzCash/EasyPaisa | ✅ |
| **Order Confirmation** — Success screen with order number | ✅ |
| **User Auth** — Login / Signup (demo) | ✅ |
| **Admin Dashboard** — Stats, product management, orders view | ✅ |
| **Add Products** — Admin can add new products (persisted) | ✅ |

### 🌍 Localization & Preferences
| Feature | Status |
| :--- | :---: |
| **Multi-Currency** — USD ⇄ PKR real-time switching (Rs 280 rate) | ✅ |
| **Bilingual** — English ⇄ Urdu with full RTL layout support | ✅ |
| **Dark / Light Mode** — Theme toggle with system preference detection | ✅ |
| **Persistent State** — Cart, wishlist, theme, currency, language saved | ✅ |

### 🎨 UI/UX
| Feature | Status |
| :--- | :---: |
| **3D Animated Splash Screen** — Orbital logo, particles, loading bar | ✅ |
| **Smooth Scroll Reveal** — Fade-in animations for all sections | ✅ |
| **Parallax Scrolling** — Depth effects on hero, promo, slider | ✅ |
| **Hover Effects** — Image zoom, glow, 3D card tilt, button fills | ✅ |
| **Auto Hero Slider** — With dots, arrows, captions | ✅ |
| **Toast Notifications** — Action feedback system | ✅ |
| **Countdown Timer** — For seasonal sale banner | ✅ |
| **Marquee Ticker** — Scrolling announcement bar | ✅ |
| **Custom Cursor** — With hover state (desktop) | ✅ |
| **Full Responsive** — Mobile, tablet, desktop optimized | ✅ |

---

## 📸 Screenshots

<details>
<summary><b>Click to expand all screenshots</b></summary>

<br>

### 🏠 Home / Hero Section
The main landing page with animated hero, floating orbit decorations, and stat counters.

![Hero](screenshots/hero.png)

### 🛒 Product Catalog
Filterable product grid with hover zoom effects, quick-add buttons, and wishlist hearts.

![Products](screenshots/products.png)

### 📂 Departments
Five curated departments with real photography and hover effects.

![Departments](screenshots/departments.png)

### 📦 Product Detail
Individual product pages with gallery, size/color selection, and add-to-cart.

![Product Detail](screenshots/product-detail.png)

### 🛍️ Shopping Cart
Slide-out cart drawer with quantity controls and checkout button.

![Cart](screenshots/cart.png)

### 💳 Checkout
Multi-step checkout with shipping form and payment options.

![Checkout](screenshots/checkout.png)

### 👤 User Authentication
Login / signup tabs with demo admin access.

![Auth](screenshots/auth.png)

### 🧑‍💼 Admin Dashboard
Stats panel, product management, and order overview for admins.

![Admin](screenshots/admin.png)

### 🌙 Light Mode
Full Light theme toggle with smooth transition.

![Dark Mode](screenshots/lightmode.png)

### 📱 Mobile View
Fully responsive layout for phones and tablets.

![Mobile](screenshots/mobile.png)

### 🇵🇰 Urdu / RTL
Complete Urdu translation with right-to-left layout.

![Urdu RTL](screenshots/urdu.png)

### 📝 Blog Section
Blog cards with individual article pages.

![Blog](screenshots/blog.png)

</details>

> **Note:** Screenshots are in the `screenshots/` folder. Replace placeholder images with actual screenshots of the running site.

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
| :--- | :--- | :--- |
| **Markup** | HTML5 | Semantic SPA structure via hash routing |
| **Styling** | CSS3 | Custom properties, Grid, Flexbox, animations, media queries |
| **Logic** | Vanilla JavaScript (ES6+) | State management, rendering, routing, observers |
| **Fonts** | Google Fonts | Fraunces (display), Manrope (body), IBM Plex Mono (monospace), Noto Nastaliq (Urdu) |
| **Icons** | FontAwesome 6 | UI and social icons |
| **Images** | Unsplash | Real product photography via CDN |
| **Storage** | localStorage | Persistent cart/wishlist/theme/currency state |

> **Zero npm packages, zero dependencies, zero build process.** Open the file and it works.

---

## 🏃 Getting Started

### Option 1: Just Open It
```bash
# Download the file
# Double click index.html
# ...that's it.
```

### Option 2: Local Server
```bash
# Clone the repository
git clone https://github.com/shehryar-spec/ZEVORA-E-Commerce-Platform.git

# Navigate to project
cd ZEVORA-E-Commerce-Platform

# Open in browser (any of these work)
start index.html         # Windows
open index.html          # macOS
xdg-open index.html      # Linux

# OR use VS Code Live Server for auto-reload
# OR use Python:
python -m http.server 5500
```

### Option 3: Deploy in 1 Click
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/drop) — just drag & drop the file.

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/new) — import from GitHub.

---

## 📁 Project Structure

```
ZEVORA-E-Commerce-Platform/
│
├── index.html               # 🎯 The entire application (HTML + CSS + JS)
├── README.md                # You are here
├── LICENSE                  # MIT license
│
└── screenshots/             # For this README
    ├── hero.png
    ├── products.png
    ├── departments.png
    ├── product-detail.png
    ├── cart.png
    ├── checkout.png
    ├── auth.png
    ├── admin.png
    ├── lightmode.png
    ├── mobile.png
    ├── urdu.png
    └── blog.png
```

<details>
<summary><b>Wait... really? One file?</b></summary>

<br>

Yes. Here's the breakdown of `index.html`:

```
┌───────────────────────────────────────────────┐
│  <!DOCTYPE html>                              │
│  <html>                                       │
│    <head>                                     │
│      <meta>, <title>, fonts                   │
│      <style>      /* ~800 lines of CSS */     │
│    </head>                                    │
│    <body>                                     │
│      Splash screen, Header, Search overlay    │
│      Home, Shop, PDP, Checkout pages          │
│      Auth, Admin, Blog, Article, About        │
│      Footer, Cart drawer, Toast, Back-to-top  │
│      <script>    /* ~500 lines of JS */      │
│    </body>                                    │
│  </html>                                      │
└───────────────────────────────────────────────┘
```

The SPA routing is handled via `hashchange` events. State (cart, wishlist, theme, language, currency, custom products) lives in `localStorage`. All rendering is done with vanilla JS template literals and DOM manipulation.

</details>

---

## 🔑 Demo Credentials

| Role | Email | Password | Access |
| :--- | :--- | :--- | :--- |
| 👤 Regular User | Any email + 4+ char password | — | Browse, cart, checkout |
| 🧑‍💼 **Admin** | `admin@zevora.com` | `admin123` | Admin dashboard, product management |

---

## 🎨 Design System

### Color Palette (Blue / White / Sandy)

| Token | Hex | Usage |
| :--- | :--- | :--- |
| `--bg` | `#F4EFE6` | Sandy cream background |
| `--surface` | `#FFFFFE` | Card and surface backgrounds |
| `--ink` | `#0A1F3D` | Primary text (deep navy) |
| `--accent` | `#1565C0` | Primary action blue |
| `--accent-light` | `#42A5F5` | Hover/highlight blue |
| `--gold` | `#D4A843` | Accent and badges |
| `--rose` | `#C62828` | Sale tags and errors |

### Typography
- **Display:** Fraunces (editorial serif for headings)
- **Body:** Manrope (geometric sans for body copy)
- **Mono:** IBM Plex Mono (labels, prices, tags)
- **Urdu:** Noto Nastaliq Urdu (RTL body text)

---

## 💡 Key Implementations

### Client-Side Routing
Hash-based SPA navigation (`#/`, `#/shop`, `#/product/:id`, `#/checkout`, `#/auth`, `#/admin`, `#/blog`, `#/blog/:id`, `#/about`) with page transitions.

### State Management
Simple but effective state container with localStorage persistence — cart, wishlist, user session, theme, language, currency, and admin-added products all survive page refreshes.

### Intersection Observer
Used for scroll-triggered reveal animations and skill bar fills, with `threshold` and `rootMargin` tuning for natural timing.

### Parallax Engine
`requestAnimationFrame`-throttled parallax that calculates element positions relative to viewport center and applies transforms at varying speeds — works on hero decorations, slider images, and promo media.

### Internationalization
Full EN/UR dictionary-based i18n system. Urdu mode switches `dir="rtl"`, applies Nastaliq font, and flips all flex/grid layouts automatically.

### Currency Layer
Centralized `fmt(price)` function converts all displayed prices on the fly when the currency toggle is clicked — no hard-coded price strings.

### Product Data
Products are defined as plain JS objects with image keys mapped to Unsplash CDN URLs (with Picsum fallback if any image fails). New products added via the admin panel are persisted to localStorage.

---

## 🗺️ Roadmap

- [ ] Product image gallery with multiple angles
- [ ] Order history for logged-in users
- [ ] Wishlist page (currently badge-only)
- [ ] Compare products feature
- [ ] Image zoom on product detail
- [ ] Shipping calculator by location
- [ ] Product reviews and ratings submission
- [ ] Dark mode for Urdu RTL
- [ ] Pagination / infinite scroll for catalog
- [ ] Related products carousel
- [ ] JSON file for product data (separation of concerns)

---

## 👨‍💻 Author

**Shehryar Asif** — Computer Science Undergraduate @ University of Wah, Pakistan

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-00ffd5?style=for-the-badge&logo=firefoxbrowser&logoColor=black)](https://shehryar-spec.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shehryar-asif-87107139a)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shehryar-spec)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shehryar.homeo@gmail.com)

</div>

---

## 📄 License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for more information.

```
MIT License

Copyright (c) 2026 Shehryar Asif

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

---

<div align="center">

<br>

**Built with HTML, CSS, JavaScript & an unusual amount of curiosity.** ⚡

<br>

If you found this project interesting, please consider giving it a ⭐ on GitHub!

</div>
