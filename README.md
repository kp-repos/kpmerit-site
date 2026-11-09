# kpmerit.com — holding page

Single static page (`index.html`). Logo and favicon are inline SVG; no external files.

**Two versions in one file**
- `1` — cobalt `#0A3CC8` page, white logo (live default)
- `2` — white page, cobalt logo

**Switch:** in `index.html`, change `data-version="1"` to `"2"` (top of file), commit, push.
**Preview without switching:** `kpmerit.com/?v=2` (or `?v=1`).

Hosted on GitHub Pages from `main` / root. `CNAME` sets the custom domain.
