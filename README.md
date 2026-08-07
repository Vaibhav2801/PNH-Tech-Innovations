# PNH Tech Innovations — GitHub Pages website

This repository contains a complete static website for PNH Tech Innovations Pvt Ltd. It uses plain HTML and CSS, so there is no build step and no framework dependency.

## Deploy with GitHub Pages

1. Create a new repository on GitHub.
2. Extract the ZIP and upload **all files and folders** to the repository root, including `.github` and `.nojekyll`.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages** in the repository.
5. Under **Build and deployment**, choose **GitHub Actions** as the source.
6. Open the repository's **Actions** tab and wait for “Deploy PNH website to GitHub Pages” to finish.
7. Your public address will appear in the deployment summary and under **Settings → Pages**.

The deployment runs automatically after every push to `main`.

## Edit the website

- Page content: `index.html`
- Design and responsive layout: `styles.css`
- Hero image: `assets/pnh-industrial-hero.png`
- Automatic deployment: `.github/workflows/pages.yml`

All image and stylesheet paths are relative, so the site works both at `username.github.io` and at `username.github.io/repository-name/`.

## Custom domain

To use your own domain, add it in **Settings → Pages → Custom domain**. GitHub will provide the DNS records to add at your domain provider.
