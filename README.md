# Spend Control

A private spending tracker that runs in your browser and installs on your phone like an app.

- Your entries are stored only on the device you use it on, in that browser's storage. Nothing is uploaded, and there is no server or account.
- Works offline once installed.
- Monthly limit, category budgets, recurring payments, bank statement import (CSV or Excel, including Greek bank formats and Revolut), trends and backups.

## Put it online with GitHub Pages

1. Create a new **public** repository, for example `spend-control`, and upload every file in this folder to it (Add file → Upload files). Include `.nojekyll`.
2. In the repository, open **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
3. After a minute or two the app is live at `https://<your-username>.github.io/spend-control/`.

The repository only contains the app's code. Anyone with the address can open the app, but they see their own empty copy: your entries never leave your device.

## Install it on your phone

- **iPhone (Safari):** open the address, tap Share, then **Add to Home Screen**.
- **Android (Chrome):** open the address and tap **Install** (or menu → Add to Home screen).

Always open it from that icon: each browser and each installed copy keeps its own entries.

## Keep your data safe

Phones can clear website storage, for example when space runs low. In the app, use **Data → Save a backup** every week or so and keep the file in Files, Drive or another cloud folder. **Restore from a backup** brings everything back, on any device.

Moving from another copy of the app (for example the one you used inside Claude): save a backup there, then restore it here.

## Updating

Replace `index.html` (and any other changed file) in the repository. The installed app picks up the new version the next time it opens online. Your entries are not affected by updates.
