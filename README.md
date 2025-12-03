# Sample Website for GitHub Pages

This repository contains a minimal static website you can use to learn how to create and host a site on GitHub Pages.

## Files
- `index.html` — main page
- `styles.css` — simple styles
- `LICENSE` — MIT license

## How to host on GitHub Pages (quick)
1. Create a new repository on GitHub (e.g., `sample-site`).
2. Clone it locally:
   ```bash
   git clone https://github.com/<your-username>/sample-site.git
   ```
3. Copy these files into the repo, commit, and push:
   ```bash
   git add .
   git commit -m "Add sample site"
   git push origin main
   ```
4. On GitHub, go to **Settings → Pages** (or **Settings → Code and automation → Pages**), choose the branch (`main`) and the folder (`/ (root)`), then Save.
5. Your site will be published at `https://<your-username>.github.io/<repo-name>/` (or `https://<your-username>.github.io/` if repository is named `<your-username>.github.io`).

## Alternative: Use `gh-pages` branch
You can also publish from a `gh-pages` branch. Create the branch and push it, then select it in the Pages settings.

## Notes
- For a custom domain, add a `CNAME` file with your domain name.
- If you want automatic deployment from the `main` branch, ensure the branch contains your static files in the root.
