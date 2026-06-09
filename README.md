# 🌿 40-Day Detox Tracker

A minimalist Progressive Web App (PWA) to track your Healer Labs 40-day detox protocol — installable on your phone, works offline.

## Features

- ✅ Day-by-day protocol checklist (all 4 phases + colon cleanse nights)
- 📅 Visual 40-day calendar with progress tracking
- 💬 Daily rotating inspirational quote
- 📱 Installable on iPhone & Android as a home screen app
- 🔒 All data stored locally on your device (no account needed)
- ✈️ Works offline after first load

## Deploy to GitHub Pages (5 minutes)

### Step 1 — Create a new repository

1. Go to [github.com](https://github.com) → **New repository**
2. Name it `detox-tracker` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 2 — Upload files

Drag and drop these files into the repository:
- `index.html`
- `manifest.json`
- `sw.js`
- `icons/` folder (with `icon-192.png` and `icon-512.png`)

Or use GitHub Desktop / git CLI:
```bash
git init
git add .
git commit -m "Initial detox tracker"
git remote add origin https://github.com/YOUR_USERNAME/detox-tracker.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages**
2. Under "Source", select **Deploy from a branch**
3. Choose **main** branch, **/ (root)** folder
4. Click **Save**

Your app will be live at:
`https://YOUR_USERNAME.github.io/detox-tracker/`

(Takes ~1 minute to deploy)

### Step 4 — Install on your phone

**iPhone (Safari):**
1. Open the URL in Safari
2. Tap the **Share** button (box with arrow)
3. Tap **Add to Home Screen**
4. Tap **Add**

**Android (Chrome):**
1. Open the URL in Chrome
2. Tap the **⋮ menu** → **Add to Home screen**
3. Tap **Install**

---

## Protocol Summary

| Phase | Days | What |
|-------|------|------|
| 🧩 Heavy Metals Detox | 1–20 | 2 capsules with main meal |
| 🪱 Parasite Cleanse | 21–40 | Before meals (escalating dose) |
| 🧲 Toxin Binder | 21–40 | 1–2 capsules away from food |
| 🌙 Colon Cleanse | 15 nights | 1 capsule at night |
| 💤 Rest Days | 31–34 | No Parasite Cleanse or Toxin Binder |

Colon Cleanse nights: Days 5, 8, 11, 14, 17, 20, 23, 26, 29, 32, 34, 36, 37, 39, 40
