# Hyuck Han — Academic Homepage

This repository contains the source for Hyuck Han’s academic homepage at
[hyuckhan.github.io](https://hyuckhan.github.io/). It is a small, custom Jekyll
site with no JavaScript or third-party front-end dependencies.

## Deployment

GitHub Pages builds and publishes the site from the repository’s `main` branch.
No separate deployment workflow is required.

## Local preview

With Jekyll installed, run:

```sh
jekyll serve
```

Then open `http://127.0.0.1:4000/`. A GitHub Pages-compatible installation can
also be used with `bundle exec jekyll serve` if a local Gemfile is added.

## Editing content

- Edit biography, education, experience, and contact details in `index.md`.
- Edit the research-interest list in `_config.yml`.
- Edit shared metadata and profile links in `_config.yml`.
- Edit presentation and responsive styles in `assets/css/style.css`.

The Publications navigation link is maintained in `_includes/header.html`.
Commented templates for future Teaching and Projects content are at the bottom
of `index.md`; matching disabled navigation links are in the header include.
Add real content before enabling those links.
