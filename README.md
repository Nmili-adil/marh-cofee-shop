# Marh Coffee Roasters ☕

> Specialty Ethiopian Arabica coffee café — Hivernage, Marrakech, Morocco

**TripAdvisor Travellers' Choice 2024 · Rated 4.7★ · #15 of 84 Cafés in Marrakech**

---

## About

Marh Coffee Roasters is a specialty coffee destination located in the upscale Hivernage district of Marrakech. The café sources 100% Ethiopian Arabica beans, roasted in-house to deliver clean, complex, and beautifully balanced cups. In addition to its coffee programme, Marh is known for its signature kunafa crêpes — a unique fusion of Moroccan and Levantine pastry traditions — along with a full menu of food and beverages.

**Open every day · 07:00 – 23:00**

---

## Project Overview

This repository contains the official single-page website for Marh Coffee Roasters. The site is built with pure HTML, CSS, and JavaScript — no build toolchain or framework required. Simply open `index.html` in a browser.

---

## Features

- **Animated preloader** with a gold progress bar
- **Custom cursor** that reacts on hover
- **Hero section** with a Three.js particle canvas animation and live open/closed status badge
- **Stats bar** — TripAdvisor rating, verified reviews, Glovo score, and city ranking
- **Our Story** section with an interactive canvas background
- **Full menu** with tabbed categories:
  - Classic Coffees (Espresso, Americano, Latte, Cappuccino, Flat White…)
  - Signature Lattes (Ube, Lavender, Matcha, Caramel, Chai…)
  - Frappés (Caramel, Mocha, Vanilla, Matcha, Ube…)
  - Kunafa Crêpes (Pistache Nutella, Pistache…)
  - Classic Crêpes (Sweet & Savoury)
  - Combos & Pastries / Take-home beans & merchandise
- **Visit section** with opening hours table (highlights today's row) and an embedded Leaflet.js map
- **Guest reviews** carousel with TripAdvisor Travellers' Choice badge
- **Online ordering** — links to Glovo and Yumlo delivery platforms
- **Multilingual support** (EN / FR / AR) via a built-in i18n system
- **Fully responsive** — mobile drawer navigation, fluid typography, touch-friendly layout
- **Floating action buttons** — WhatsApp contact & scroll-to-top

---

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 / CSS3 / Vanilla JS | Core structure, styling, and interactivity |
| [Three.js r128](https://threejs.org/) | Hero & About canvas particle animations |
| [Leaflet.js 1.9.4](https://leafletjs.com/) | Interactive location map |
| [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) | Display / heading typeface |
| [Outfit](https://fonts.google.com/specimen/Outfit) | Body typeface |

All external libraries are loaded via CDN — no `npm install` or build step needed.

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/Nmili-adil/marh-cofee-shop.git
cd marh-cofee-shop

# Open the site in your browser
open index.html
# or on Linux:
xdg-open index.html
```

No server, no dependencies, no configuration. The site works directly from the filesystem.

> **Note:** The interactive map and Google Fonts require an internet connection to load correctly.

---

## Project Structure

```
marh-cofee-shop/
├── index.html          # Complete single-page website (HTML + CSS + JS)
├── marh-coffee-sow.docx  # Statement of Work document
└── README.md
```

---

## Sections

| Section | Anchor |
|---|---|
| Hero | `#hero` |
| Statistics | `#stats` |
| Our Story | `#about` |
| Menu | `#menu` |
| Hours & Location | `#visit` |
| Guest Reviews | `#reviews` |
| Order Online | `#order` |

---

## Contact & Links

| Channel | Link |
|---|---|
| 📧 Email | [marhcoffeeroasters@gmail.com](mailto:marhcoffeeroasters@gmail.com) |
| 📸 Instagram | [@marhcoffeeroasters](https://www.instagram.com/marhcoffeeroasters/) |
| 📍 Google Maps | [Find us in Marrakech](https://maps.google.com/?q=Marh+Coffee+Roasters+Marrakech) |
| 🛵 Glovo | [Order on Glovo](https://glovoapp.com/fr/ma/marrakech/stores/marh-coffe-roasters-mar) |
| 🏠 Yumlo | [Order on Yumlo](https://yumlo.ma/en/marrakech/marh-coffe-roasters-mar) |
| ⭐ TripAdvisor | [Read Reviews](https://www.tripadvisor.fr/Restaurant_Review-g293734-d33271236-Reviews-Marh_Coffee_Roasters-Marrakech_Marrakech_Safi.html) |

---

## License

© 2025 Marh Coffee Roasters · Marrakech, Morocco · All rights reserved.
