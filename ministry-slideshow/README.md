# Ministry Slideshow

A self-contained HTML slideshow. Everything (styles, scripts, and images) is bundled into a single `index.html` file — no build step, no dependencies.

## View it

- **Locally:** open `index.html` in any modern browser.
- **Online (GitHub Pages):** enable Pages for this repo (Settings → Pages → deploy from the `main` branch, `/root`), then visit the published URL.

## Notes

- The file is large (~16 MB) because all assets are inlined. It renders on load once JavaScript unpacks the bundle.
- JavaScript must be enabled to display the slideshow.

## Publishing to GitHub

```bash
cd "ministry-slideshow"
git init
git add .
git commit -m "Add ministry slideshow"
git branch -M main
git remote add origin https://github.com/<your-username>/ministry-slideshow.git
git push -u origin main
```
