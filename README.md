# Collect Team Reeves

Pokémon TCG collection tracker with set completion, 3×3 card scanning (experimental OCR), favorite-card showcase, and a Top Value Cards panel using **manually assigned values**. This is not a live pricing feed.

## Publish with GitHub Pages

1. Sign in to GitHub and create a **public** repository named `collect-team-reeves`.
2. Choose **Add file → Upload files** and upload `index.html` and `.nojekyll` into the repository root. Commit the files.
3. Visit **Settings → Pages → Build and deployment**, select **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
4. Your site URL will be `https://YOUR-USERNAME.github.io/collect-team-reeves/` once deployment succeeds.

## Important limitations

- This static site stores cards, favorites, and price estimates only in each browser's localStorage. Visitors **do not** see one shared Team Reeves collection, and clearing browser storage may erase data. Export a JSON backup and keep it somewhere safe.
- 'Top Value Cards' sorts by manually entered USD amounts, **not** real-time market prices. Card IDs must be owned first; a live feed would require a separate pricing integration.
- The nine-card scanner is experimental text recognition and needs manual confirmation, particularly for mixed-set photographs.
- Catalog images/data come from TCGdex, and photo OCR loads Tesseract.js from a CDN. An internet connection is required.
