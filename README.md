# Bukhsh Estate & Marketing (demo site)

A static site: no build step, no dependencies to install. GSAP and the fonts load from CDNs.

    index.html
    assets/hero.mp4  poster.jpg  bukhsh_logo.jpg

Interior and aerial photos are hotlinked from Unsplash (see credits in the footer).

## Run locally
Open `index.html` in a browser, or run `npx serve .` in this folder.

## Deploy
- Vercel: run `npx vercel` in this folder (or drag the folder onto vercel.com/new). Framework preset: Other. No build command, output directory `.`
- GitHub Pages: push this folder to a repo, then Settings > Pages > Deploy from branch > main / root.

## Make it your client's
Edit index.html, then swap the files in `assets/`.
