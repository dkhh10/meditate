# Meditate

A quiet stopwatch for Vedic meditation, built as a single-page PWA.

- Tap to start, tap to pause, reset to finish.
- Keeps the screen awake while running.
- Gentle bell at 30 minutes, then every 2 minutes until silenced.
- Sessions of 5 minutes or more are logged locally on reset. Tap the dots top-left to see today, the last 14 days, and the session list. Export as JSON or CSV.

All data stays in the browser's local storage. No accounts, no server.

## Files

- `index.html` – the whole app (markup, styles, script)
- `sw.js` – service worker for offline use
- `manifest.webmanifest`, `icon-*.png` – install to home screen
- `bell.m4a`, `wake.mp4` – bell sound and the tiny video used as a wake-lock fallback on iOS

## Deploy

Static site, deployed with `vercel --prod`.
