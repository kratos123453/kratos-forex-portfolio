# Deploy Your Portfolio to GitHub

## 🚀 Step-by-Step Instructions

### 1. Create a GitHub Repository
1. Go to [GitHub.com](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name it: `kratos-forex-portfolio` (or any name you prefer)
5. Make it **Public** (so GitHub Pages can host it)
6. **Don't** initialize with README (we already have one)
7. Click "Create repository"

### 2. Connect Your Local Repository
After creating the repository, GitHub will show you commands. Use these:

```bash
# Add the remote repository (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/kratos-forex-portfolio.git

# Push your code to GitHub
git branch -M main
git push -u origin main
```

### 3. Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" section (in the left sidebar)
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

### 4. Your Portfolio Will Be Live!
- GitHub will provide you with a URL like: `https://YOUR_USERNAME.github.io/kratos-forex-portfolio`
- It may take a few minutes to deploy
- You can share this URL with anyone!

## 📝 Example Commands
If your GitHub username is "kratos", the commands would be:
```bash
git remote add origin https://github.com/kratos/kratos-forex-portfolio.git
git branch -M main
git push -u origin main
```

## 🔧 Troubleshooting
- If you get authentication errors, you may need to set up a Personal Access Token
- Make sure the repository is public for GitHub Pages to work
- The first deployment can take 5-10 minutes

Your portfolio will be live and accessible to anyone with the URL! 🎮📈 