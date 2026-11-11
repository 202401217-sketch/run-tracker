# 5K Run Tracker – installable web app

Files: `index.html`, `manifest.json`, `sw.js`, `icon.svg`

## Put it online (free, ~5 minutes) – GitHub Pages
1. On github.com, create a new **public** repo, e.g. `run-tracker`.
2. **Add file → Upload files** → drag in all 4 files → **Commit**.
3. Repo **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` / `(root)` → **Save**.
4. After about a minute your app is live at `https://<your-username>.github.io/run-tracker/`.

(Netlify Drop also works: open app.netlify.com/drop and drag the unzipped folder in.)

## Install on your phone
- **Android (Chrome):** open the link → ⋮ menu → **Add to Home screen / Install app**.
- **iPhone (Safari):** open the link → Share → **Add to Home Screen**.

It then opens full-screen like a normal app and works offline.

## Your data
- Runs are saved on that phone (in the browser's storage), not online.
- Tap **⬇ Backup** now and then to save a `.json` file; **⬆ Restore** loads it back
  (use this to move to a new phone, or if you clear browser data).

## Pay rule used
₹200 per km. Any single run of 5 km or more pays ₹500 per km for the whole run. Goal: ₹27,500.
