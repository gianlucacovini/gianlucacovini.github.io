# gianlucacovini.github.io

Source for Gianluca Covini's personal academic website, built with Jekyll and
published through GitHub Pages.

## Local preview

With Ruby and Bundler installed:

```bash
bundle install
bundle exec jekyll serve
```

The site can also be run with the included `Dockerfile`.

## Content

Public pages live in `_pages/`; downloadable documents live in `assets/files/`.
The Research page is deliberately kept out of `_data/navigation.yml` until the
next preprint is ready. Do not remove `_pages/research.md` or its files under
`assets/files/Publications/` and `assets/files/Talks/`.

The CV sources are stored beside their compiled PDFs under `assets/files/CV/`.
Only the PDFs inside the `build` directories are versioned; LaTeX intermediate
files are ignored.

The visual theme is based on
[Academic Pages](https://github.com/academicpages/academicpages.github.io),
itself derived from Minimal Mistakes. See `LICENSE` for the original theme
license.
