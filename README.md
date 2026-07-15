# abhmul.github.io

A deliberately simple personal academic website for Abhijeet Mulgund.

## Architecture

The site is plain semantic HTML and CSS, with no framework, build step, JavaScript, package dependencies, analytics, or external font requests. GitHub Pages serves the files directly from the root of the `main` branch.

## Local preview

From the repository root, run any static file server, for example:

```sh
ruby -run -e httpd . -p 4000
```

Then open <http://localhost:4000>.

## Updating

- About and contact: `index.html`
- Publications: `publications/index.html`
- CV: `cv/index.html`
- Shared styles: `assets/styles.css`
- Portrait: `assets/abhijeet-mulgund-2026.jpg`
- Browser icon: `assets/favicon.svg`

Push changes to `main`; GitHub Pages will publish them automatically.
