# Deploying Ars Fumi 0.6.4 to GitHub Pages

This package is deliberately deployment-flat: `index.html`, `sw.js`, `manifest.webmanifest`, and the `assets` folder belong directly in the repository root used by GitHub Pages.

1. Export a JSON backup from the currently installed Ars Fumi build.
2. Extract this ZIP.
3. Upload **all files and the `assets` folder inside the extracted folder** to the GitHub Pages publishing root.
4. Confirm that GitHub shows `index.html` directly at repository root, not inside another `ars_fumi_0_6_4` folder.
5. Commit the changes and check the repository's Pages/Actions status.
6. Open the Pages URL in a normal browser tab and hard-refresh once.
7. Fully close and reopen the Home Screen app.
8. Confirm **Ars Fumi 0.6.4** is shown in the app.

The application code and storage schema are unchanged. The `.nojekyll` file only tells GitHub Pages to publish the static files exactly as supplied.
