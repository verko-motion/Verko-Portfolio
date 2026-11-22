# Verko — Portfolio

Static site, no build step. Files: `index.html`, 8 preview videos (`clip1.mp4` ... `clip8.mp4`), `.nojekyll`. Everything sits in one folder on purpose, so it uploads from a phone without folders.

## Put it online with GitHub Pages
1. On github.com, create a new public repository (e.g. `verko-portfolio`).
2. Tap **Add file > Upload files**, select all the files (index.html and all 8 clips), then **Commit changes**. (On a phone, use your browser's "Desktop site" mode if the upload button is hidden.)
3. Open **Settings > Pages**. Under **Build and deployment** choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After about a minute the site is live at `https://YOUR-USERNAME.github.io/verko-portfolio/`.

Custom domain (like verko.com): **Settings > Pages > Custom domain**.

## Editing
Titles, links and captions are plain text in `index.html`. To add a clip, upload a short MP4 and copy one of the `<div class="vc ...">` cards.
