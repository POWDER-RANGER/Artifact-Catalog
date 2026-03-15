# POWDER-RANGER — Artifact Catalog

> **157 entries · 9 domains · Oct 2024 – Mar 2026**
> A self-contained, single-file HTML work catalog with live search, domain filtering, and animated project cards.

[![Live Demo](https://img.shields.io/badge/Live-GitHub%20Pages-2ec77a?style=flat-square\&logo=github)](https://powder-ranger.github.io/Artifact-Catalog/)
[![Entries](https://img.shields.io/badge/Entries-157-8075e5?style=flat-square)]()
[![Domains](https://img.shields.io/badge/Domains-9-e05c28?style=flat-square)]()
[![Status](https://img.shields.io/badge/Status-Active-5ca8f0?style=flat-square)]()

---

## Overview

The **POWDER-RANGER Artifact Catalog** is a dark-themed, interactive dashboard cataloging every significant project artifact produced from October 2024 through March 2026. It runs entirely in a single `index.html` — no build step, no npm, no backend required.

Entries span AI agent systems, cybersecurity tooling, game automation, music production pipelines, space/physics visualizations, web UIs, hardware schematics, and systems engineering work.

---

## Features

- **Live Search** — Fuzzy-filters across titles, descriptions, and tags with an 80ms debounce
- **Domain Filters** — One-click filter by any of 9 domain categories
- **Status Badges** — Published · Active · Archived with color-coded indicators
- **Animated Cards** — Per-domain accent color bars, hover glow, and `fadeUp` entry animation
- **Sidebar Stats** — Real-time counts for total entries, months, domains, and series
- **Responsive Layout** — Adapts to mobile with collapsed sidebar and stacked nav
- **Zero Dependencies** — Self-contained except for Google Fonts CDN

---

## Domains

| Icon | Domain | Color | Description |
|------|--------|-------|-------------|
| ◈ | **Space Viz** | Teal `#1aab7d` | Orbital sims, physics visualizers, sacred geometry, cymatic renderers |
| ◈ | **AI Agent** | Purple `#8075e5` | Autonomous agents, LLM pipelines, persona frameworks, safety auditing |
| ◈ | **Gaming** | Orange `#e05c28` | Rocket League bots, OSRS animations, netcode simulators, mobile games |
| ◈ | **Security** | Pink `#db4f7a` | OSINT tools, red-team GUIs, RBAC policy engines, audit frameworks |
| ◈ | **Music** | Gold `#c07c10` | R.A.I.N. system, ComfyUI bridges, AI music production architecture |
| ◈ | **Systems** | Blue `#3585e0` | PowerShell automation, Android sovereignty, gaming optimization |
| ◈ | **Web UI** | Green `#5fa318` | Portfolios, dashboards, ecommerce, interactive tools, calculators |
| ◈ | **Hardware** | Gray `#8f8f85` | Trailer specs, servo systems, ESP32 diagrams, AR glasses concepts |
| ◈ | **Writing** | Tan `#9a7245` | Docs, specs, guides, research frameworks, strategy documents |

---

## Status Key

| Badge | Meaning |
|-------|---------|
| 🟢 **Published** | Publicly deployed and live |
| 🔵 **Active** | Currently in development |
| ⚫ **Archived** | Completed or superseded |

---

## Deploy

### GitHub Pages (Recommended)

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `Deploy from a branch` → `main` → `/ (root)`
4. Save — live at `https://<your-username>.github.io/Artifact-Catalog/`

### Local

```bash
git clone https://github.com/POWDER-RANGER/Artifact-Catalog.git
cd Artifact-Catalog
# Open index.html in any browser — no server needed
open index.html
```

### Any Static Host

Drop `index.html` onto **Netlify**, **Cloudflare Pages**, or **Vercel** — it works immediately with no configuration.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | Vanilla HTML5 |
| Styling | Pure CSS3 (CSS custom properties, grid, flexbox, keyframe animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Barlow Condensed · Barlow · JetBrains Mono via Google Fonts |
| Rendering | No framework, no bundler, no runtime dependencies |

---

## Project Stats

```
Total Entries   157
Active Series    60
Domains           9
Timespan         17 months  (Oct 2024 – Mar 2026)
File Count        1          (index.html — fully self-contained)
```

---

## Author

**Curtis Charles Farrar** — Independent Systems Engineer & AI Security Architect
Keokuk / Muscatine, Iowa · Remote

> *"Every artifact here represents a real system, a real problem, or a real experiment. Nothing is filler."*

---

## License

MIT — use freely, credit appreciated.
