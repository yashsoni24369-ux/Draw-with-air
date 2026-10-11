# AirDraw — smoother version

This update is optimized to reduce finger-drawing lag:
- Uses MediaPipe's faster `modelComplexity: 0` setting.
- Requests a smaller 320×240 camera stream.
- Keeps the camera preview canvas small instead of rendering it at the full drawing-area resolution every frame.
- Prevents overlapping hand-tracking requests.
- Applies light fingertip smoothing to reduce jitter.

## Publish the update
1. Extract this ZIP.
2. Open your existing GitHub repository.
3. Replace the old `index.html` with the new one and commit the change.
4. Wait for GitHub Pages to deploy, then reload the website. If your phone shows the old version, close and reopen the tab.

Camera access requires HTTPS or localhost. MediaPipe models load from a CDN, so internet access is required.
