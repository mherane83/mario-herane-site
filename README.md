# Mario Herane Personal Website

Static bilingual personal website ready for GitHub Pages.

## Publish with GitHub Pages

1. Create a new GitHub repository, for example:
   `mario-herane-site`

2. Upload all files in this folder to the repository.

3. In GitHub, go to:
   Settings > Pages

4. Under "Build and deployment":
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /root

5. Save.

Your site will be available at:

`https://YOUR-GITHUB-USERNAME.github.io/mario-herane-site/`

## Local preview

Open `index.html` in your browser.

## Custom domain

If you own a domain, add it in:
Settings > Pages > Custom domain

Then configure your DNS with your domain provider.

## Main files

- `index.html`
- `styles.css`
- `script.js`
- `assets/`


## Image troubleshooting

This version uses JPG image references consistently:
- `./assets/mario-herane-hero.jpg`
- `./assets/mario-herane-portrait.jpg`

After publishing, test:
`https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPO/image-check.html`

If images appear there, the site image paths are correct.
If they do not appear, the `assets` folder was not uploaded to GitHub or GitHub Pages has not refreshed yet.
