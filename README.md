# Ars Fumi 0.2 — Science beta

The second review build still focuses on the Science module. Recipes, People, and Statistics remain styled previews so each module can be developed and approved separately.

## What changed in 0.2

- Reworked Light Mode around muted blue-grey surfaces rather than dominant white.
- Strengthened the green identity of the People preview.
- Added full equipment catalogue management in Settings.
- Equipment can be added, renamed, reclassified, and removed.
- Adding equipment from Science selects it immediately; adding from Settings only stores it.
- Removing active equipment safely falls back to another installed item.
- Past session snapshots remain available after catalogue removal.

## Quick desktop review

Open `index.html` in a modern browser. Core tracking and local storage work directly.

## Local PWA test

From this folder run:

```bash
python -m http.server 8080
```

Open `http://localhost:8080`.

## GitHub Pages deployment

Upload the complete contents of this folder to a GitHub repository. In the repository, open **Settings → Pages**, choose **Deploy from a branch**, select the branch containing these files and the `/ (root)` folder, then save. GitHub will provide the HTTPS address needed for service-worker and iPhone Home Screen testing.

On iPhone, open that address in Safari and use **Share → Add to Home Screen**.

## Review priorities

1. Light Mode comfort and contrast.
2. Mobile slider comfort and field density.
3. Equipment editing/removal from Settings.
4. Normal mode speed and clutter.
5. Senku Mode depth and progressive disclosure.
6. Single/Mix workflow and side-by-side percentage entry.
7. Save states: Session, Experiment, Candidate, Recipe.

Data stays in the browser. Export JSON before clearing browser data.
