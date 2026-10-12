# Joonsuh Yoon — personal website

Static, GitHub Pages-ready website with a printable CV. No build tools or dependencies are required.

## Preview

Open `index.html` in a browser, or run `python3 -m http.server 8000` in this directory.

## Files

- `index.html`: homepage content
- `cv.html`: printable CV; use Print / Save PDF
- `style.css`, `tokens.css`: responsive layout and typography
- `assets/`: images supplied from appendix0/fetch_here and favicon

The layout follows the compact academic-page style of [Jon Barron](https://jonbarron.info/). This implementation uses semantic HTML and responsive CSS rather than layout tables.

## GitHub Pages

Place these files at the root of `appendix0/appendix0.github.io`. In repository Settings → Pages, deploy from the main branch and root directory. `.nojekyll` keeps the site buildless.

## Content notes

Public contact email and profile photo have not been supplied; no placeholder identity or email is shown. CS285 is accurately presented as independent study. Award labels retain the user's Korean wording. Image assets were supplied through fetch_here: the original diagram and Memex screenshot at commit 28a4b68, and PincerCraft artwork (`0E0BEF60-2881-4069-84B0-18CFF31B40B9.png`) and gameplay (`IMG_1121.png`) at commit a9960ba.
