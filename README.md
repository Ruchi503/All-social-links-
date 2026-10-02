# ArtSense links page

A static link-in-bio page for ArtSense (Instagram, YouTube, Pinterest, and the ZaveCo shop).

## Files
- `index.html` — the page
- `favicon.svg` — browser tab icon
- `404.html` — sends broken links back to the home page
- `.nojekyll` — tells GitHub Pages to serve the files as-is

## Publish on GitHub Pages
1. Create a new public repository (name it `artsensegirl.github.io` if your GitHub username is `artsensegirl` to get the shortest URL; any name works).
2. Upload all four files to the root of the repository. `.nojekyll` is hidden on some computers, so if you can't see it, create a new empty file with that name in GitHub instead.
3. Go to **Settings → Pages**, set **Source** to "Deploy from a branch", choose `main` and `/ (root)`, then save.
4. After a minute or two the site is live at `https://<username>.github.io/` or `https://<username>.github.io/<repo-name>/`.

## Editing links
Open `index.html` and find the `<ul class="links">` section. Each link is one `<li>`; change the `href` to update a URL.
