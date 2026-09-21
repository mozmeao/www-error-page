# www-error-page

[![Netlify Status](https://api.netlify.com/api/v1/badges/36bac8b9-b479-49ba-9c7e-d6c244dbd218/deploy-status)](https://app.netlify.com/sites/mozmeao-www-error-page/deploys)

A static page to display from our CDN in case of prolonged errors.

Still in use 2024-07-10

## Pages

- `site/index.html` — generic error/download page, served for every path via the `/*` catch-all.
- `site/whatsnew.html` — English-only, self-contained copy of Springfield's evergreen What's New Page,
  served for `/:locale/whatsnew/*` and `/whatsnew/*` so Firefox release-day WNP traffic gets something
  useful in any locale during an outage.
