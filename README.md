# VINE Research

The public research site for VINE — a geometric AI platform built by NEXICOG Ltd.

This repository holds the curated, leak-scanned build output published at
[vineai.net/research](https://vineai.net/research). One core algorithm, proved
across many domains; the portfolio is organised into reading-path buckets
(Orientation → Mechanism → Cognitive → World → Tower → Conductor → Observations).

## Layout

- `index.html` — landing page
- `provenance.html` — the OZ-to-Vine arc, dated
- `portfolio/` — formal evidence, results, behaviour, case studies
- `devlog/` — day-by-day notebook of what was built and why
- `sessions/` — session notes
- `tags/` — tag indices
- `static/` — site CSS and fonts
- `rss.xml` — dev log feed
- `sitemap.xml` — site map

## Serving

Pages use absolute paths for shared assets (`/vine_theme.css`, `/favicon.svg`),
so they render correctly when served from the root of a domain. To preview
locally:

```
python -m http.server 8000
```

then open `http://localhost:8000/`.
