# iTinyJava — studio site & privacy policies

Static site for the iTinyJava game studio, served via GitHub Pages from
**https://itinyjava.github.io/**. The root landing page (`index.html`)
represents iTinyJava as a game developer (used for Play Console business
verification); per-game privacy policies live in subfolders.

## URLs
- Studio landing page: `https://itinyjava.github.io/`
- Stuck Arrows: `https://itinyjava.github.io/stuck-arrows/privacy/`

## Add a new game's policy
1. Create `<game-slug>/privacy/index.html` (copy `stuck-arrows/privacy/index.html` and edit the content).
2. Set the contact to `itinyjava+<game-slug>@gmail.com` (Gmail plus-addressing; routes to the shared inbox, non-personal).
3. Commit and push — Pages redeploys automatically in ~1 minute.

## Notes
- Pure static HTML (no build step, no Jekyll) — reviewer- and crawler-friendly.
- `.nojekyll` disables Jekyll so every folder is served verbatim.
