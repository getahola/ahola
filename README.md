# ahola — landing page

Static landing page for [ahola.app](https://ahola.app) — *The happiest way to meet people.*

Plain HTML/CSS, no build step. Deployed to GitHub Pages via [.github/workflows/deploy.yml](.github/workflows/deploy.yml).

## Structure

- `index.html` — the full landing page (inline styles)
- `CNAME` — custom domain (`ahola.app`)
- `.nojekyll` — serve files as-is (skip Jekyll processing)

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Deploy

Push to `main`; the workflow publishes to GitHub Pages. First-time setup:
Settings → Pages → Source: **GitHub Actions**.

## Related

- Demo prototype (`demo.ahola.app`) lives in a separate repo.
