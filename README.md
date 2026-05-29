# FinsightCFO

Marketing website for **FinsightCFO** — AI-assisted CFO reports for small businesses.
Customers send their financial files; our team builds a CFO-style report with
AI-assisted analysis and delivers it back by email.

## Pages
- `index.html` — home (features, how it works, the report, pricing, what to submit)
- `team.html` — meet the founders / our story
- `privacy.html` — privacy policy *(draft — review with counsel)*
- `terms.html` — terms of service *(draft — review with counsel)*

## Stack
Static HTML/CSS/JS. No build step.
- `css/style.css` — shared styles (warm editorial brand: Newsreader + Hanken Grotesk)
- `assets/` — images and logo

## Local preview
```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy
Served via GitHub Pages from `main` (root). Pushing to `main` updates the live site.

---
© 2026 FinsightCFO, Inc.
