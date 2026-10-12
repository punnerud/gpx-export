# Strava to Data: GPX & Stats – website

Static website for the iPhone app **Strava to Data: GPX & Stats**, served with GitHub Pages at
**https://punnerud.github.io/gpx-export/**.

| Page | URL |
|---|---|
| Home (marketing, pricing, FAQ) | https://punnerud.github.io/gpx-export/ |
| Privacy policy | https://punnerud.github.io/gpx-export/privacy.html |
| Support | https://punnerud.github.io/gpx-export/support.html |
| Terms of use | https://punnerud.github.io/gpx-export/terms.html |

App Store: https://apps.apple.com/app/id6741417217

## Structure

- Plain HTML and one stylesheet (`assets/site.css`). No JavaScript, no build step, no external fonts or CDNs.
- `assets/shots/` – app screenshots, 600 px wide, WebP with JPG fallback.
- `assets/icon.png`, `assets/favicon.png`, `favicon.ico`, `apple-touch-icon.png`, `assets/og-image.jpg` – icons and the social preview image (made with `strava_appstore_media/source/og_image.py`).
- `.nojekyll` – serve files as-is.

## Local preview

```sh
python3 -m http.server 8000
# open http://localhost:8000/
```

## Deploy

Push to `main`. GitHub Pages serves the repository root.

Not affiliated with or endorsed by Strava, Inc. Strava is a trademark of Strava, Inc.
