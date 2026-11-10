# sangwookim.github.io

Personal CV site built on [sharu725/online-cv](https://github.com/sharu725/online-cv), with a monochrome (`mono`) skin.

## Editing content
- All content lives in `_data/data.yml`.
- Profile photo: put a square image in `assets/images/` and set `sidebar.avatar`.
- Up to three publication blocks (`publications`, `publications2`, `publications3`) and three experience blocks (`experiences`, `experiences2`, `experiences3`); comment out a block to hide it.
- Sidebar supports `orcid`, `scholar`, `pdf-en`, `pdf-kr` in addition to the template defaults.

## Colors
`_sass/skins/_mono.scss` — keep this file ASCII-only (non-ASCII comments break the GitHub Pages Sass build).

## Local preview
```bash
bundle install
bundle exec jekyll serve
```
