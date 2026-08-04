# Payam Parvizi — Personal Website

Recruiter-facing portfolio for robotics, reinforcement learning, physics-based simulation, and sim-to-real research engineering.

## Deploy

This is a standard Jekyll site designed for GitHub Pages.

1. Replace the contents of the `payamparvizi.github.io` repository with these files.
2. Push to the default branch.
3. In **Settings → Pages**, select **Deploy from a branch** and the repository root.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

## Main files

- `index.html` — all homepage content
- `_layouts/default.html` — metadata, navigation, footer, and structured data
- `assets/css/site.css` — visual design and responsive behavior
- `assets/js/site.js` — mobile navigation and footer year
- `Payam_Parvizi_Robotics_RL_Resume.pdf` — public two-page résumé

## Updating content

Project descriptions, links, publications, experience, and education are intentionally kept in `index.html` so the site can be maintained without a build system or data pipeline.
