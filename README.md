# AirDraw — Finger Motion Canvas

A single-page website that lets you draw on a canvas by pinching your thumb and index finger in front of your camera. Includes color selection, brush size, undo, clear, PNG export, and mouse/touch fallback.

## Run locally
Camera access generally requires HTTPS or `localhost`. You can use VS Code with the Live Server extension, then open the local URL in a modern browser.

## Publish on GitHub Pages
1. Create a public repository named `airdraw`.
2. Upload `index.html` and this `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, branch `main`, folder `/(root)`, and Save.
5. Visit `https://YOUR-USERNAME.github.io/airdraw/` after deployment finishes.

## Notes
- Internet access is needed to load MediaPipe from jsDelivr.
- Allow camera access when prompted.
- Use HTTPS or localhost for camera access.
- The camera stream is processed in the browser; this project does not upload video to a server.
