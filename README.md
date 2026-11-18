# Shardbeat

Dodge the shapes. Ride the beat. A phone-first rhythm-dodging game that runs in the browser.
The music is synthesized live, so there are no audio files and nothing to download.

- **Story:** 5 chapters (First Light, Falling Notes, The Loop, Static Choir, Downbeat), each with its own tempo, song and obstacle set
- **Challenges:** Glass Heart (one heart), Double Time (fast), Gauntlet (everything, two hearts). Unlocked by clearing story chapters
- **Controls:** drag anywhere to steer. Arrow keys or WASD on a keyboard. P to pause
- Progress, stars and settings save on the device

## Put it on GitHub Pages

1. Create a new public repository on github.com (for example `shardbeat`).
2. Click **Add file > Upload files** and drag in everything in this folder:
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`.
   Commit the upload.
3. Go to **Settings > Pages**. Under **Build and deployment**, set Source to
   **Deploy from a branch**, pick the `main` branch and the `/ (root)` folder, then Save.
4. After a minute your game is at `https://YOUR-USERNAME.github.io/shardbeat/`.

## Play it like an app on your phone

Open that link in Chrome (Android) or Safari (iPhone).
- Android: menu (three dots) > **Add to Home screen** or **Install app**
- iPhone: Share button > **Add to Home Screen**

It then opens fullscreen and works offline after the first visit.
