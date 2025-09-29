# smshed (static landing) — Loveable-ready

- Branch to pull: **loveable-ready**
- Entry file: `index.html`
- Assets: `./assets/*`
- Extra scripts: `./_flock.js`
- Paths are **relative** (./) so it works from any base path.

## What to verify after pull
1) `/` serves `index.html` (200)
2) `./assets/index-x-OvecDP.css` (200)
3) `./assets/index-*.js` (200)
4) `./_flock.js` (200)
5) Links to `./pricing.html` and `./checkout.html` load (if present)

No build step. **Do not install packages.** Serve as plain static files from repo root.
