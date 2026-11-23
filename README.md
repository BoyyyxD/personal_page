# Academic Website

Personal academic website: [boyyyxd.github.io/personal_page](https://boyyyxd.github.io/personal_page/).

## Update content

- `_config.yml`: profile, contact links, site settings, and theme.
- `_pages/about.md` and `_pages/cv.md`: biography and CV.
- `_publications/`: publication entries; put downloadable PDFs in `files/`.
- `_data/navigation.yml`: navigation. Blog and Guide links are commented out; template examples are excluded from the build in `_config.yml`.
- `_sass/theme/_air_light.scss` and `_air_dark.scss`: blue and slate colors.

Use `relative_url` for local links so they work under `/personal_page`.

## Preview locally

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve --livereload
```

Open `http://localhost:4000/personal_page/`. GitHub Actions builds and deploys the site; see `.github/workflows/jekyll.yml`.

Based on [Academic Pages](https://github.com/academicpages/academicpages.github.io), using Jekyll. See [LICENSE](LICENSE).
