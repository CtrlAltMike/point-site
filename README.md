# point.hendrick.net

The entry point for Michael Hendrick's professional signal — a single interactive
compass that routes visitors to four destinations:

- **Résumé** → LinkedIn
- **Curriculum Vitae** → cv.hendrick.net
- **Source Repo** → GitHub
- **Writing** → mike.hendrick.net

Built as a real-time GPU fluid field (Pavel Dobryakov's WebGL-Fluid-Simulation).
Hover the name or a bearing to ignite ink; the "Ink" toggle (top-right) disables it.

## Hosting

Static site served by GitHub Pages at the custom domain `point.hendrick.net`.

- `index.html` — the page (self-contained; loads React, the fluid solver, and fonts from CDN)
- `support.js` — the component runtime
- `CNAME` — custom-domain binding for GitHub Pages

No build step. Edit `index.html` and push to `main`.
