# Codestar Technologies International

A responsive, single-page company website built with plain HTML, CSS, and JavaScript. No build step or package installation is required.

## Preview locally

Open `index.html` in a browser, or use the VS Code Live Server extension for automatic refresh while editing.

## Before publishing

- Replace the sample email `hello@codestar.example` in `index.html` and `script.js` with the company's real contact address.
- Update the company description, services, imagery, and any other content to match Codestar's actual offerings.
- The inquiry form opens a pre-filled email draft; it does not send or store submissions. A backend or form service is needed for direct submissions.
- The photos and web fonts load from Unsplash and Google Fonts, so those assets require an internet connection.

## Publish to GitHub

Create an empty repository on GitHub, then run these commands from this folder (replace the URL with your repository URL):

```sh
git init
git add .
git commit -m "Add Codestar company website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

To host the site with GitHub Pages, open the repository's **Settings > Pages**, choose the `main` branch and `/ (root)` folder, and save. The site will be available at the Pages URL GitHub provides.
