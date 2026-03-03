# JadaJaz Radio 🎵

A PWA boombox web app for JadaJaz DJ mixes.

## Deploy to GitHub Pages (5 steps)

1. **Create a new GitHub repo** at github.com → "New repository"
   - Name it: `jadajaz-radio` (or anything you want)
   - Set it to **Public**
   - Don't initialize with README

2. **Upload these 3 files** to the repo:
   - `index.html`
   - `manifest.json`
   - `sw.js`

   (Click "Add file" → "Upload files" in GitHub)

3. **Enable GitHub Pages**:
   - Go to repo **Settings** → **Pages**
   - Source: **Deploy from a branch**
   - Branch: `main` → `/ (root)`
   - Click **Save**

4. **Your site will be live** at:
   `https://YOUR-GITHUB-USERNAME.github.io/jadajaz-radio`

5. **On iPhone**: Open that URL in Safari → tap Share → Add to Home Screen ✅

## Files
- `index.html` — the boombox app
- `manifest.json` — PWA config (name, icon, theme)
- `sw.js` — service worker for offline/installable support
