# Party Invitation Website 🎉

A festive HTML website with animated party invitation design featuring a big letter "P" in the center with colorful animations and confetti effects.

## Features

- 🎨 Animated gradient background with shifting colors
- ✨ Big letter "P" with pulsing animation and glowing effects
- 🎊 Falling confetti animation
- ⭐ Sparkling effects
- 📱 Responsive design for mobile devices
- 🎵 Party-themed text with floating animation

## How to Deploy to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in to your account
2. Click the "+" icon in the top right corner and select "New repository"
3. Name your repository (e.g., `party-invitation` or `my-party-site`)
4. Make sure it's set to **Public** (required for free GitHub Pages)
5. **Do NOT** initialize with README, .gitignore, or license (since we already have files)
6. Click "Create repository"

### Step 2: Upload Your Files

#### Option A: Using GitHub Web Interface
1. In your new repository, click "uploading an existing file"
2. Drag and drop your `index.html` file
3. Add a commit message like "Add party invitation website"
4. Click "Commit changes"

#### Option B: Using Git Command Line
```bash
# Navigate to your project folder
cd C:\Users\Usuario\Desktop\IMPORTANTES\Fiesta_museo

# Initialize git repository
git init

# Add your files
git add .

# Commit your changes
git commit -m "Add party invitation website"

# Add your GitHub repository as remote (replace YOUR_USERNAME and YOUR_REPO_NAME)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab (at the top of your repository)
3. Scroll down to "Pages" section in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"
7. GitHub will show you a URL like: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`

### Step 4: Access Your Website

- Your website will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`
- It may take a few minutes to deploy initially
- You can check the deployment status in the "Actions" tab of your repository

## Customization

You can easily customize the website by editing the `index.html` file:

- **Change the letter**: Replace the "P" in the `.big-letter` div
- **Change colors**: Modify the gradient colors in the `background` CSS property
- **Change text**: Update the party text in the `.party-text` divs
- **Adjust animations**: Modify the animation durations and effects in the CSS

## File Structure

```
├── index.html          # Main HTML file with embedded CSS and JavaScript
└── README.md          # This file with deployment instructions
```

## Browser Support

This website works on all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## License

This project is open source and available under the [MIT License](LICENSE).
