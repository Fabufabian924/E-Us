# EURUSD Bias Tracker

Track monthly, weekly and daily EURUSD bias. Score 5 factors per timeframe; bias shows only when at least 3 of 5 agree. Notes and log are saved in your browser.

## Files
- `index.html` the whole app
- `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png` make it installable and usable offline

## Host on GitHub Pages
1. Upload all files in this folder to a new repo (keep them at the top level)
2. Settings → Pages → Deploy from a branch → `main` / root → Save
3. Open `https://<your-username>.github.io/<repo-name>/`

## Install on your phone
- **Android (Chrome):** an "Install app" button appears at the top, or use menu → Install app / Add to Home screen
- **iPhone (Safari):** Share → Add to Home Screen

## Live data note
The "Fetch data" button uses Claude connectors that only exist inside claude.ai. On GitHub it shows a message and everything else works. To get live prices there, replace `fetchData()` with calls to a market data API and keep API keys private.
