# tickflow-timer
# ⏱ TickFlow — Precision Timer App

A beautiful, floating stopwatch and countdown timer you can deploy to Netlify in minutes.

## ✨ Features

- **Stopwatch** with millisecond precision
- **Countdown Timer** — set hours, minutes, seconds
- **Floating Popup** — draggable, resizable timer overlay on your screen
- **Lap tracking** — with fastest 🏆 and slowest 🐢 lap highlights
- **Customizable popup** — transparency, size (small/medium/large), accent colors, background
- **Sound alert** when countdown ends
- **Keyboard shortcuts**: `SPACE` start/pause · `R` reset · `L` lap · `P` popup

---

## 🚀 Deploy to Netlify (Step-by-Step)

### Step 1 — Push to GitHub

1. Go to [github.com](https://github.com) and sign in
2. Click **"New repository"** (green button, top right)
3. Name it: `tickflow-timer` (or anything you like)
4. Set it to **Public**, leave everything else default
5. Click **"Create repository"**
6. On the next page, click **"uploading an existing file"**
7. Drag and drop the `index.html` file from this folder
8. Click **"Commit changes"**

### Step 2 — Deploy on Netlify

1. Go to [netlify.com](https://netlify.com) and sign in (or sign up free)
2. Click **"Add new site"** → **"Import an existing project"**
3. Choose **"Deploy with GitHub"**
4. Authorize Netlify to access your GitHub
5. Select your `tickflow-timer` repository
6. Leave all build settings **blank/default** (no build command needed)
7. Click **"Deploy site"**

✅ Done! Netlify gives you a live URL like `https://tickflow-abc123.netlify.app`

### Optional: Custom Domain
In Netlify → Site settings → Domain management → Add custom domain

---

## 📌 How to Use the Floating Popup

1. Click the **📌 pin icon** (top right of the app) — or press **P** on keyboard
2. A floating timer appears — **drag it anywhere** on your screen
3. Drag the **⤡ corner handle** to resize it
4. Click **⚙️ settings** to customize:
   - Transparency (20% to 100%)
   - Size: Small / Medium / Large
   - Accent color (6 choices)
   - Background color (5 choices)

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `SPACE` | Start / Pause |
| `R` | Reset |
| `L` | Record Lap (stopwatch mode) |
| `P` | Toggle floating popup |

---

## 📁 File Structure

```
tickflow-timer/
└── index.html     ← Entire app in one file
└── README.md      ← This file
```

No dependencies. No npm. No build step. Just one HTML file.
