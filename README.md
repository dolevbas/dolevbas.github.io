# Dolev Bashi website

This repository contains the static files for <https://dolevbas.github.io/>.
GitHub Pages serves the public site from the `master` branch.

## Current structure

- `index.html` is the main About page.
- `research/index.html` presents the main research themes, one representative scientific result, and a direct link to the ADS publication list.
- `DolevCV.pdf` is linked directly from the site navigation.
- `space-engineering/index.html` is retained in the repository, but it is currently hidden from the public navigation and sitemap. It also has `noindex` metadata, and `robots.txt` disallows `/space-engineering/`.
- `nano/`, `aboutme/`, and `2021-09-12-aboutme/` are lightweight redirects kept for older links; they now resolve to the homepage.

## Site cleanup

The site was simplified from the previous template-based Jekyll setup into a small static website. The cleanup removed unused theme layouts, includes, sample posts, demo assets, JavaScript, and template configuration files. The remaining site is easier to maintain because the public pages are plain HTML with one shared stylesheet at `assets/css/site.css`.

## Design and content changes

- Updated the homepage around a concise About section, CV link, and publications link.
- Updated the About page for the Senior Lecturer position and research group at Bar-Ilan University, together with the continuing Research Affiliate affiliation at Cambridge.
- Added a prospective-students section for the new Bar-Ilan University group.
- Reworked the Research page around exoplanets, binary stars, multiple-star systems, compact objects, and Galactic-context astrophysics.
- Integrated one representative research figure into the themes overview, removed the uneven results gallery, and kept a direct ADS publication link in the Research hero.
- Replaced the template-style page structure with a new visual direction: a fixed DB navigation rail on desktop, a compact top navigation on mobile, a full-bleed tug-of-war opening image, a two-column editorial About section, an animated research-area strip, a dark prospective-students section, and row-based research navigation.
- Used the rock photo as a secondary About image, made the tug-of-war photo the main first-viewport visual, and added an unframed lecture photo to the Research page.
- Added `.nojekyll`, a sitemap, robots rules, a favicon, and a custom 404 page.
