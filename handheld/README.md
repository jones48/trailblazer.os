# TrailBlazer OS — Handheld X1 v0.1

This is a touch-first UI prototype, **not** a bootable OS image.

## Test on HP Windows laptop
1. Extract the ZIP.
2. Open `index.html` in Chrome or Edge. No installs or server required for basic UI.
3. Test six tiles. Camera/Media/Files use the browser file picker. Sharing depends on browser support.

## Publish to GitHub Pages
1. Create a `handheld-v01` folder in your GitHub Pages repository.
2. Upload `index.html` and `manifest.webmanifest` into it.
3. Visit `https://YOURNAME.github.io/YOURREPO/handheld-v01/` (adjust for your Pages URL).
4. On iPhone, use Safari > Share > Add to Home Screen. Do not use Guided Access until testing camera and sharing.

## Next Linux milestone
Run the same UI in Chromium kiosk mode on Raspberry Pi OS. Add a Python local API only after the interface is validated; bind to localhost, and do not expose unrestricted system commands.

## Known limitations
- No native OS replacement, automatic boot or device lock in this package.
- Camera capture is browser-dependent.
- File selections are not saved or uploaded.
- Bill AI and printer status are placeholders.
- Requires HTTPS for best iPhone PWA behavior.
