# abhmul.github.io

A deliberately simple personal academic website for Abhijeet Mulgund.

## Architecture

The site is plain semantic HTML and CSS, with no framework, build step, package dependencies, or external font requests. GitHub Pages serves the files directly from the root of the `main` branch. A small GoatCounter script provides privacy-friendly visitor analytics.

## Local preview

From the repository root, run any static file server, for example:

```sh
ruby -run -e httpd . -p 4000
```

Then open <http://localhost:4000>.

## Updating

- About and contact: `index.html`
- Publications: `publications/index.html`
- CV page: `cv/index.html` (document destination managed at `https://tiny.cc/abhijeet-cv`)
- Homepage styles: `assets/home.css`
- Interior-page styles: `assets/styles.css`
- Portrait: `assets/abhijeet-mulgund-2026.jpg`
- Extended desktop portrait: `assets/abhijeet-mulgund-2026-wide.jpg`
- Browser icon: `assets/favicon.svg`

Push changes to `main`; GitHub Pages will publish them automatically.
