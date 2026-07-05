# FirestormFMD Website

Static site for FirestormFMD, deployable via GitHub Pages.

## Tracked in this repo

- `index.html` — the live site. Fully self-contained: fonts load from the Google Fonts CDN, everything else (script, styles, the logo image) is bundled inline. This is the only file GitHub Pages needs to serve.
- `LICENSE.txt` — GPL-3.0 license.
- `assets/fmd-logo.png` — source logo asset, kept for reference/future edits.

## Ignored (see `.gitignore`)

- `FirestormFMD Site.dc.html`, `FirestormFMD Explorations.dc.html`, `support.js` — source files for editing the site in the design canvas tool. They require a runtime (`support.js`) to render and aren't standalone pages, so they're kept locally but not pushed.
- `.thumbnail` — internal preview image from the design tool.
- `screenshots/`, `uploads/` — draft/duplicate images not referenced anywhere in `index.html`.

## Deploying

Push to GitHub, then in the repo go to Settings → Pages → set source to the default branch, root folder. The site will be served at your repo's Pages URL, rendering `index.html`.
