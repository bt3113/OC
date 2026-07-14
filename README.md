# Orbit Capital

A clean-room, original implementation of a cinematic AI-finance landing page. It recreates the broad interaction language of premium immersive finance sites—dark spatial canvas, a procedural rotating globe, glass UI, scroll reveals, metric cards, service sections and pricing—without copying proprietary source code or protected media.

## Run locally

No build step or package installation is required.

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080`.

## Deploy

A GitHub Pages workflow is included and publishes the repository root whenever `main` changes. The project can also be deployed directly to Netlify, Cloudflare Pages or Vercel.

- Build command: none
- Output directory: repository root

## Structure

- `index.html` — self-contained page, responsive CSS and procedural Canvas animation
- `.github/workflows/pages.yml` — automatic GitHub Pages deployment

## Notes

- All graphics are generated with CSS, SVG data and Canvas 2D.
- No third-party website assets or source code are included.
- Replace placeholder contact links before production use.
