# Double D 语言工作室 — Join Page

Simple bilingual page with WeChat QR codes: personal contact and activities mini-app. Event details stay in the shared mini-app link.

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
npx --yes serve .
```

On Ampps: visit `http://localhost/doubled/` (or your Ampps domain path).

## Publish on GitHub Pages

1. Create a GitHub repository and push this folder to the `main` branch (repo root = site root).
2. On GitHub: **Settings → Pages → Build and deployment**
3. Source: **Deploy from a branch**
4. Branch: `main` / folder: `/ (root)` → Save
5. After a minute, open: `https://<your-username>.github.io/<repo-name>/`

## Replace QR codes later

Put new images in `assets/`:

| File | Purpose |
|------|---------|
| `assets/qr-personal.jpg` | Personal WeChat contact |
| `assets/qr-activities.png` | WeChat mini-program (all activities) |
| `assets/hero.jpg` | Hero photo |

Edit text in `index.html` as needed.
