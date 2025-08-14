# ARMA Hand Scanner (Web)

Phone-ready static site. Deploy with **GitHub Pages**:

## Quick Deploy
1. Create a new repo (e.g., `hand-scanner`).
2. Upload these files to the repo root.
3. In repo settings → **Pages** → Source: **Deploy from a branch** → Branch: `main` (or `master`), folder: `/root`.
4. Your site will be at `https://<your-username>.github.io/<repo-name>/` (e.g., `https://yourname.github.io/hand-scanner/`).

## Usage
- Open on your phone, allow camera.
- Use the **Glove Size** auto-calibration (S–3XL), or fine-tune with Pixels/mm.
- Capture 8–12 views → **Build 3D** → **Export STL**.

## Notes
- Works fully on-device. WebXR depth is used only if available on your device/browser.
- To customize brand size tables, edit the `SIZE_TABLES` JSON in `index.html`.
