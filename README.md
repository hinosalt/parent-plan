# ParentPlan Frontend

This demo showcases a parenting plan web app built with only static HTML, CSS and JavaScript.

## Features
- Responsive design with a mobile menu
- Language toggle (Japanese/English)
- Local sign-up and login using `localStorage`
- Multi-step parenting plan wizard, calendar, communication and expense tools

Open `index.html` in a browser to try it out.

## Deployment

To deploy this static site on GitHub Pages, enable Pages in your repository settings.
A GitHub Actions workflow is provided in `.github/workflows/deploy.yml` to automatically publish the site when pushing to `main`.
You can also preview locally using any static server, e.g. run `npx http-server` and open the URL it outputs.
