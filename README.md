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
