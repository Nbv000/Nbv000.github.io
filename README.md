# nbv000.su

Personal site for nbv000.su, hosted on GitHub Pages.

## Local preview

```
python3 -m http.server 8000
```

Open http://localhost:8000

## Structure

- `index.html` — single-page site
- `style.css` — nothing fancy, ~160 lines
- `favicon.svg` — placeholder icon
- `CNAME` — custom domain for GitHub Pages

## Deploy

Push to `main` branch of the repository with Pages enabled. Custom domain set via `CNAME` file.

DNS: apex `nbv000.su` → A-records to GitHub Pages IPs:
- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153
