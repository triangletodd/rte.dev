# rte.dev

Personal website of **Todd Edwards**, focused on cloud, DevOps, Linux, developer tooling, and platform engineering.

## Design

A lightweight cyberpunk portfolio using a dark navy palette with neon cyan, magenta, and purple accents. The site is built with plain HTML and CSS—no JavaScript framework or build step required.

## Local preview

Open `index.html` in a browser. For more reliable absolute-path asset loading, run a small local server at the repository root:

```sh
python3 -m http.server 8000
```

Visit `http://localhost:8000`.

## Editing

- `index.html` — page content, project links, contact information, and metadata
- `assets/css/cyberpunk.css` — the live stylesheet and theme tokens (`:root`)
- `assets/images/terminal-mark.svg` — terminal favicon
- `assets/images/avatar.jpg` — existing portrait

The older CSS and Sass assets remain in the repository for history, but the new page only uses `assets/css/cyberpunk.css`.

## Deployment

The repo preserves `CNAME` (for `rte.dev`), `_config.yml`, and `.well-known/`. It is designed to remain compatible with a static GitHub Pages deployment.

## Accessibility and performance

- Semantic page landmarks and headings
- Keyboard focus indicators and a skip link
- Reduced-motion support
- Responsive mobile layout
- No JavaScript or client-side dependencies
- Only font requests to Google Fonts; local system font fallbacks are provided

## Links

- [Live site](https://rte.dev)
- [GitHub](https://github.com/triangletodd)
- [LinkedIn](https://www.linkedin.com/in/triangletodd/)
