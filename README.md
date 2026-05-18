# Post Studio

> A browser-based 9:16 post creator for Instagram & TikTok. No backend. No install. One HTML file.

![](https://img.shields.io/badge/version-3.0-orange) ![](https://img.shields.io/badge/offline--ready-yes-green) ![](https://img.shields.io/badge/dependencies-0-blue)

---

## What it is

A single `.html` file that lets you design, customize, and export full-resolution social media posts (1080×1920 px) directly in the browser.

Pick a template → upload a photo → edit text → export PNG.

---

## Features

- **33 templates** — Dark (Founder style) + Light (Diary style)
- **24 color packs** — from Amber Gold to Neon Mint to Linen Cream
- **Photo editor** — drag to reposition, scroll to zoom, overlay opacity
- **Carousel mode** — multiple slides, exported individually
- **Project save/load** — full state as `.json` including photos
- **DE / EN** — language toggle built in
- **Responsive** — desktop 3-panel, tablet 2-panel, mobile tab bar
- **Auto-contrast** — text stays readable over any photo

---

## Usage

```bash
# Local — just open it
open post-studio-v3.html

# Or host anywhere static (GitHub Pages, Netlify, Vercel)
# No build step. No package.json. No server.
```

---

## Fonts

Loaded from Google Fonts (requires internet). Falls back to system fonts offline (`Segoe UI`, `Helvetica Neue`, `Impact`).

To embed fonts locally: download `.woff2` files from [fonts.google.com](https://fonts.google.com) and add inline `@font-face` rules to the `<style>` block.

---

## Customization

**Add a template** — append to `TPLS` array + add a `case` in `render()`.

**Add a color pack** — append to `CP` object with `bg`, `acc`, `hl`, `mu` values.

**Change defaults** — edit `handle` and `brand` in the `TPLS` defaults.

---

## Browser Support

Chrome 90+ · Firefox 90+ · Safari 16+ · Edge 90+ · iOS Safari 15+

---

## License

GPL
