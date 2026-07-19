# AVIS Residence

Static website for AVIS Residence apartments (Sutorina, Igalo).

## Hosting on GitHub Pages

1. Create a new GitHub repository and upload the **contents of this folder** (index.html, support.js, image-slot.js, image-slots.state.json, uploads/, .nojekyll).
2. In the repo: **Settings -> Pages**.
3. Under *Build and deployment*, set **Source = Deploy from a branch**, branch = **main**, folder = **/ (root)**, then Save.
4. After a minute the site is live at `https://<username>.github.io/<repo>/`.

Everything is static — no build step, no server. The `.nojekyll` file must stay so all assets are served as-is.
