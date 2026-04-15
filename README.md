# St Aubyn Lodge of MMM No. 64

Static website for **St Aubyn Lodge of Mark Master Masons No. 64**, under the Grand Lodge of Mark Master Masons of England and Wales.

The site currently hosts the invitation and practical information for the Lodge's Reponement Ceremony in Belgrade, 30 May 2026.

**Live:** <https://staubyn64.org>

## Tech

Plain HTML + CSS — no frameworks, no build step, no package manager.

- `index.html` — single-page invitation / info site
- `css/style.css` — all styles
- `assets/images/` — images served on the site
- `resources/` — source materials (PDFs, original graphics) — not served directly
- `CNAME` — GitHub Pages custom domain (`staubyn64.org`)

## Local preview

Open `index.html` directly in a browser, or serve the directory:

```
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deployment

Pushes to `main` are deployed automatically by GitHub Pages. The custom domain is configured via the `CNAME` file and DNS at the domain registrar.

## Contact

Organising Secretary — <orgsec@staubyn64.org>

---

© St Aubyn Lodge of Mark Master Masons No. 64
