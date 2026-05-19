# DoHyun Lim Resume Site

Personal resume and project portfolio site for `https://dororo99.github.io`, built with the Academic Pages Jekyll template and hosted on GitHub Pages.

## Local Development

This repository intentionally does not use Docker or Dev Containers.

```bash
bundle install
bundle exec jekyll build
bundle exec jekyll serve -l -H localhost
```

The local preview runs at `http://localhost:4000`.

## Content

- `_pages/about.md` - homepage summary
- `_pages/cv.md` - web CV
- `_pages/publications.html` - publications index
- `_portfolio/` - project writeups
- `_publications/` - publication entries

To add a paper, copy the example from `_templates/publication.md` to a new `.md` file in `_publications/`, update the front matter, and commit the file.

## Template Credit

This site is based on [Academic Pages](https://github.com/academicpages/academicpages.github.io), which is released under the MIT License.
