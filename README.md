# Traffic Research Weekly

A Chinese static single-page archive of recently published transport research papers.

## Repository contents

- `index.html` — the deployable static website
- `transport_weekly_reports/seen_papers.json` — DOI records used to avoid duplicate weekly entries
- `.github/workflows/deploy-pages.yml` — automatic GitHub Pages deployment workflow

Each paper is presented as a concise research brief: question, method, and finding or practical value.

## Publish with GitHub Pages

1. Upload or commit these files to the `main` branch through the GitHub website.
2. Open **Settings → Pages → Build and deployment** and set **Source** to **GitHub Actions**.
3. Every subsequent commit to `main` will deploy the website automatically. You can also run **Deploy static site to GitHub Pages** manually from the **Actions** tab.
