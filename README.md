# Restaurant Invoice Generator — PWA

Quick instructions to run and test the Progressive Web App locally.

Prerequisites
- A modern browser (Chrome, Edge, Firefox).
- Python 3 or Node.js (for a static server).

Run a local server (recommended) from the project folder:

Using Python 3:
```bash
python -m http.server 8000
```

Using Node (http-server):
```bash
npx http-server -p 8000
```

Or run the included PowerShell helper on Windows:
```powershell
./run-server.ps1
```

Open the app:

Open http://localhost:8000/ in your browser. In DevTools -> Application you can inspect the `Manifest` and `Service Worker` and try "Install" or "Add to home screen".

Files added for PWA support:
- `manifest.json` — web app manifest
- `sw.js` — service worker (caching strategy)
- `icon-192.svg`, `icon-512.svg` — app icons
- `run-server.ps1` — Windows PowerShell helper to start a simple server

If you'd like, I can also add an automated build or a more robust SW (workbox) setup.
