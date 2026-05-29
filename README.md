# Waypoint Website

A Jekyll-based portfolio site for photography and geospatial projects.

## Included pages

- `index.md` — Home
- `about.md` — About
- `photography.md` — Photography
- `maps.md` — Maps
- `resume.md` — Resume

## Local development

1. Install Ruby and Bundler if needed.
2. Install Jekyll:
   ```bash
   gem install bundler jekyll
   ```
3. From the repo root:
   ```bash
   jekyll serve
   ```
4. Open `http://127.0.0.1:4000`

## Deploy to GitHub Pages

1. Push this repository to GitHub.
2. In the repo settings, enable GitHub Pages.
3. Choose the `gh-pages` branch as the source.
4. The site will be available at `https://<username>.github.io/<repository>`.

## GitHub Actions deployment

This repository includes a workflow at `.github/workflows/deploy.yml` that:

- installs Jekyll
- builds the site into `_site`
- deploys to the `gh-pages` branch automatically on every push to `main`

## Notes

- The site uses a simple custom layout in `_layouts/default.html`.
- Add your content to the Markdown files and update styles in `assets/css/styles.css`.
