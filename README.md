# Lap Splitter PWA

A progressive web app for splitting race times across laps for 400m, 800m, and 1600m races.

## How to Install on Your Phone

### Option A: GitHub Pages (Recommended - Free)

1. **Create a GitHub account** (if you don't have one) at github.com
2. **Create a new repository** — name it something like `lap-splitter`
3. **Upload all files** from this zip (keep the folder structure):
   ```
   index.html
   manifest.json
   sw.js
   icons/
     icon-192.png
     icon-512.png
   ```
4. Go to **Settings → Pages** → set Source to "Deploy from a branch" → select `main` → Save
5. Wait ~1 minute, then visit: `https://YOUR_USERNAME.github.io/lap-splitter/`
6. On your phone, open that URL in Safari (iOS) or Chrome (Android)

### Option B: Netlify (Free, Drag & Drop)

1. Go to [app.netlify.com](https://app.netlify.com)
2. Sign up (free) and click "Add new site" → "Deploy manually"
3. **Drag and drop** the unzipped folder onto the upload area
4. Your site is live instantly at a `.netlify.app` URL
5. Visit that URL on your phone

### Adding to Your Home Screen

**iPhone (Safari):**
- Open the URL → tap the **Share** button (square with arrow) → **Add to Home Screen**

**Android (Chrome):**
- Open the URL → tap the **three dots** menu → **Add to Home screen** (or you may see an "Install" banner)

The app will launch in full-screen mode like a native app, and works offline after the first visit!

## Files Included

- `index.html` — The complete app (zero dependencies)
- `manifest.json` — PWA configuration (name, icons, theme)
- `sw.js` — Service worker for offline caching
- `icons/` — App icons for home screen
