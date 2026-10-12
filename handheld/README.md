# TrailBlazer OS 0.4 — Bill Chat Edition

## Install to existing GitHub Pages site

In `jones48/trailblazer.os`, open the `handheld/` directory and upload these three files: `index.html`, `sw.js`, and `manifest.webmanifest`. Replace the existing files of the same names **inside handheld only**. Do not upload to repository root.

After GitHub Pages deploys, open https://jones48.github.io/trailblazer.os/handheld/?v=4 in Safari. If the installed Home Screen app shows an old version, close/reopen it or remove and re-add it after verifying the website has updated.

## What works

- Conversation UI with message history stored in this device's browser localStorage
- Time, date, simple arithmetic, project notes, and guided prompts
- Export chat as TXT and clear chat
- Service worker caches the shell for offline opening after first successful load

## Limitations

- This is **not yet a generative AI**. It returns limited local command responses.
- MLC Chat's downloaded model is sandboxed in its own app and is **not connected** to this web page.
- No cloud sync; project notes and history remain in this device/browser storage and may be erased by iOS storage cleanup.
- No microphone interface in this chat-first release. Native on-device Apple Foundation Models access requires a native app.
