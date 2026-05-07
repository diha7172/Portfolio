# Chicago Trip App 🌆

A Progressive Web App (PWA) for Dinuka's Chicago trip — May 23–25, 2025.

## What's inside

- Full 3-day itinerary with times, prices, and tips
- Tappable Google Maps links for every single stop
- All food spots (no chains — Gene & Jude's, The Purple Pig, Twin Anchors, Pequod's, Mr. Beef)
- Daily transit guide (Pace Bus 223 + CTA Blue Line)
- Hotel details and booking reminders
- Works offline once installed

---

## How to put this on your Android phone (3 steps)

### Step 1 — Upload to GitHub

1. Go to **github.com** and sign in (or create a free account)
2. Click the **+** button → **New repository**
3. Name it anything, e.g. `chicago-trip`
4. Make it **Public** (required for free GitHub Pages hosting)
5. Click **Create repository**
6. On the next screen, click **uploading an existing file**
7. Drag and drop **all 4 items** from this folder:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/` folder (with both icon PNG files inside)
8. Click **Commit changes**

### Step 2 — Enable GitHub Pages

1. In your repo, go to **Settings** (top menu)
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** branch, **/ (root)** folder
5. Click **Save**
6. Wait ~60 seconds, then your app is live at:
   `https://YOUR-USERNAME.github.io/chicago-trip/`

### Step 3 — Install on Android

1. Open **Chrome** on your Android phone
2. Navigate to your GitHub Pages URL above
3. Tap the **three dots menu** (⋮) in Chrome
4. Tap **"Add to Home Screen"** or **"Install app"**
5. Tap **Add** — it appears on your home screen like a real app
6. Open it once while on WiFi so it caches for offline use ✓

---

## The app works completely offline

Once you've opened it on WiFi, all content is cached. No data needed while walking around Chicago.

## Files

```
chicago-trip-app/
├── index.html      ← the entire app (all days, food, info)
├── manifest.json   ← tells Android it's installable
├── sw.js           ← service worker for offline caching
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md       ← this file
```
