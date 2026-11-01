# Kiana Sherafati — personal website

A lightweight, English-language academic portfolio, published with GitHub Pages at
[kianasherafati.github.io](https://kianasherafati.github.io/).

## Local preview

No installation or build is required. From this directory, run:

```sh
python -m http.server 4173 --bind 127.0.0.1
```

Then visit `http://localhost:4173`.

## Updating content

- `index.html`: introduction, interests, selected work, teaching, and swimming.
- `projects.html`: six projects, technology tags, source links, and expandable details.
- `cv.html`: education, teaching, skills, training, and honors.
- `Kiana.CV.pdf`: downloadable CV. Replace this file when a newer CV is available,
  then update the dated overview, GPA, education status, and experience on the pages.
- `portrait.jpg`: site portrait; the original photograph is also retained.
- `style.css`: shared colors, typography, layout, responsive rules, and animations.
- `site.js`: progressive enhancements for project filtering, scroll reveals, and email copying.
- `favicon.svg`, `robots.txt`, and `sitemap.xml`: site identity and search metadata.

The academic content is based on the CV supplied in May 2025 and the existing
portfolio. No publications, research appointments, or newer qualifications are implied.
Project illustrations are decorative diagrams, not screenshots of the applications.

## Accessibility and deployment

Pages include keyboard focus indicators, skip links, semantic navigation, responsive
layouts, and reduced-motion support. Core content, links, CV downloads, and project
details work without JavaScript. The site uses system fonts and local assets;
it has no runtime dependencies, analytics, or external font requests.

GitHub Pages serves the static files directly from the configured publishing branch.
Preserve the existing filenames so incoming project and CV links continue to work.
