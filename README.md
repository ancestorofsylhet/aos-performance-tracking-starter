# AOS Performance Tracking — Starter Demo

## Files
- `index.html`: website layout
- `style.css`: responsive dark green/gold design
- `script.js`: sample data, player rankings, result submissions, demo admin review

## Run locally
Open `index.html` in a browser, or open this folder in VS Code.

## Publish with GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html`, `style.css`, `script.js`, and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.

## Important limitation
This is a front-end prototype. It uses `localStorage`, so records are stored only in the current browser and are NOT shared between players' devices. The demo PIN `2468` is visible in the JavaScript source and is not secure. Do not use this for a real public admin system.

For real club use, connect Supabase (or another backend), store players/matches/submissions in a shared database, enable Row Level Security, and enforce admin-only approval on the server/database. Never put a service-role secret in frontend JavaScript.

The player names and scores included are sample data. Replace them with verified AOS records.
