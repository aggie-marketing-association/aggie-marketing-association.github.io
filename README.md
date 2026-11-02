# Aggie Marketing Association — Website

**Live site: <https://aggie-marketing-association.github.io/>**

Public site for the Aggie Marketing Association (AMA), a student-led organization
at UC Davis. Single-page static site: no build step, no external dependencies.

## Files

| File | Purpose |
|---|---|
| `index.html` | The entire website: inline CSS, JavaScript, and base64-embedded logo assets |
| `.nojekyll` | Tells GitHub Pages to serve files as-is instead of running Jekyll |

## Updating the site

1. Edit `index.html` (styles live in the `<style>` block, content in the markup).
2. Commit and push to `main`:
   ```bash
   git add -A
   git commit -m "Update content"
   git push
   ```
3. GitHub Pages redeploys automatically in about a minute.

## Notes

- This repository is named `<organization>.github.io`, so it is served at the
  organization root URL rather than under a `/repository/` path.
- The logo is embedded as base64 WebP inside `index.html`, so the page stays a
  single self-contained file and works offline.
- The site lists current officers' UC Davis email addresses publicly.
- The legacy address `https://hyusu-png.github.io/ama-website/` redirects here.