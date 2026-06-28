# Blackjack Basic Strategy Drill PWA

This folder is ready to upload to GitHub Pages, Netlify, Cloudflare Pages, or any static HTTPS host.

Files:
- index.html: the app
- manifest.webmanifest: installable app metadata
- sw.js: service worker for offline caching
- icons/: app icons

Basic hosting:
1. Upload the whole folder contents, keeping index.html at the root.
2. Open the HTTPS site URL on your phone.
3. Android Chrome/Edge: use Install app or Add to Home screen.
4. iPhone Safari: Share -> Add to Home Screen -> Open as Web App -> Add.

The app stores drill stats and misses in localStorage on each device. There is no backend or shared account data.
