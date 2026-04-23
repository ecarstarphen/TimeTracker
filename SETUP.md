# Time Tracker — Install on Your Samsung

## What's in this folder
- `index.html` — the app
- `manifest.json` — tells Chrome it's installable
- `sw.js` — makes it work offline
- `icon-192.png` / `icon-512.png` — app icons

---

## Step 1 — Put it on GitHub Pages (free hosting)

1. Go to **github.com** and sign in (or create a free account)
2. Click the **+** button → **New repository**
3. Name it: `time-tracker` (or anything you like)
4. Set it to **Public**
5. Click **Create repository**
6. Click **uploading an existing file**
7. Drag ALL 5 files from this folder into the upload area
8. Click **Commit changes**
9. Go to **Settings** → **Pages** (left sidebar)
10. Under "Branch", select **main** → click **Save**
11. Wait ~60 seconds, then your app is live at:
    `https://YOUR-USERNAME.github.io/time-tracker`

---

## Step 2 — Install on your Samsung

1. Open **Chrome** on your Samsung
2. Go to your GitHub Pages URL above
3. Tap the **three-dot menu** (⋮) in the top right
4. Tap **"Add to Home screen"**
5. Tap **"Install"** or **"Add"**
6. Done! It now appears on your home screen like a real app.

---

## Features
- Clock In / Clock Out with live elapsed timer
- Call In logging
- Weekly summary (hours, days worked, call-ins)
- All entries log with tabs for This Week / All
- Persistent storage — survives closing the app
- Works offline after first load
- Export to CSV (opens in Google Sheets or Excel)

---

## Coming next (when you're ready)
- Notes on entries
- Edit / delete entries
- Option B: convert to a real APK with PWABuilder
