# Saku

A personal money tracker in rupiah that installs on your iPhone from Safari. No App Store, no Mac.

- Wallets, income, expenses and transfers
- Quick text entry: `kopi 20k dan parkir 5k`
- Categories with monthly budgets, savings goals
- Insights: health score, month comparison, recording streak
- CSV import, backup and restore
- Works offline. Your data stays on your phone; nothing is sent anywhere.

## Put it online (free, with GitHub Pages)

1. In this repository: Settings > Pages.
2. Under "Build and deployment", choose Source: "Deploy from a branch".
3. Branch: `main`, folder: `/ (root)`. Save.
4. After a minute the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Install on iPhone

1. Open the site address in Safari.
2. Tap the Share button, then "Add to Home Screen".
3. Open Saku from the new icon. It runs full screen, like an app.

Data is kept per browser. Always use the home-screen icon, and tap "Save backup" on the Home screen now and then.

## Files

| File | Job |
| --- | --- |
| `index.html` | The whole app: layout, styles and logic |
| `manifest.webmanifest` | Tells the phone the app's name, colours and icon |
| `sw.js` | Lets the app open without internet. Change `VERSION` in it whenever you change the app |
| `icons/` | Home-screen icons |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |
