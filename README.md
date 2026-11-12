# Spend Control

A private spending tracker that runs in your browser and installs on your phone like an app.

- Your entries are stored only on the device you use it on. Nothing is uploaded, and there is no server or account.
- Works offline once installed.
- Monthly limit, category budgets, recurring payments, trends, and bank statement import (CSV or Excel, including Greek bank layouts and Revolut).
- Guards against counting money twice: statement rows are matched to entries you typed and to recurring payments, and transfers between your own accounts are paired for you to confirm.
- Phone and computer can be combined by merging backups.

## Put it online with GitHub Pages

1. Create a new **public** repository, for example `spend-control`, and upload every file in this folder to it (Add file → Upload files). Include `.nojekyll`.
2. In the repository, open **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
3. After a minute or two the app is live at `https://<your-username>.github.io/spend-control/`.

The repository only contains the app's code. Anyone with the address can open the app, but they get their own empty copy: your entries never leave your device.

Good to know: every GitHub Pages site under the same username shares one browser storage area. Your other Pages sites could, in principle, read this app's data in your browser, and clearing site data for one clears it for all. If that matters to you, host the app under a separate GitHub account or a custom domain.

## Install it on your phone

- **Android (Chrome):** open the address and tap **Install** in the banner (or menu → Add to Home screen → Install). Long-press the icon for an **Add an entry** shortcut.
- **iPhone (Safari):** open the address, tap Share, then **Add to Home Screen**.

Always open it from that icon. Each browser, and the installed app, keeps its own entries.

## Keep your data safe

Phones can clear website storage, for example when space runs low or when browser data is cleared. In the app, use **Data → Save a backup** every week or so and keep the file in a cloud folder. **Bring in a backup** restores it on any device.

The app also keeps two copies of your data on the device and a snapshot for each of the last 14 days you made changes (**Data → Earlier versions**). Those protect against mistakes, not against the browser's storage being cleared. Only backup files do that.

## Phone and computer together

Each device keeps its own entries. To combine them:

1. On one device: **Data → Save a backup**, and send the file to the other device.
2. On the other: **Data → Bring in a backup → Merge**.

Merging keeps what is on the device and adds what is new in the backup. Edits made later win, and entries you deleted stay deleted. Do it in both directions to bring both devices fully up to date.

## Updating

Replace `index.html` (and any other changed file) in the repository. The installed app picks up the new version the next time it opens online. Your entries are not affected by updates.
