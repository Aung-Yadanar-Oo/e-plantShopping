# e-plantShopping 🌱

A React-based e-commerce application for plant shopping built with Vite, Redux Toolkit, and deployed on GitHub Pages.

## 🚀 Deployed Site

The application is live at: **https://Aung-Yadanar-Oo.github.io/e-plantShopping/**

## 📋 Prerequisites

- Node.js (version 14 or higher)
- npm (comes with Node.js)
- Git

## 🛠️ Getting Started for Contributors

### Initial Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Aung-Yadanar-Oo/e-plantShopping.git
   cd e-plantShopping
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```
   The application will be available at `http://localhost:5173` (or another port shown in the terminal).

### Local Development

- **Start development server**: `npm run dev`
- **Build for production**: `npm run build`
- **Preview production build**: `npm run preview`
- **Lint code**: `npm run lint`

## 🚢 Deployment to GitHub Pages

### Deploy the Application

1. **Ensure all changes are committed**
   ```bash
   git add .
   git commit -m "Your commit message"
   git push origin main
   ```

2. **Deploy to GitHub Pages**
   ```bash
   npm run deploy
   ```
   
   This command will:
   - Build the production version (`npm run build`)
   - Deploy the `dist` folder to the `gh-pages` branch
   - Make the site live at https://Aung-Yadanar-Oo.github.io/e-plantShopping/

### First-Time GitHub Pages Setup

If this is the first deployment:

1. Run `npm run deploy`
2. Go to the repository on GitHub
3. Navigate to **Settings** → **Pages**
4. Ensure **Source** is set to deploy from the `gh-pages` branch
5. The site should be live in a few minutes

## 🔄 Resuming Work (After Logging Out or Switching Devices)

### On the Same Device

1. **Navigate to the project directory**
   ```bash
   cd /path/to/e-plantShopping
   ```

2. **Pull latest changes**
   ```bash
   git pull origin main
   ```

3. **Install any new dependencies** (if package.json changed)
   ```bash
   npm install
   ```

4. **Start development**
   ```bash
   npm run dev
   ```

### On a New Device

1. **Clone the repository** (if not already cloned)
   ```bash
   git clone https://github.com/Aung-Yadanar-Oo/e-plantShopping.git
   cd e-plantShopping
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development**
   ```bash
   npm run dev
   ```

## 📤 Pushing Changes to GitHub

1. **Check status of your changes**
   ```bash
   git status
   ```

2. **Stage your changes**
   ```bash
   git add .
   # Or stage specific files:
   git add src/ComponentName.jsx
   ```

3. **Commit your changes**
   ```bash
   git commit -m "Brief description of changes"
   ```

4. **Push to GitHub**
   ```bash
   git push origin main
   # Or push to your feature branch:
   git push origin your-branch-name
   ```

5. **Deploy updates** (if you want to update the live site)
   ```bash
   npm run deploy
   ```

## 👥 Sharing for Peer Review

### Share the Live Site
Simply share this URL: **https://Aung-Yadanar-Oo.github.io/e-plantShopping/**

### Share Your Code Changes

1. **Create a new branch for your feature**
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make changes and commit**
   ```bash
   git add .
   git commit -m "Add: description of your feature"
   git push origin feature/your-feature-name
   ```

3. **Create a Pull Request**
   - Go to https://github.com/Aung-Yadanar-Oo/e-plantShopping
   - Click "Pull Requests" → "New Pull Request"
   - Select your branch and create the PR
   - Share the PR link with reviewers

### Share a Development Version

If you want reviewers to test your changes before deploying:

1. **Run the dev server**
   ```bash
   npm run dev
   ```

2. **Use a tunneling service** (like ngrok or VS Code port forwarding)
   - Or deploy to a separate test environment

## 🏗️ Project Structure

```
e-plantShopping/
├── src/
│   ├── components/      # React components
│   ├── assets/          # Images and static files
│   ├── App.jsx          # Main App component
│   └── main.jsx         # Application entry point
├── public/              # Public assets
├── dist/                # Production build (auto-generated)
├── package.json         # Dependencies and scripts
└── vite.config.js       # Vite configuration
```

## 🛠️ Available Scripts

| Script | Description |
|--------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Create production build |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint to check code quality |
| `npm run predeploy` | Automatically runs before deploy (builds the app) |
| `npm run deploy` | Deploy to GitHub Pages |

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Notes

- The application uses Vite as the build tool
- State management is handled by Redux Toolkit
- The deployment automatically publishes to the `gh-pages` branch
- Always test locally before deploying to production

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.