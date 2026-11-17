# Sankara Eye Care × Claude — Case Study Page

Static case study page: **Sankara Eye Care Reduces Medical Report Turnaround Time from 4 Hours to 15 Minutes Using Claude**.

Built to match the Quadra Systems site design (EB Garamond + Raleway, Quadra orange `#F26102`).

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole page (HTML + CSS + a little JS) |
| `quadra-logo.svg` | Quadra logo (header and footer) |
| `sankara-logo-hd.png` | Sankara Eye Care logo, high-resolution rebuild, transparent background |
| `case-study-banner.webp` | Hero banner image |
| `serve.js` | Tiny local preview server (not used by Vercel) |

## Run locally

```bash
node serve.js
```

Then open http://localhost:4321

## Deploy

Static site — Vercel serves `index.html` directly, no build step.

## Notes

- Outcome photo and the five avatar photos are free-licence images from Unsplash, loaded from `images.unsplash.com`.
- Other illustrations, the testimonial photo and the TÜV badges load from the live Quadra site (`framerusercontent.com`).
- The footer Subscribe form is not connected to a mailing list.
