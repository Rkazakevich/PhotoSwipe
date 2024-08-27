PhotoSwipe v5 — JavaScript image gallery and lightbox

### Repo structure

- `dist/` - main JS and CSS
- `src/` - source JS and CSS.
  - `src/js/photoswipe.js` - entry for PhotoSwipe Core.
  - `src/js/lightbox/lightbox.js` - entry for PhotoSwipe Lightbox.
- `docs/` - documentation markdown files.
- `demo-docs-website/` - website with documentation, demos and manual tests.
- `build/` - rollup build config.

To build JS and CSS in `dist/` directory, run `npm run build`.

To run the demo website and automatically rebuild files during development, run `npm install` in `demo-docs-website/` and `npm run watch` in the root directory.

This project is tested with [BrowserStack](https://www.browserstack.com/).
