# Noosa Long Weekend — Kathy's 60th

Interactive itinerary for a 4-day Noosa trip, Jul 30 – Aug 2, 2026.

**Live site:** https://wadejensen.github.io/noosa-2026/

## File layout

- `index.html` — the presentation. References `assets/` for images.
- `assets/` — airbnb photos referenced by `index.html`.
- `itinerary.md` — text version of the schedule (source of truth for bookings + timings).
- `.nojekyll` — disables Jekyll processing (required so `{{ }}` template patterns in the presentation aren't mangled).
- `.gitignore` — ignores `.DS_Store`.

## Enabling GitHub Pages (one-time)

1. Push this repo to GitHub.
2. Repo → **Settings** → **Pages**.
3. **Source**: Deploy from a branch. **Branch**: `main`, **Folder**: `/ (root)`. Save.
4. Wait ~1 minute — the site should be live at the URL above.

## Browser requirements

Modern browser (Safari 16.4+, Chrome 80+, Firefox 113+). The presentation uses `DecompressionStream` and `URL.createObjectURL` — both standard in current browsers.
