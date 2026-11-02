# Aggie Marketing Association — Website

Public site for the Aggie Marketing Association (AMA), a student-led organization
at UC Davis. Single-page static site, no build step, no external dependencies.

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

- The logo is embedded as base64 WebP inside `index.html`, so the page stays a
  single self-contained file and works offline.
- The site lists current officers' UC Davis email addresses publicly. Replace
  them with an organizational inbox if that becomes a problem.
- If the repository name changes, the Pages URL changes with it
  (`https://<user>.github.io/<repo>/`).
