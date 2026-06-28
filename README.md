# Flica Monitor — GitHub Pages Setup

## Setup Instructions

1. Create a free GitHub account at github.com
2. Create a new repository called `flica-monitor`
3. Upload all files from this folder to the repository
4. Go to Settings → Pages → Source → Deploy from branch → main
5. Your alert page will be live at: `https://YOUR_USERNAME.github.io/flica-monitor`
6. Open that URL on your iPhone in Safari
7. Tap Share → Add to Home Screen
8. Open the app → tap Enable Push Notifications
9. Enter your GitHub Pages URL in the extension Settings tab

## How it works

The Chrome extension on your Surface updates `alerts.json` in your
GitHub repository whenever a trip is found. Your iPhone page polls
that file every 10 seconds and shows a push notification.

## Files

- `index.html` — iPhone web app
- `alerts.json` — updated by the extension with new trips
- `manifest.json` — makes it installable as a PWA
- `icon.png` — app icon
