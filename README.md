# Noosa Long Weekend — Kathy's 60th

Interactive itinerary for a 4-day Noosa trip, Jul 30 – Aug 2, 2026.

**Live site:** https://wadejensen.github.io/noosa-2026/

## What's in the repo

- `index.html` — the presentation itself. Single self-contained HTML file (~2.2 MB) with all assets (fonts, images, React) embedded and unpacked at runtime.
- `.nojekyll` — tells GitHub Pages to skip Jekyll processing. Required because the presentation uses `{{ }}` template patterns that Jekyll would otherwise mangle.

## Enabling GitHub Pages (one-time)

1. Push this repo to GitHub.
2. Repo → **Settings** → **Pages**.
3. Under **Source**: select **Deploy from a branch**.
4. **Branch**: `main`, **Folder**: `/ (root)`. Save.
5. Wait ~1 minute — the site should be live at the URL above.

## Browser requirements

Modern browser (Safari 16.4+, Chrome 80+, Firefox 113+). The presentation uses `DecompressionStream` and `URL.createObjectURL` — both standard in current browsers.
