# Advocacy AI Training Series — Clone

Faithful clone of **https://events.helloeiko.com/lilly-advocacy-ai** (the "Advocacy AI Training Series" landing page) and its internal registration sub-pages.

## Structure
- `capture/` — raw capture spec for every page (full-page screenshots at 1440px & 390px, rendered `page.html`, `styles.json`, `assets.txt`, `fonts.txt`, `embeds.txt`, `meta.txt`, `links.txt`, plus downloaded `assets/`).
- `site/` — the rebuilt static site deployed to Vercel (one folder per page).

## Pages
- `/lilly-advocacy-ai` — main landing page (home)
- `/privacy` — privacy & consent
- `/e/<workshop>` — 10 workshop overview pages
- `/e/<workshop>-<date>` — 22 date-specific registration pages
