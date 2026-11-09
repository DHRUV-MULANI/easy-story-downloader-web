# Easy Story Downloader — web

Public landing page + privacy policy for the Easy Story Downloader Android app.

- `index.html` — landing page
- `privacy.html` — privacy policy (use this URL in Google Play Console)
- `styles.css`, `assets/` — styling

This site is static. It intentionally does **not** implement media downloading:
a browser-only downloader cannot call Instagram directly (CORS) and would need a
backend scraper. The downloader runs in the Android app.
