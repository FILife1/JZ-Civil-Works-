# JZ Civil Works – Quotation & Invoice App

Installable web app (PWA) for creating quotations, invoices and client statements as PDF.

## Put it online with GitHub Pages
1. Create a new repository on GitHub (e.g. `jz-civil-works`), public.
2. Upload **all files** from this project to the repository root (index.html must be at the top level).
3. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. After a minute your app is live at `https://YOUR-USERNAME.github.io/jz-civil-works/`.

## Install on a phone
- **Android (Chrome):** open the link; an "Install" bar appears (and Chrome may show its own install prompt). Tap Install.
- **iPhone (Safari):** tap Share → Add to Home Screen.
- **Computer (Chrome/Edge):** click the install icon in the address bar.

## Notes
- Prices, history and settings are saved in the browser on each device. Use *History → Export backup* to move data between devices.
- The PDF library loads from cdnjs on first visit, then works offline.
- After editing files, change `V="jz-v1"` in `sw.js` (e.g. to `jz-v2`) so users receive the update.
