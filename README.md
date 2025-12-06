# coding-project-template

## GitHub Pages Deployment

This project is automatically deployed to GitHub Pages using GitHub Actions.

### Live Site

The site is published at: **https://aung-yadanar-oo.github.io/e-plantShopping/**

### How It Works

The deployment is automated through GitHub Actions:
- Every push to the `main` branch triggers an automatic build and deployment
- The workflow can also be manually triggered from the Actions tab on GitHub

### Deployment Workflow

The GitHub Actions workflow (`.github/workflows/pages.yml`) performs the following steps:
1. Checks out the repository code
2. Sets up Node.js environment
3. Installs project dependencies
4. Builds the React app using Vite (`npm run build`)
5. Deploys the built static files from the `dist` folder to GitHub Pages

### Manual Deployment

To deploy changes manually:
1. Make your code changes and commit them
2. Push to the `main` branch: `git push origin main`
3. The GitHub Actions workflow will automatically build and deploy your changes
4. Check the Actions tab on GitHub to monitor the deployment progress

Alternatively, you can trigger a manual deployment:
1. Go to the Actions tab on GitHub
2. Select the "Deploy to GitHub Pages" workflow
3. Click "Run workflow" and select the `main` branch

### Local Development

To run the project locally:
```bash
npm install
npm run dev
```

To build the project locally:
```bash
npm run build
```

To preview the production build locally:
```bash
npm run preview
```