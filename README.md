# HAVEN — Interior Architecture & Design Studio

A fully responsive, production-quality landing page for **HAVEN**, a fictional luxury interior architecture and design studio. Built as a portfolio demonstration of front-end design and UI craftsmanship.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## Overview

This project is a single-page marketing website designed to showcase a high-end interior design brand. The goal was to achieve a polished, editorial aesthetic typically seen in luxury agency websites — using no frameworks, no build tools, and no dependencies beyond Google Fonts.

## Features

- **Custom animated cursor** — a dual-ring cursor with a smooth lagging trail and hover reactions
- **Scroll-triggered reveal animations** — elements fade and slide into view using the Intersection Observer API
- **Sticky frosted-glass navigation** — the nav gains a backdrop blur and subtle shadow on scroll
- **Hero section** — staggered text animations and a slow CSS zoom effect on load
- **CSS marquee band** — infinitely scrolling service list with no JavaScript
- **Interactive service cards** — animated underline sweep and hover color transitions
- **Split about section** — overlapping image layout with a floating stat callout
- **Project gallery** — zoom-on-hover cards with slide-in detail text
- **Process timeline** — horizontal step indicators with dot hover states
- **Contact & footer** — full multi-column footer with a bold CTA strip

## Tech Stack

- **HTML5** — semantic, accessible markup
- **CSS3** — custom properties, grid, flexbox, keyframe animations, transitions
- **Vanilla JavaScript** — Intersection Observer, cursor tracking, scroll events
- **Google Fonts** — Cormorant Garamond, Tenor Sans, DM Mono

## Getting Started

No installation or build step required. Just clone the repo and open the file in your browser.

```bash
git clone https://github.com/your-username/haven-design-studio.git
cd haven-design-studio
open index.html
```

## Project Structure

```
haven-design-studio/
└── index.html      # Entire site — markup, styles, and scripts in one file
└── README.md
```

## Design Decisions

| Choice | Rationale |
|---|---|
| Single HTML file | Demonstrates that great UI doesn't require a complex stack |
| Cormorant Garamond + DM Mono | Editorial serif paired with utilitarian mono for contrast and character |
| Warm cream & rust palette | Avoids clichéd tech-blue or purple gradients; evokes luxury materials |
| CSS-only marquee | Performant, no JS overhead |
| Intersection Observer for reveals | Modern, efficient alternative to scroll event listeners |

## License

This project is open source and available under the [MIT License](LICENSE).
