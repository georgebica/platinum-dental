# Platinum Dental — Slatina

Website for **Platinum Dental**, a dental clinic in Slatina, Olt, led by Dr. Arin Lupașcu.

## Structure

- `index.html` — homepage (hero, despre, liquid-glass service & pricing panels, reviews, program, contact)
- `servicii/` — five SEO-optimized service pages, one per treatment area
- `servicii/service.css` — shared styles for the service pages
- `hero/`, `cabinet-about.mp4` — media assets
- `robots.txt`, `sitemap.xml`, `llms.txt` — crawler / SEO files

## Running locally

It is a static site — no build step. Serve the folder with any static server:

```bash
python -m http.server 8000
```

Then open <http://127.0.0.1:8000/>.
