# Crop Care

Crop Care is a multilingual smart farming web app for Indian farmers. It includes modules for dashboards, crop recommendation, fertilizer guidance, disease detection, government schemes, market prices, farming calendar, weather, soil health, irrigation, farmer profile, alerts, a chat assistant and admin analytics.

## Run locally

Open index.html directly in a browser, or serve the folder with a simple local server:

```bash
python -m http.server 8000
```

Then open http://localhost:8000/.

## GitHub upload

Upload the whole folder to GitHub as a repository. The app is fully client-side and needs no backend setup.

## Deploy to GitHub Pages (automatic)

This repository includes a GitHub Actions workflow that deploys the `main` branch to a `gh-pages` branch on every push.

1. Push your project to GitHub (set your remote and push `main`).
2. The workflow `.github/workflows/deploy.yml` will run automatically and publish the site to `gh-pages`.
3. After the workflow completes, enable Pages in the repository Settings → Pages and choose the `gh-pages` branch (if required).

If you prefer manual publishing, you can also enable Pages to serve from the `main` branch or create a `gh-pages` branch yourself.
