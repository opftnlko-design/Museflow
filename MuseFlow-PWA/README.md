# MuseFlow PWA

Beautiful music player with offline support.

## Features
- Works as a Progressive Web App (installable on Android / iOS / Desktop)
- Offline listening for songs you played while online (Audius & Jamendo)
- YouTube songs play while online (video is hidden, only audio is used when possible)
- Playlists, Liked songs, Sleep timer, Smart recommendations

## How to install on phone (Android)

1. Open the `index.html` (or host the whole folder on any web server / GitHub Pages / Netlify)
2. On Chrome → menu → **Install app** or **Add to Home screen**
3. The app will appear like a normal app with the MuseFlow icon

### Important about Offline + YouTube
- Songs from **Audius** and **Jamendo** are automatically saved when you play them (if "Save songs for offline" is enabled in Settings).
- **YouTube songs cannot be saved offline** (YouTube does not allow downloading). When you go offline, only previously played non-YouTube songs will work.

## Folder structure
```
MuseFlow-PWA/
├── index.html          ← Main app
├── manifest.json       ← PWA manifest
├── sw.js               ← Service Worker (offline app shell)
├── icons/              ← All app icons + favicon
│   ├── logo.svg
│   ├── icon-*.png
│   └── apple-touch-icon.png
└── README.md
```

## For best experience on low-end phones
- Go to Settings → turn **Artwork** OFF
- Turn **Animations** OFF
- Set Music source to **Audius** or **Jamendo** (YouTube is heavier)

Made with ♥
