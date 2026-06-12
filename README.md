# Yuhang Li — Personal Website

Personal academic website of [Yuhang Li](https://liyuhanglll.github.io), Ph.D. candidate in Electrical and Computer Engineering at UCLA, built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme.

## Local development

```bash
# requires Ruby >= 3 (e.g., brew install ruby)
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Editing content

- **About / homepage:** `_pages/about.md`
- **Publications:** `_bibliography/papers.bib` (entries with `selected = {true}` appear on the homepage)
- **News:** `_news/`
- **Research projects:** `_projects/`
- **CV:** `_data/cv.yml`
- **Social links:** `_data/socials.yml`
- **Site settings:** `_config.yml`

## Deployment

Pushing to `main` on GitHub triggers `.github/workflows/deploy.yml`, which builds the site and publishes it to the `gh-pages` branch for GitHub Pages.

## License

The theme is available as open source under the terms of the [MIT License](https://github.com/alshedivat/al-folio/blob/main/LICENSE).
