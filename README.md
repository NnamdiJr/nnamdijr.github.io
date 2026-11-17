# Nnamdi Offor

Personal website, built with Jekyll and published with GitHub Pages.

## Local development

With Ruby and Bundler available:

```sh
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000. To build once: `bundle exec jekyll build`.

## Deployment

GitHub Pages currently builds from the `master` branch. Keep `CNAME` intact for
nnamdioffor.com. Develop on a branch and validate before merging to master.
The post filenames, content and permalink setting preserve the existing archive.
Legacy `/about.html` and `/contact.html` URLs redirect to the canonical pages.

## Design

The visual system lives in `css/site.css`. The home illustration is original SVG
markup, not a stock photo. Contact links use email, LinkedIn and GitHub rather
than the old unsupported PHP form. Typography loads from Google Fonts with local
system fallbacks. No client-side JavaScript is needed for navigation.
