# Pondo ng Bayan, Para sa Bayan

An 11-chapter student advocacy website presentation. This repository is separate from SAS2000.

## Files
- `index.html` — website entry point, using the separate assets below.
- `assets/styles.css` — responsive presentation styles and animations.
- `assets/presentation.js` — chapter navigation, menu, fullscreen, reading view, swipe handling, and print controls.
- `assets/images/` — all four supplied original photographs/graphics.
- `assets/favicon.svg` — website icon.
- `standalone.html` — complete original single-file version with embedded images, CSS, and JavaScript; works independently of the assets folder.
- `vercel.json` — static hosting configuration.
- `ASSETS.json` — image descriptions and checksums.
- `CONTENT-SOURCES.md` — content and image provenance notes.

## Open locally
Open `index.html` in a modern browser, or open `standalone.html` for the self-contained version. No npm, dependencies, or build step is needed.

## Save to GitHub
1. Extract the ZIP.
2. Open the extracted `pondo-ng-bayan` folder.
3. Upload its **contents**, including the complete `assets` folder, to the root of `Jamiraqui/pondo-ng-bayan`. Do not upload only the ZIP or nest the files inside another project folder.
4. Commit the changes. The website entry point remains `index.html`.

For a Git checkout, copy these files into the checkout, review `git diff`, then commit and push normally. The ZIP contains no `.git` history, credentials, or environment files.

## Deploy to Vercel
Use project `pondo-ng-bayan`, framework **Other**, no build command, and output directory `.`. The included `vercel.json` records the settings. Deploy the repository’s main branch.

## Presentation controls
Use the chapter menu, progress markers, previous/next buttons, left/right keys, Home/End, or horizontal swipes. Fullscreen depends on browser support. “Read all chapters” enables continuous reading. The About dialog offers print/PDF access. Motion can be paused and respects reduced-motion preferences.

## Content
See `CONTENT-SOURCES.md`. Campaign objectives and metrics are proposed indicators, not reported results.
