# IIQE Paper 1 — iPhone Study (GitHub Pages)

This folder is ready to publish as a static site: upload `index.html` to a GitHub
repository, enable Pages, and open the URL on your iPhone.

## Option A — no git, from the GitHub website

1. Sign in at https://github.com and click **New repository**.
2. Name it (e.g. `iiqe-study`), set it to **Public**, and click **Create repository**.
3. On the new repo page click **uploading an existing file**.
4. Drag `index.html` into the page and click **Commit changes**.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, set **Source** to **Deploy from a branch**,
   **Branch** to **main**, folder to **/ (root)**, then **Save**.
7. Wait 1–2 minutes. Your site is at:
   `https://YOUR-USERNAME.github.io/iiqe-study/`
8. On the iPhone: open that link in **Safari**, tap **Share** → **Add to Home Screen**.

## Option B — with git on your computer

```bash
git init
git add index.html
git commit -m "Add IIQE iPhone study app"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/iiqe-study.git
git push -u origin main
```

Then enable Pages exactly as in steps 5–7 above.

## Updating later

Replace `index.html` in the repository (website upload or `git push`). Pages
redeploys automatically in about a minute. If Safari shows the old version,
reload the page (pull down to refresh).

## Notes

- The file must be named `index.html` at the repository root (or inside a
  `docs/` folder, with Pages set to that folder).
- Keep the repository **Public** — GitHub Pages is free for public repositories.
- Study progress is saved in the browser's localStorage for that site address,
  so keep using the same URL to keep your progress.
