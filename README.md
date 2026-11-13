# Junteng Liu — Homepage

Personal academic homepage for Junteng Liu, built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template, a fork of [Minimal Mistakes](https://mademistakes.com/work/minimal-mistakes-jekyll-theme/).

## Site content

- `_pages/about.md` — the home page: introduction, research interests & skills, education, research experience, honors, publications and contact information. Publications are listed here as well as on the publications subpage.
- `_pages/publications.html` and `_publications/` — the publications subpage and the individual publication records.
- `_config.yml` — site settings, author profile and contact links.
- `_data/navigation.yml` — the About and Publications navigation.

## Build locally

```bash
bundle install
bundle exec jekyll serve --baseurl "/LJT-Homepage"
```

## Deploy

`.github/workflows/jekyll.yml` builds the site with Jekyll and deploys it to GitHub Pages. The site is configured for a repository page at `https://spainricardo76522.github.io/LJT-Homepage/`.
