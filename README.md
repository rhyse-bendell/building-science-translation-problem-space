# Building a Problem Space for Science Translation

Static project website built with Jekyll and hosted by GitHub Pages.

## Local development

1. Install Ruby and Bundler.
2. Run `bundle install`.
3. Run `bundle exec jekyll serve`.
4. Open the local URL printed by Jekyll. Because this is a project site, its configured base path is `/building-science-translation-problem-space/`.

Use `bundle exec jekyll build` to create a production build in `_site/`.

## Publishing

Pushes to `main` trigger the Pages deployment workflow. Repository settings must use **GitHub Actions** as the Pages source.

## Public site and private materials

This repository is public, and GitHub Pages serves static public files. Anything committed here can become publicly retrievable. Do not commit access codes, private links, internal planning files, unapproved PDFs, private participant materials, recruitment lists, or other sensitive information.

Approved public documents may be placed under `assets/docs/public/`. Private or controlled documents must not be committed; store and distribute them through approved, controlled-access channels. The site may list private materials as “distributed by invitation,” but it must not host them publicly.

### Pre-publication checklist

- [ ] No real study access code in the repository.
- [ ] No real response-platform link in the repository.
- [ ] No private documents under `assets/docs/`.
- [ ] No internal meeting notes.
- [ ] No Zoom or Google Doc links.
- [ ] No private email addresses unless approved for public posting.
- [ ] No participant lists or recruitment spreadsheets.
- [ ] The Materials page links only to approved public files.

See [`docs/publication-checklist.md`](docs/publication-checklist.md) for the maintainer checklist.
