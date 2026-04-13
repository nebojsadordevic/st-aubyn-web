# St Aubyn Lodge of MMM No. 64 — Website

Static website for St Aubyn Lodge of Mark Master Masons No. 64, under the Grand Lodge of Mark Master Masons of England and Wales.

## Tech Stack

- Plain HTML + CSS (no frameworks, no build step)
- Hosted on GitHub Pages with custom domain: **staubyn64.org**

## File Structure

```
index.html          — single-page invitation/info site
css/style.css       — all styles
assets/images/      — images served on the site
resources/          — source materials (PDFs, original graphics) — not served directly
CNAME               — GitHub Pages custom domain config
```

## Design

- **Palette:** navy (#1a2744), gold (#c8a84e), cream (#faf8f2)
- **Fonts:** Cormorant Garamond (headings), Inter (body) — loaded from Google Fonts
- **Tone:** formal, dignified, appropriate for a Masonic lodge

## Conventions

- Keep it simple — single HTML file, single CSS file
- No JavaScript unless strictly necessary
- All external links open in new tabs (`target="_blank" rel="noopener"`)
- Images go in `assets/images/`, source materials in `resources/`
