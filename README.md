# pedroarantes.com

Static personal site: `index.html`, `styles.css`, `favicon.svg` and the engraving plates in `assets/`. No build step.

The look follows the Flow design system (IBM Plex, ink on paper, elevation as a border, sea engravings inverted for the dark theme).

## Deploy

`.github/workflows/pages.yml` publishes the site to GitHub Pages on every push to `main`, and can be run by hand from the Actions tab. A new file the site serves must be added to its "Collect site files" step.
