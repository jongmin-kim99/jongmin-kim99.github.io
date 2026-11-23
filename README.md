# jongmin-kim99.github.io

Personal academic website of Jongmin Kim, built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme (MIT license).

## Where to edit

| What                      | File                         |
| ------------------------- | ---------------------------- |
| Name, URL, site settings  | `_config.yml`                |
| Bio and research interests | `_pages/about.md`            |
| Publications              | `_bibliography/papers.bib`   |
| CV page                   | `_data/cv.yml`               |
| Email / GitHub / Scholar  | `_data/socials.yml`          |
| Profile photo             | `assets/img/prof_pic.jpg`    |
| News items                | `_news/*.md`                 |
| Blog posts                | `_posts/*.md`                |

## Deployment

Pushing to `main` runs `.github/workflows/deploy.yml`, which builds the site and pushes it to the `gh-pages` branch.
GitHub Pages must be set to serve from the `gh-pages` branch. See `docs/INSTALL.md` for local builds (Docker or Ruby).
