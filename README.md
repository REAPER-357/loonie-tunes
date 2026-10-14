# Loonie Tunes Music Player (Beta)

Loonie Tunes is a minimalist, privacy-focused Progressive Web App (PWA) designed for offline local audio playback. It uses native directory-scoped file access to eliminate automatic system storage scraping, ensuring unwanted audio files (such as call recordings, voice memos, and app media) stay out of your music library.

---

## Key Features

* **Directory-Scoped Access:** Select specific folders directly using the File System Access API. Bypasses broad storage indexers like Android's `MediaStore`.
* **Metadata Tab Organization:** Automatically parses ID3 tags to group and sort tracks by **Artist**, **Album**, **Track**, and **Genre**.
* **Playlist Management:**
* Create, edit, and delete custom playlists.
* Multi-select track addition with select-all and deselect-all actions.
* Export and import playlists via JSON for easy local backups.


* **Audio Gain Controls:** Integrated Web Audio API gain node for customizable volume boost.
* **Customization & Themes:** Toggle between dark and light modes with seamless preference saving.
* **Offline PWA:** Fully functional offline with a registered Service Worker (`sw.js`) and Web App Manifest (`manifest.json`).
* **Privacy First:** Zero telemetry, no analytics, no external tracking, and no ads.

---

## Project Structure

```text
├── index.html        # Main app interface and client logic
├── manifest.json     # PWA configuration manifest
├── sw.js             # Service Worker for offline asset caching
├── small-icon.png    # App launcher icon (192x192)
└── icon.png          # App launcher icon (512x512)

```

---

## Quick Start

1. **Host or Load Locally:** Serve the repository root directory using any web server or local HTTPS host (e.g., via GitHub Pages or a local dev server).
2. **Install as PWA:** Open the URL in a modern browser (such as Chrome, Brave, or hardened Firefox/LibreWolf) and select **Add to Home Screen** or **Install App**.
3. **Select Folder:** Tap **Select Music Folder** to grant read access to your local `/Music` directory.

---

## Why Loonie Tunes?

Like all my apps, I make it to meet needs that are not met on any app that I've tried, so I make my own to meet those needs. Feel free to modify the code for your needs, or enjoy this app. All the best.

— **REAPER-357**
