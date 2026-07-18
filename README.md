# Matty's Cafe — Bath

One-page website for Matty's Cafe, 15 St Peter's Terrace, Lower Bristol Road, Bath BA2 3BT.

- `index.html` — the whole site (self-contained HTML/CSS/JS, no build step)
- `fonts.css` — self-hosted fonts (Young Serif, Work Sans, IBM Plex Mono; SIL OFL licensed)
- `img/` — photos and the Matty's logo

## Publishing

Serve the repo root with any static host. For GitHub Pages:
Settings → Pages → Deploy from a branch → `main` / root.

To point a custom domain (e.g. mattyscafe.com) at it: add the domain in the
Pages settings, set a CNAME record for `www` to `forstermax847-crypto.github.io`,
and A records on the bare domain to GitHub Pages IPs
(185.199.108.153, .109.153, .110.153, .111.153). Keep existing MX records
untouched so email keeps working.
