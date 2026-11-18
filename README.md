# Index 00 — Aryan

A standalone art and fashion showcase, ready for GitHub Pages. Includes all 40 works, the minimal glass interface, responsive image previews, search and image/list views. No installation, build step, API keys, or ChatGPT login required.

## Publish

1. Extract this ZIP.
2. Create a public GitHub repository.
3. Upload the extracted contents to the repository root. index.html must be at the root, beside app.js, style.css, works.json and assets/. Upload the entire assets folder. Do not upload just the ZIP. If the browser upload limits the number of files, upload assets in batches or use Git/GitHub Desktop.
4. In the repository, open Settings > Pages. Choose Deploy from a branch, select main and / (root), and save.
5. GitHub Pages displays your public URL once deployment finishes.

## Upload using Git (alternative)

Run in the extracted folder, replacing YOUR-REPOSITORY-URL with your new repository HTTPS URL:

```sh
git init
git add .
git commit -m "Publish Index 00 showcase"
git branch -M main
git remote add origin YOUR-REPOSITORY-URL
git push -u origin main
```

## Preview locally

Run `python -m http.server 8000` in this folder, then open http://localhost:8000. Use a web server: directly double-clicking index.html may prevent works.json from loading.

## Edit the gallery

Edit works.json to update titles, categories, metadata and image paths. Keep the thumb, thumbSmall, thumbMedium, full and width fields consistent with their image assets. Text and portfolio links are in index.html; visual styles are in style.css.

Portfolio: https://chaudharyaryan1503.wixsite.com/work

Artwork and clothing images are bundled locally. The optional original-file links still open their Google Drive files. The tool and portfolio links open external sites.

All artwork remains Aryan's. No licence for reuse of the artworks is granted by this package.
