# Winter Moments — Responsive Gallery Website

A responsive clone of the Tooplate "Winter Gallery" reference site, built with plain **HTML5** and **CSS3** (media queries only — no CSS frameworks, no JavaScript).

## Structure
- `index.html` — page markup (Hero, Gallery, About, Contact, Footer)
- `style.css` — all styling + responsive breakpoints

## Features
- Fixed header with logo + nav (turns into a slide-in burger menu on mobile)
- Full-height hero section
- Gallery grid with **CSS-only** category filtering (All / Landscapes / Decorations / Food / Family) — done with hidden radio inputs + sibling selectors, no JS needed
- About section with stats (Years Experience / Photos Captured)
- Contact form (Name / Email / Message) styled to match reference
- Footer with contact details

## Breakpoints
| Range | Layout |
|---|---|
| 1200px+ (Desktop) | 3-column gallery grid, full horizontal nav |
| 768px–1199px (Tablet) | 2-column gallery grid, stacked About section |
| below 768px (Mobile) | 1-column gallery grid, burger nav menu |

## How to run locally
Just open `index.html` in a browser — no build step required.

## Deploy
Drag-and-drop the folder onto Netlify, or run `vercel` / `netlify deploy` from inside this directory, or connect the GitHub repo directly in either dashboard.

## Notes
- Gallery/about images use placeholder photo URLs (picsum.photos) standing in for the reference site's winter photography — swap the `background-image` / `src` URLs in `index.html` with the actual reference images if you have them saved locally.
