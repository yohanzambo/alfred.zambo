# ZAMBO Alfred Yohann — Portfolio

> Personal portfolio of **ZAMBO Alfred Yohann E.**, SysOps & NoC Engineer at ANTIC (Cameroon).
> Live at: **[https://yourusername.github.io](https://yourusername.github.io)**

---

## Overview

Single-page portfolio built with pure HTML/CSS/JavaScript — no framework, no dependencies beyond Font Awesome and Google Fonts.
Features a bilingual interface (FR/EN), a SysOps/Cybersecurity dark theme with matrix rain background, and fully interactive sections.

---

## Features

- **Bilingual** — French / English toggle, preserving all CSS display types
- **Dark SysOps theme** — matrix rain canvas, cyan/green palette, terminal aesthetics
- **Animated header** — spinning profile ring, live stat counters, role badges
- **Filterable project cards** — 11 projects, collapsible details, category filters (Network, Security, Virtualisation, Automation, Monitoring)
- **Skills section** — tool tag clouds per category + animated progress bars
- **Certifications** — Credly-linked cards (CCNA, Fortinet FCA/FCP, ISO 27001, LPIC-1, AWS)
- **Scroll reveal** — IntersectionObserver-based animations on timeline items
- **Responsive** — mobile-first, adaptive grid layouts
- **SEO ready** — meta description, Open Graph tags, dual favicon (PNG + ICO)

---

## Project Structure

```
.
├── index.html              # Main HTML — all sections and JS
├── .nojekyll               # Disables Jekyll processing on GitHub Pages
├── assets/
│   └── css/
│       └── style.css       # All styles (CSS variables, components, responsive)
├── img/
│   ├── tof.jpg             # Profile photo
│   ├── favicon.ico         # Favicon (ICO)
│   └── favicon-32x32.png   # Favicon (PNG 32x32)
└── CV/
    └── CV-ZAMBO-1.pdf      # Downloadable CV
```

---

## Tech Stack

| Layer      | Technology                                |
|------------|-------------------------------------------|
| HTML       | Semantic HTML5, bilingual `.fr`/`.en` classes |
| CSS        | Custom properties, CSS Grid, Flexbox, `conic-gradient`, `IntersectionObserver` |
| JavaScript | Vanilla JS — no jQuery, no framework      |
| Fonts      | Inter (body) + JetBrains Mono (terminal) via Google Fonts |
| Icons      | Font Awesome 6.5                          |
| Hosting    | GitHub Pages                              |

---

## Sections

| Tab | Content |
|-----|---------|
| A propos | Personal info cards with status indicator |
| Expérience | Animated timeline — ANTIC (2022–present), ADC (2021) |
| Projets | 11 project cards (P01–P11) with tech tags and collapsible details |
| Compétences | 6 skill categories with tool tags and animated progress bars |
| Certifications | 7 certification cards linked to Credly |

---

## Deployment

The site is deployed via **GitHub Pages** from the `main` branch root.

```
Settings → Pages → Source: Deploy from branch → main / (root)
```

No build step required. Push to `main` and the site updates within ~60 seconds.

---

## Pending Updates

- [ ] Update Credly URLs for: **ISO 27001**, **LPIC-1**, **AWS Cloud Practitioner**, **AWS AI Practitioner**
- [ ] Add GitHub profile URL in `index.html` (social link, line ~84)

---

## Author

**ZAMBO Alfred Yohann E.**
SysOps & NoC Engineer — ANTIC, Yaoundé, Cameroon
[LinkedIn](https://linkedin.com/in/alfred-y-zambo-8359311a1) · [Email](mailto:yohanzambo.28@gmail.com) · [WhatsApp](https://wa.me/237694904503)

---

*Cellule des Systèmes d'Information — © 2026 ANTIC*
