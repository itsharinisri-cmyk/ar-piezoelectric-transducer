# Piezoelectric Transducer Explorer

A static GitHub Pages project with a rotatable 3D educational model, cutaway toggle, force-to-voltage demonstration, and WebXR / Scene Viewer / Quick Look AR entry point.

## Publish on GitHub Pages
1. Extract this ZIP.
2. In your GitHub repository, upload `index.html` and the entire `models` folder to the repository root (not inside another folder).
3. Go to **Settings → Pages**. Select **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
4. Open the Pages URL after deployment finishes.

## Notes
- Keep the two `.glb` files inside the `models` folder.
- The simulator uses a demo coefficient of 0.10 V/N; it is not a calibrated sensor model.
- AR requires a compatible mobile browser/device and HTTPS.
