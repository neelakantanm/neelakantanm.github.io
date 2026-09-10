# Gautam Neelakantan Memana's academic homepage

A static migration of https://people.math.wisc.edu/~neelakantanm/ prepared on September 10, 2026. The intended GitHub Pages address is https://neelakantanm.github.io/.

The page keeps the original Georgia typeface, gray background, white page, blue accents, portrait, research summaries, and sections. The summaries use native keyboard-accessible disclosure controls. The layout adapts to narrow screens.

The portrait, CV, MS thesis, and Ergodic theory notes are included as local files copied from the public links on the original homepage. The paper, institution, project, and blog links retain their existing destinations. The blog continues to live in its separate `Blog` repository at https://neelakantanm.github.io/Blog/.

## Publish on GitHub Pages

1. Sign in as `neelakantanm`. Create a **public** repository named exactly `neelakantanm.github.io`, or open that repository if it already exists. If one already exists, review its contents before replacing files.
2. Upload the contents of this folder to the repository's `main` branch. Put `index.html`, `assets`, and `documents` directly at the repository root, rather than inside another folder. Include `.nojekyll` when uploading through Git. The plain HTML also works with GitHub's default Jekyll build when uploading visible files through the web interface.
3. In **Settings → Pages**, select **Deploy from a branch**, select **main** and **/(root)**, and save.
4. Wait for the Pages deployment to finish, then visit https://neelakantanm.github.io/. GitHub notes that publication can take up to 10 minutes.

GitHub's instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Edit the site

- Edit `index.html` to update the biography, research, teaching, office, email, and links.
- Edit `assets/style.css` to change appearance.
- Replace `assets/portrait.jpg` to change the photo.
- Replace the PDFs in `documents/` to update the downloadable documents. These are copies; later edits to the Google Drive originals will not update these files automatically.
- Mathematical text uses MathJax, loaded from jsDelivr. The collapsible summaries work without JavaScript.

The biography, July 1, 2026 start-date wording, office address, and current teaching statement were retained from the source page. No new affiliation or teaching status was inferred. Minor spelling, spacing, and HTML errors were corrected.

For a local preview, open `index.html` in a browser, or run `python3 -m http.server 8000` in this folder and visit http://localhost:8000/.

## Original university address

This package does not change the university server. Once the GitHub homepage is live, update the old homepage to point visitors to the new address if you still have access to it.

## Included files

```text
index.html
assets/style.css
assets/mathjax-config.js
assets/portrait.jpg
documents/cv.pdf
documents/ms-thesis.pdf
documents/ergodic-theory-notes.pdf
.nojekyll
README.md
```
