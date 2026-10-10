TRAILBLAZER OS 0.1 — INSTALLATION

1. Unzip this package on a computer.
2. Create a PUBLIC GitHub repository named trailblazer-os (or use an existing GitHub Pages repository).
3. Upload all five files (index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png) to the repository ROOT. Do not upload the enclosing folder alone.
4. In repository Settings > Pages, select Deploy from a branch, main, /(root), Save.
5. Wait for GitHub Pages to publish. Open the Pages URL shown in Settings > Pages, usually https://YOUR-USERNAME.github.io/trailblazer-os/ .
6. On your iPhone 16 Pro Max, open that URL in SAFARI. Tap Share > Add to Home Screen (or Open as Web App if shown) > Add.
7. Launch TrailBlazer from its new Home Screen icon. The interface opens in standalone mode.

NOTES:
- iOS remains the actual operating system. This is a PWA dashboard.
- You need HTTPS for service worker offline caching; GitHub Pages provides HTTPS.
- Visit the site once while online before expecting offline access. External shortcuts still need internet.
- Project list, theme, and quick notes are stored locally in browser storage; no cross-device sync or backup yet.
- This build does NOT directly control Bambu printers, run an offline AI, or open iOS Camera programmatically.
- If you update the app, refresh the site online; cache refresh may require reopening it.
