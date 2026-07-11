# iTinyJava — privacy policies

Static site hosting per-game privacy policies for iTinyJava games, served via
GitHub Pages from **https://itinyjava.github.io/**.

## URLs
- Stuck Arrows: `https://itinyjava.github.io/stuck-arrows/privacy/`

The site root (`/`) intentionally has no landing page — link stores directly to
each game's policy path.

## Add a new game's policy
1. Create `<game-slug>/privacy/index.html` (copy `stuck-arrows/privacy/index.html` and edit the content).
2. Set the contact to `itinyjava+<game-slug>@gmail.com` (Gmail plus-addressing; routes to the shared inbox, non-personal).
3. Commit and push — Pages redeploys automatically in ~1 minute.

## Notes
- Pure static HTML (no build step, no Jekyll) — reviewer- and crawler-friendly.
- `.nojekyll` disables Jekyll so every folder is served verbatim.
