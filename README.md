# WChampFX — $1M Funded Challenge (`1mil.wchampfx.com`)

Static landing page deployed via Coolify (Dockerfile → `nginx:alpine`, port 80).

- `index.html` — the page. VSL embed + Typeform URL live in `WCHAMPFX_CONFIG` at the bottom of the file.
- `nginx.conf` — serves `/` with no-cache HTML, `/healthz` healthcheck.
- Coolify app: Product → staging, domain `https://1mil.wchampfx.com`, build pack `dockerfile`.
