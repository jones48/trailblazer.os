# Bill AI 0.5 — Local Brain Test

Experimental browser-based LLM test, **separate from Bill 0.4**.

## Install on GitHub (mobile)

1. In `jones48/trailblazer.os`, open the `handheld` directory.
2. Create a new folder `ai-test` by uploading these files at `handheld/ai-test/index.html` and `handheld/ai-test/worker.js` (GitHub web UI may require creating the folder via **Add file → Create new file** first, typing `ai-test/.gitkeep`, then committing; alternatively upload with a desktop browser).
3. Open `https://jones48.github.io/trailblazer.os/handheld/ai-test/` after Pages deploys.
4. Tap **Download & start Bill**. First download requires internet.

Do **not** overwrite any file directly in `handheld/` or the repository root.

## Technical notes

- Uses Transformers.js 3.8.1 in a module Web Worker and ONNX Community Qwen3-0.6B model with WebGPU and q4 weights.
- This model/pipeline pairing is experimental and **not verified on the user's device**. CDN/model revision availability and iOS memory limits can prevent loading. Test and inspect status messages before relying on it.
- The test does not request a paid API key or send prompts to a remote inference API. Browser fetches model files from the CDN/model repository.
- Browser caching/offline availability depends on browser storage policy; there is no service worker in this isolated test.
- Model-generated engineering facts may be wrong; verify measurements and safety-critical instructions.
