# Rune Crystal Defense

A landscape tower-defense game: heroes fight automatically around a crystal. Installable as a PWA.

## Files
- `index.html` - the whole game
- `manifest.json`, `sw.js`, `icons/` - PWA files
- `.nojekyll` - tells GitHub Pages to serve files as-is

## Publish on GitHub Pages
1. Create a repo and upload everything in this folder to the root of the `main` branch.
2. Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Your URL will be `https://<user>.github.io/<repo>/` (HTTPS is required for PWABuilder).

## Package with PWABuilder
1. Open pwabuilder.com and paste your GitHub Pages URL.
2. Check the report: manifest, service worker and icons should all pass.
3. Choose Package for Stores (Android / Windows / iOS) and download.

Note: the Silkscreen font loads from Google Fonts; offline it falls back to a monospace font.
