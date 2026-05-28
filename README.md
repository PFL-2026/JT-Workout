# T Dog Workout

A single-page interactive workout tracker — four routines (Hamstring, Quads, Pull, Push) as tappable tabs, dark neon theme, lightning-bolt icon, mobile-first. Tap an exercise to mark it done; progress saves automatically in your browser.

## Host on GitHub Pages

1. Create a new repository on GitHub (e.g. `tdog-workout`).
2. Upload **all the files in this folder** to the repo root — keep them at the top level, not inside a subfolder.
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment", set **Source = Deploy from a branch**, **Branch = main**, **Folder = / (root)**, then Save.
5. Wait ~1 minute. Your site will be live at `https://<your-username>.github.io/tdog-workout/`.

## Save as an app (iPhone)

1. Open the GitHub Pages URL in **Safari**.
2. Tap **Share → Add to Home Screen**.
3. It launches fullscreen with the bolt icon.

> If you previously added an old version, delete that home-screen icon first — iOS caches icons aggressively.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The app |
| `favicon.ico` | Classic browser-tab favicon (16/32/48) |
| `favicon.svg` | Vector favicon for modern browsers |
| `favicon-16.png`, `favicon-32.png`, `favicon-48.png` | PNG tab favicons |
| `apple-touch-icon.png` | iOS home-screen icon (180×180) |
| `icon-192.png`, `icon-512.png` | Android / PWA icons |
| `site.webmanifest` | Web app manifest |
