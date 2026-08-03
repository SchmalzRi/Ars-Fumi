# Put Ars Fumi on GitHub Pages

1. Create a new GitHub repository, for example `ars-fumi`.
2. Extract the beta ZIP.
3. Upload **the contents inside the folder**, including `index.html`, `manifest.webmanifest`, `sw.js`, and the `assets` folder.
4. Commit the files to the repository's main branch.
5. Open the repository's **Settings**.
6. Select **Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Select `main` and `/ (root)`, then save.
9. Open the HTTPS address GitHub provides after deployment completes.

For iPhone testing, open that address in Safari and choose **Share → Add to Home Screen**.

When replacing a beta build, upload the new files over the old ones. The service worker uses a new cache version, but Safari may briefly retain the previous build; closing the installed app and reopening it usually completes the update.
