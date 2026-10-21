# Maria Foskolou · Portfolio
`index.html` is fully self-contained (all images, CSS and JS are embedded), so the site cannot lose its images when uploaded.

**Deploy on GitHub Pages:** create a repo → upload `index.html` and `.nojekyll` (the `source/` folder is optional) → Settings → Pages → Deploy from a branch → `main` / root → Save. Live at `https://<username>.github.io/<repo>/`.

**Editing:** change text/colours in `source/app.js` / `source/style.css`, then run `python3 source/build.py` to regenerate `index.html`. Replace the LinkedIn link in `source/index.html` (`id="li"`).
