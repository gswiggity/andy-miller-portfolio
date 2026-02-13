# Andy Miller Portfolio — Claude Instructions

## Project Overview
Static portfolio website for Andy Miller (film school student). Showcases YouTube video work, creator photo, and bio.

## Tech
- Plain HTML/CSS/JS — no framework, no build step
- Deployed on Vercel (static output from `src/`)
- Target URL: https://andymiller.vercel.app

## Structure
- `src/index.html` — Single page, all content here
- `src/styles/main.css` — All styles, CSS custom properties for theming
- `src/scripts/main.js` — Scroll behavior, nav active state
- `src/assets/images/` — Creator photo and any media

## Design
- Dark palette anchored on #3e73e7 (blue)
- All color tokens in `:root` in main.css
- Professional but not minimal — gradient accents, glow effects, card hover animations
- Font: Inter (Google Fonts)

## Key Rules
- No build step — everything in `src/` is served directly
- Keep it a single page (no routing)
- YouTube embeds use standard iframe embed URLs
- Creator photo should use `object-fit: cover` in the hero image container
