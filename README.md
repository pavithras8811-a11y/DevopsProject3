# Automated Website Deployment Using GitHub Actions

## Project description
A simple static website that is automatically deployed to GitHub Pages whenever changes are pushed to the `main` branch. This beginner project demonstrates Git version control and a basic CI/CD workflow.

## Tools used
- HTML and CSS
- Git and GitHub
- GitHub Actions
- GitHub Pages

## Project files
- `index.html` — website content
- `style.css` — website styling
- `.github/workflows/deploy.yml` — automated deployment workflow

## How to run locally
1. Download or clone this repository.
2. Open `index.html` in a web browser.

## How to deploy
1. Create a new GitHub repository.
2. Upload these project files to the repository's `main` branch.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, choose **GitHub Actions** as the source.
5. Open the **Actions** tab and check that the workflow completes successfully.
6. After deployment, open **Settings → Pages** to find the published website URL.

## How automatic deployment works
Whenever you push a change to the `main` branch, GitHub Actions checks out the repository, packages the website files, and deploys them to GitHub Pages.

## Customization
Edit the text in `index.html` or the styles in `style.css`, then commit and push the changes to `main`. The workflow will deploy the updated site.

## Learning outcomes
- Basic Git and GitHub usage
- Understanding a CI/CD workflow
- Automating static website deployment
- Hosting a website with GitHub Pages

## Notes
This project deploys a static HTML/CSS website; it does not require a server or database. GitHub Pages availability and repository visibility settings depend on your GitHub account and repository configuration.
