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
