# TrailBlazer OS 0.3 — Bill Voice Interface

Upload `index.html` and `sw.js` into the `handheld/` directory of the `jones48/trailblazer.os` GitHub repository, replacing `index.html` and adding `sw.js` if absent. Leave the repository root unchanged. Wait for GitHub Pages to deploy and open https://jones48.github.io/trailblazer.os/handheld/?v=3 in Safari.

Features: animated orb, browser speech recognition when supported, text command fallback, spoken replies via browser speech synthesis, camera/photo/file pickers, basic arithmetic, local project notes saved in browser localStorage, and page caching for offline reopening after initial successful load. Camera and photos use browser file selection, not unrestricted access to native apps. Offline AI model is NOT integrated: MLC Chat remains a separate app. Speech recognition on Safari may be unsupported or require internet, even when this page is cached. Test offline functionality after loading once online.

Do not put API keys or sensitive project secrets into public GitHub files.
