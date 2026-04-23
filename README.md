# profes Investor Wallet Dashboard

GitHub Pages ready PWA files for the profes dashboard.

## Files to upload

- `index.html`
- `config.js`
- `manifest.webmanifest`
- `sw.js`
- `offline.html`
- Logo is loaded from `https://p1.ikotech.in/logo.png`

## Setup

1. Deploy the Google Apps Script backend as a Web App.
2. Copy the Web App URL ending with `/exec`.
3. Open `config.js`.
4. Replace `PASTE_YOUR_GOOGLE_APPS_SCRIPT_WEB_APP_URL_HERE` with your Web App URL.
5. Upload this folder to GitHub.
6. In GitHub, go to `Settings > Pages` and publish from the branch root.

Important: deploy the Apps Script Web App with access set to `Anyone`, otherwise GitHub Pages cannot call the backend.

## Role links

- Admin: `?role=admin`
- Investor: `?role=investor`
- Employee: `?role=employee`
