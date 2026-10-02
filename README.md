# The Unhinged Ladle

A responsive, satirical chili food blog built with plain HTML, CSS, and JavaScript. Includes three complete fictional recipe articles, hash-based recipe links, and printable recipes. No build or dependencies required. All asset paths work under a GitHub Pages repository subdirectory.

## Preview

Run `python3 -m http.server 8000` and open http://localhost:8000.

## Publish on GitHub Pages

1. Create a GitHub repository and push this folder to its `main` branch.
2. Under **Settings → Pages → Build and deployment**, choose **GitHub Actions**.
3. Run the **Deploy GitHub Pages** workflow, or push a change to `main`.

The workflow publishes only the public site files. If using another branch, update `.github/workflows/pages.yml`.

## Edit

Recipes and article text live in `app.js`; homepage copy in `index.html`; design in `styles.css`.

Chili photograph: Deepthi Clicks, https://unsplash.com/photos/72oTVZs_730 (Unsplash license). Photography is illustrative, not a photograph of the joke recipes. Google Fonts are optional; system fallback fonts work offline.
