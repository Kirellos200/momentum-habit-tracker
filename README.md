# Momentum Habit Tracker — PWA

Momentum is a responsive, installable Progressive Web App (PWA).

## Run on desktop
Open `index.html` in a modern browser.

## Install on iPhone/iPad
1. Host this folder on an HTTPS site (GitHub Pages, Netlify, Vercel, etc.).
2. Open the site in Safari.
3. Tap **Share** → **Add to Home Screen**.
4. Open Momentum from the new home-screen icon.

## Install on Android
1. Host this folder on an HTTPS site.
2. Open it in Chrome.
3. Use the browser menu → **Install app** / **Add to Home screen**.

## Important
A PWA service worker generally requires a web origin such as HTTPS or localhost. Opening the HTML directly as a `file://` URL is useful for testing the tracker, but it will not provide the full install/offline PWA behavior.

Your habit data is stored locally in the browser using LocalStorage. Export JSON from Settings to back it up.
