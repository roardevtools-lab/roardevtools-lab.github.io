# ROAR DEV TOOLS website

Static website for GitHub Pages. Includes only website files and supplied marketing screenshots; no Unity package source.

## Publish for free

1. Sign in to the `roardevtools-lab` GitHub account.
2. Create a public repository named exactly `roardevtools-lab.github.io`. If that repository already exists, back up its current website before updating it.
3. Extract this website ZIP. Upload the contents of the `roar-dev-tools-website` folder to the repository root, not the containing folder. `index.html` must appear at the root. Include the `assets` folder and all other HTML/CSS files.
4. Commit the uploaded files to `main`.
5. Open repository Settings > Pages. Under Build and deployment, select Deploy from a branch, then `main` and `/ (root)`, and Save.
6. Wait for the Pages deployment to complete. The intended public URL is https://roardevtools-lab.github.io/ . It becomes live only after deployment succeeds.
7. Open every page and test the support email link, then add the URL to your Unity publisher profile.

No custom domain or paid hosting is required. GitHub Pages uses a public repository on the free plan, so all website files are public.

## Preview locally

From this folder, run `python -m http.server 8000` and open http://localhost:8000 .

## Update after Asset Store publication

Replace the “Asset Store release coming soon” badges with a link to the real listing. Use only compatibility versions you have verified.

## Content notes

The current uploaded package was inspected to ground the site in its actual workflow. The site's compatibility follows the publisher's supplied verification: Unity 2022.3 LTS and development in Unity 6000.0.74f1. The package PDF contains different version requirements; reconcile those before submission. No automated tests or Unity changes were added.
