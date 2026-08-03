# Ars Fumi 0.2.1 — Science beta

This is a mobile-focused maintenance build of the Science module. Recipes, People, and Statistics remain styled previews so each module can still be developed and approved separately.

## What changed in 0.2.1

- Shortened equipment selectors on phones by removing the decorative separator option that wrapped across two rows.
- Replaced native HTML tobacco suggestions with a custom Ars Fumi autocomplete.
- Suggestions now appear in the page rather than in iPhone Safari's native keyboard accessory list.
- Added touch and keyboard controls for tobacco suggestions.

## Updating an existing GitHub Pages beta

Replace the files in the repository root with the contents of this folder and commit the update. Your existing data stays intact because the browser storage key has not changed.

An installed Home Screen PWA may briefly retain the old cached build. After GitHub Pages finishes deploying, open or refresh the Safari version once, then fully close and reopen the Home Screen app. A second refresh may be required while the new service worker activates.

## Quick desktop review

Open `index.html` in a modern browser. Core tracking and local storage work directly.

## Local PWA test

From this folder run:

```bash
python -m http.server 8080
```

Open `http://localhost:8080`.

## GitHub Pages deployment

Upload the complete contents of this folder to a GitHub repository. In the repository, open **Settings → Pages**, choose **Deploy from a branch**, select the branch containing these files and the `/ (root)` folder, then save.

On iPhone, open the GitHub Pages address in Safari and use **Share → Add to Home Screen**.

Data stays in the browser. Export JSON before clearing browser data.
