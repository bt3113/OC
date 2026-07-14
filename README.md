# Orbit Capital

A clean-room, original implementation of a cinematic AI-finance landing page. It recreates the broad interaction language of premium PeachWeb/WebGL sites—dark spatial canvas, rotating financial globe, glass UI, scroll reveals, metric cards and pricing—without copying proprietary source code or protected media.

## Run locally

No build step or package installation is required.

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080`.

## Deploy

The project is static and can be deployed directly with GitHub Pages, Netlify, Cloudflare Pages or Vercel.

- Build command: none
- Output directory: repository root

## Structure

- `index.html` — semantic page content
- `styles.css` — responsive visual system and animations
- `app.js` — procedural canvas globe, interaction and reveal logic
- `assets/favicon.svg` — original project mark

## Notes

- All graphics are generated with CSS, SVG and Canvas 2D.
- No third-party site assets or source code are included.
- Replace placeholder contact links before production use.
