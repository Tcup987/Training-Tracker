# Training Log (PWA)

Static app; data is stored on the device (browser storage). Works offline once installed.

## Deploy on GitHub Pages
1. Create a repo and upload every file in this folder to the repo root.
2. Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Open https://YOUR-USERNAME.github.io/REPO-NAME/ in Chrome on Android, then menu > Install app.

## Import existing data
Add ExportForPwa.gs to the Apps Script project, run `exportForPwa`, download training-export.json from Drive,
then Program > Import file in the app. Use Program > Export backup regularly.
