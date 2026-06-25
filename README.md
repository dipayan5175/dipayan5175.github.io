# Dipayan Banik Academic Portfolio

This repository powers my GitHub Pages academic website at `dipayan5175.github.io`.

The site is a single-page academic portfolio focused on research, publications, work experience, CV, and contact information.

## Site Sections

- Home
- About
- Work & Academics
- Research
  - Conference Papers
  - Workshops
  - Posters
- CV
- Contact

## Key Files

- `index.html` - Main website content and page structure.
- `assets/css/style.css` - Custom styling for the template and academic publication layout.
- `assets/js/main.js` - Template JavaScript for navigation, animation, and scrolling behavior.
- `assets/img/website.jpg` - Sidebar/profile photo.
- `assets/img/background.jpg` - Hero background image.
- `Academic_CV-Dipayan.pdf` - Linked academic CV.

## Preview Locally

Because this is a static site, it can be opened directly in a browser:

```text
index.html
```

For a local web server, run one of:

```powershell
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Updating Content

Most academic content is in `index.html`.

Common updates:

- Add accepted or under-review papers in the `Research` section.
- Update publication links by editing the paper title anchor.
- Add award notes using `publication-note`.
- Replace `Academic_CV-Dipayan.pdf` when the CV changes.
- Update profile and hero images in `assets/img/`.

## Credits

The site is adapted from the BootstrapMade iPortfolio template and customized for an academic portfolio.
