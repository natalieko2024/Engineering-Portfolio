# Mechatronics portfolio (Quarto)
- Preview: `quarto preview` · Build: `quarto render`
- Edit content in the `.qmd` files. Each project lives in `projects/<slug>/index.qmd` (put `images/`, `videos/`, `docs/` beside it).
- Experience detail pages live in `experience/` and are linked from the home strip and résumé, not the navbar.
- Colors: `styles.css` (`:root` and `body.quarto-dark` variables) and `custom-*.scss`.
- Deploy: push to `main`; `.github/workflows/publish.yml` publishes to GitHub Pages (set Pages source to the `gh-pages` branch).
