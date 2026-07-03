# point.hendrick.net

Tiny personal wayfinding page for Michael Hendrick. It is basically an
interactive compass with four exits:

- **Résumé** -> LinkedIn
- **Curriculum Vitae** -> cv.hendrick.net
- **Source Repo** -> this repo
- **Writing** -> mike.hendrick.net

The background is a real-time GPU fluid field using Pavel Dobryakov's
WebGL-Fluid-Simulation. Hover the name or one of the bearings and it kicks a
little ink into the field. The `INK` toggle turns that off when you want the page
to sit still.

## Hosting

This is a plain static site on GitHub Pages, served at `point.hendrick.net`.

- `index.html` - the page itself
- `support.js` - the small runtime it uses
- `CNAME` - tells GitHub Pages about `point.hendrick.net`

No build step, no package install, no ceremony. Edit `index.html`, push to
`main`, and GitHub Pages takes it from there.
