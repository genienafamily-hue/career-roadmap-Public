# Market Strategy & Income Roadmap

A single static web page (no build step) for planning how to earn: four career paths, income streams with a gap-to-baseline view, and an AND/OR action roadmap. Everything is editable and saved in the browser (local storage).

## Run locally
```
npm start
```
Serves the folder at http://localhost:8080 (needs Python 3). You can also open `index.html` directly.

## Files
- `index.html`: the app
- `manifest.webmanifest`, `icons/`: home-screen name and icons

## Notes
- The "Ask the coach" feature only works when the page runs inside Claude (claude.ai). Elsewhere the rest of the app works and the coach shows that it is unavailable.
- Data stays in your own browser; nothing is sent anywhere by this page.
- Planning material only, not legal, tax or immigration advice.
