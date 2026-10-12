# Muse Studios — static site

```
index.html     ← entire site: all CSS + JS inline
*.png          ← film stills + founder photo (root level)
.nojekyll      ← tells GitHub Pages to serve files as-is
404.html       ← redirects unknown URLs to the homepage
```

## GitHub Pages
1. Upload the contents of this folder (keep all .png files and `.nojekyll`) to the root of a repo.
2. Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
3. Live at `https://<user>.github.io/<repo>/` in ~1 minute.

No build step. React, Babel and Google Fonts load from public CDNs at runtime.
