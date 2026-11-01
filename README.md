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

- `index.html`: short academic introduction, thesis summary, three selected projects,
  a brief experience overview, and a personal note about swimming.
- `projects.html`: four selected projects with expandable implementation details;
  six earlier projects remain available in the “More coursework” disclosure.
- `cv.html`: education, research, professional experience, projects, teaching, skills,
  honors, and languages.
- `Academic_CV.pdf`: current downloadable CV. `Kiana.CV.pdf` contains the same
  document so existing incoming download links remain current. Replace both when
  updating the CV, then synchronize the GPA, degree status, and experience on the pages.
- `portrait.jpg`: site portrait; the original photograph is also retained.
- `style.css`: shared colors, typography, layout, responsive rules, and animations.
- `site.js`: progressive enhancements for scroll reveals and email copying.
- `favicon.svg`, `robots.txt`, and `sitemap.xml`: site identity and search metadata.

Academic and professional content follows the updated CV supplied in November 2026.
Project descriptions also draw on the linked public GitHub repositories. The thesis
result is macro schema-retrieval recall at 20 tables in the thesis experiments;
it does not represent query-generation accuracy. Coursework scope and attributions
remain documented in the respective repositories. The homepage is a concise overview;
the CV and linked repositories carry the full academic and technical detail.

## Accessibility and deployment

Pages include keyboard focus indicators, skip links, semantic navigation, responsive
layouts, and reduced-motion support. Core content, links, CV downloads, and project
details work without JavaScript. The site uses system fonts and local assets;
it has no runtime dependencies, analytics, or external font requests.

GitHub Pages serves the static files directly from the configured publishing branch.
Preserve the existing filenames so incoming project and CV links continue to work.
