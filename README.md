# IP Sewa — GitHub Pages

A lightweight static landing page for IP Sewa, focused on intellectual property protection guidance for businesses in Nepal.

## Overview

This repository contains the GitHub Pages website for IP Sewa, with sections for:
- Trademark registration
- Patent registration
- Industrial design protection
- IP guidance and resources
- Service and process information

## Live site

- Website: https://ipsewa.github.io/
- Main business site: https://ipsewa.com/

## Files

- `index.html` — the landing page (services, free tools, process, guides, FAQ, network links)
- `404.html` — branded not-found page
- `assets/` — self-hosted Bootstrap 5.3.3 and DM Sans (no Google Fonts, no CDN)
- `robots.txt`, `sitemap.xml` — crawl hints for search engines
- `.nojekyll` — serve files as-is, without a Jekyll build
- `README.md` — project documentation

## Local preview

Open `index.html` directly in a browser, or run a simple local web server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deployment

This site is configured for GitHub Pages and is published from the repository root.

## Notes

The page is intentionally static and self-contained, making it easy to edit and deploy without a build step.
It makes **no API calls and runs no scripts** — the hero figures are fixed text, refreshed by hand when
a new bulletin ships. Every link points at a live ipsewa.com page; re-check them if a service or guide
URL changes.

## License

This project is provided as-is for the IP Sewa website and may be adjusted as needed for branding and content updates.
