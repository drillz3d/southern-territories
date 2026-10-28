# Southern Territories — website files (v0.6)

This release **keeps the original v0.1 website structure, typography, spacing and section order**, and replaces the image assets with better-proportioned imagery tailored to the exact slots.

## Fixed
- Hero: re-composed as a taller cinematic landscape to avoid extreme cropping of a wide panorama in a tall hero frame. No text is baked into the image.
- Map: reframed the parchment-style map as a properly proportioned 2022 x 660 asset, with a full-size version accessible by clicking it. It displays at its natural aspect ratio (no forced crop or stretching).
- Council chamber, bridge and infrastructure imagery: separate images are supplied for their purposes rather than reusing mismatched images. Updated crop and position behaviour.
- Houses: smaller banner illustrations fit the original small sigil slots.
- Image files are included locally, and the stylesheet URL has a new version to avoid stale browser cache.

## Update your existing GitHub Pages site
1. Extract this ZIP.
2. Open the **southern-territories** folder inside it.
3. In `github.com/drillz3d/southern-territories`, upload the **contents** of that folder (`index.html`, `styles.css`, `script.js`, `README.md`, and the `assets` folder) to the repository root and commit to `main`.
4. In GitHub's upload screen, use "Replace" if prompted. Check that the assets are committed under `/assets/`, not under an extra nested `southern-territories/` folder.
5. Refresh `https://drillz3d.github.io/southern-territories/` after GitHub Pages finishes deploying.

All house names, identities, geography, plans and dates on the site are illustrative proposals rather than confirmed project decisions. This site is static and requires no paid hosting or external image service.
