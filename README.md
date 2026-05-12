# Dolev Bashi website

This repository contains the static files for <https://dolevbas.github.io/>.
GitHub Pages serves the public site from the `master` branch.

## Current structure

- `index.html` is the main About page.
- `research/index.html` presents selected research themes, representative results, and a link to the ADS publication list.
- `DolevCV.pdf` is linked directly from the site navigation.
- `space-engineering/index.html` is retained in the repository, but it is currently hidden from the public navigation and sitemap. It also has `noindex` metadata, and `robots.txt` disallows `/space-engineering/`.
- `nano/`, `aboutme/`, and `2021-09-12-aboutme/` are lightweight redirects kept for older links.

## Site cleanup

The site was simplified from the previous template-based Jekyll setup into a small static website. The cleanup removed unused theme layouts, includes, sample posts, demo assets, JavaScript, and template configuration files. The remaining site is easier to maintain because the public pages are plain HTML with one shared stylesheet at `assets/css/site.css`.

## Design and content changes

- Updated the homepage around a concise About section, CV link, and publications link.
- Added a prospective-students note for the new Bar-Ilan University group opening in October 2026.
- Reworked the Research page around exoplanets, binary stars, multiple-star systems, compact objects, and Galactic-context astrophysics.
- Added selected research-result cards using existing figure assets and ADS links.
- Replaced template styling with a restrained academic visual style, responsive layout, sticky navigation, subtle hover states, and reduced-motion-aware transitions.
- Added `.nojekyll`, a sitemap, robots rules, a favicon, and a custom 404 page.
