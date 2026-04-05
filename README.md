# 音凪 — OTONAGI

集中と静寂のポモドーロタイマー。BGM付きで作業に没頭できるWebアプリ。

## Features

- Pomodoro timer (25min work / 5min short break / 15min long break)
- MP3 music player (up to 7 tracks, stored in IndexedDB)
- Built-in ambient sounds (Lo-Fi, Rain, Ambient, Cafe, Forest)
- Background image customization (up to 4 images with crossfade)
- Play modes: Select / Sequential / Random
- NHK-style notification chime
- PWA: installable, works offline
- No server required — runs entirely in your browser

## Usage

Open `index.html` in a browser, or visit the GitHub Pages URL.

### Add Music
1. Open the BGM section
2. Tap the drop zone to select MP3 files
3. Tracks are saved locally (IndexedDB) and persist across sessions

### Add Background Images
1. Tap the image button (top-right of timer panel)
2. Select up to 4 images — they crossfade on track/session changes

## Tech Stack

Single HTML file. No build tools, no frameworks, no dependencies.

- Web Audio API (procedural built-in sounds)
- IndexedDB (large binary storage for MP3/images)
- CSS Glassmorphism + backdrop-filter
- PWA (Service Worker + Web App Manifest)
- Google Fonts: Yuji Boku, Cormorant Garamond, Noto Sans JP

## License

MIT
