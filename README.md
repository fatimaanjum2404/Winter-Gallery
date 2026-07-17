# Winter Gallery — Final Responsive Build

This is the **real Tooplate "Winter Gallery" template** (the actual reference site's own files),
with one addition: explicit desktop / tablet / mobile breakpoints layered on top, as required by
the assignment brief.

## Files
- `index.html` — original template markup (real content, real image URLs, real gallery structure)
- `tooplate-winter-gallery.css` — original template styles **plus** an appended block at the bottom
  titled "ADDED FOR ASSIGNMENT REQUIREMENT" with explicit breakpoints:
  - **1200px+** → 3-column gallery grid (desktop/laptop)
  - **768px–1199px** → 2-column gallery grid (tablet)
  - **below 768px** → 1-column gallery grid (mobile)
- `tooplate-winter-scripts.js` — original template's gallery filter + lightbox JS (unchanged)

## About the images
All images are hotlinked directly from `images.unsplash.com` — **exactly like the original
reference site does**. There are no local image files because the real template doesn't ship any;
it links straight to Unsplash's CDN. This is intentional and matches the reference 1:1.

Unsplash's CDN is a large, reliable, globally distributed host — this should resolve the earlier
mobile-loading issue, which was most likely caused by the placeholder image host used in an
earlier draft, not by anything in your code.

## Deploy
Push this folder as-is to GitHub, then deploy on Netlify or Vercel. No build step needed.

## If images still don't load on a specific phone
That would point to that device/network blocking `images.unsplash.com` specifically (rare, but
possible with some corporate/campus wifi or content filters) — try switching to mobile data to
confirm before assuming it's a code issue.
