# Dominion Majemu-Itura Aseyege — Portfolio Website

> A bold, editorial-style personal portfolio for **Xcel** — Web3 partnerships lead, ministry founder, and music label operator based in Lagos, Nigeria.

---

## Overview

This is a single-file HTML portfolio website built for Dominion Majemu-Itura Aseyege (Xcel). It covers all three of his professional worlds — Web3 & blockchain, ministry & community, and music — in one cohesive, production-grade site.

The site is fully self-contained: no frameworks, no build step, no dependencies beyond Google Fonts. Drop the HTML file anywhere and it works.

---

## Features

- **Custom animated cursor** with a lagging ring effect
- **Scroll-triggered fade-in animations** on every section
- **Sticky nav** that transitions from transparent to dark on scroll
- **Responsive layout** — works on desktop and mobile
- **Google Drive photo integration** — hero image auto-loads from Drive link
- **All sections:** Hero, About, Pillars, Web3, Ministry, Music, Projects, Speaking, Contact, Footer

---

## Sections

| Section | Description |
|---|---|
| **Hero** | Full-screen intro with name, tagline, role tags, and key stats |
| **About** | Bio, the Ecclesiastes 12:1 mandate, and social links |
| **Three Worlds** | Web3, Ministry, and Music pillars laid out on a dark grid |
| **Web3 & Blockchain** | Key highlights from Web3Bridge partnerships work + role card |
| **Ministry** | Chapel 121 overview, events (Remember '26, Yovel, AITM, Media) |
| **Music** | Sovereign Records / Covenant Sound, artist roster, label vision |
| **Projects** | 6 real projects across Web3, ministry, and music |
| **Speaking** | Talk topics and a booking prompt |
| **Contact** | Links to email, Twitter/X, GitHub, and Web3Bridge |

---

## Tech Stack

| Layer | Choice |
|---|---|
| Structure | Semantic HTML5 |
| Styling | Vanilla CSS (custom properties, grid, flexbox) |
| Interactivity | Vanilla JavaScript (no libraries) |
| Fonts | Google Fonts — Bebas Neue, Syne, DM Sans |
| Hosting | Any static host or WordPress (see below) |

---

## Design System

```
Colors
  --ink:        #0a0a0a   (primary dark)
  --cream:      #faf7f2   (background)
  --paper:      #f5f0e8   (alternate section background)
  --gold:       #c8973a   (accent)
  --gold-light: #e8b84b   (hover state)
  --muted:      #6b6560   (body text)

Typography
  Display:  Bebas Neue      (hero name, large section labels)
  Headings: Syne 700/800    (section titles, card titles)
  Body:     DM Sans 300–500 (paragraphs, tags, metadata)
```

---

## Deploying to WordPress

There are three ways to use this on WordPress:

**Option 1 — WP Coder Plugin (recommended)**
1. Install the free [WP Coder](https://wordpress.org/plugins/wp-coder/) plugin
2. Create a new snippet, paste the full HTML file content
3. Create a blank WordPress page and embed the shortcode WP Coder gives you

**Option 2 — Elementor / Divi HTML Widget**
1. Create a blank page in WordPress with Elementor or Divi
2. Drag an HTML widget onto the canvas
3. Paste the full HTML content into the widget

**Option 3 — Custom Page Template**
1. In your active theme folder, create a file called `page-portfolio.php`
2. Add the standard WordPress template header comment at the top
3. Paste the HTML below it and assign the page template to your portfolio page

---

## Updating Content

Since this is a single HTML file, all edits are made directly in the file. Key areas:

- **Your photo** — update the Google Drive file ID in the `<script>` block at the bottom:
  ```js
  const fileId = 'YOUR_GOOGLE_DRIVE_FILE_ID_HERE';
  ```
- **Stats** — search for `.stat-num` content in the Hero section
- **Projects** — each `.project-card` block in the Projects section
- **Speaking topics** — each `.talk-item` block in the Speaking section
- **Contact links** — update `href` values in the `#contact` section and footer

---

## Links

| Platform | URL |
|---|---|
| GitHub | [github.com/Codeinx](https://github.com/Codeinx) |
| Twitter / X | [@MajemuItura](https://x.com/MajemuItura) |
| Web3Bridge | [web3bridgeafrica.com](https://web3bridgeafrica.com) |
| Chapel 121 | [chapel121.xyz](https://chapel121.xyz) |

---

## Author

**Dominion Majemu-Itura Aseyege (Xcel)**
Partnerships & Strategic Growth — Web3Bridge Africa
Founder — Chapel 121 (COTGLOBAL)
Lagos, Nigeria

---