# Chris Johnston personal site (Quarto)

This repository contains a Quarto-based academic website with pages for research, teaching, and a markdown CV.

## Local development

1. Install [Quarto](https://quarto.org/docs/get-started/).
2. Render the site:

   ```bash
   quarto render
   ```

3. Preview locally:

   ```bash
   quarto preview
   ```

## Updating the CV

Edit `cv.qmd` directly. If you prefer a data-driven approach later, you can migrate CV entries into a `.bib` file and let Quarto render selected sections automatically.

## GitHub Pages deployment

This repo includes a GitHub Actions workflow at `.github/workflows/deploy.yml` that renders the Quarto project and deploys `_site` to GitHub Pages.

To finish setup in GitHub:

1. Go to **Settings → Pages**.
2. Under **Build and deployment**, choose **Source: GitHub Actions**.
3. In **Settings → Environments → github-pages**, allow deployments from this branch as needed.

The custom domain is configured via `CNAME` as `cdjohnston.com`.
