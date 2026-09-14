# Kuntal Sarkar - Developer Portfolio

A responsive, high-performance portfolio website built with pure semantic HTML5, modern CSS3, and vanilla JavaScript. Features a dark slate tech aesthetic with cyan and violet accents, dynamic canvas particles, 3D tilt effects, light/dark mode, and scroll animations.

## 🌟 Key Features

- **Dark / Light Theme Switch**: Sleek dark slate (#0b0f17) palette with cyan/violet neon glows, plus a high-contrast light mode saved to `localStorage`.
- **Interactive Particle Network**: Lightweight HTML5 Canvas background with mouse-interactive connecting nodes.
- **Scroll-Triggered Reveals**: Smooth fade, slide, and scale transitions driven by the native `IntersectionObserver` API.
- **Interactive 3D Tilt**: Perspective card tilting on hover for project, skill, and stat cards.
- **Dynamic Typewriter**: Hero section role animation with smooth cursor blinking.
- **Zero Framework Dependencies**: Pure Vanilla JS & CSS — loads instantly with no build or compilation steps.
- **Fully Responsive**: Optimized for mobile, tablet, and widescreen layouts with hamburger navigation.

## 🚀 How to Publish to GitHub Pages

To publish this portfolio to your GitHub account (`https://github.com/kuntalsarkar96744-afk`):

### 1. Create a New Repository on GitHub
1. Log in to your GitHub account.
2. Click **New** (or go to `https://github.com/new`).
3. Set the repository name to `portfolio` (or `kuntalsarkar96744-afk.github.io` for a root user page).
4. Keep it **Public** and leave "Initialize with README" unchecked.
5. Click **Create repository**.

### 2. Push Your Code Using Git
Open your local terminal inside the portfolio folder:

```bash
# Initialize git repository
git init

# Stage all portfolio files
git add .

# Create initial commit
git commit -m "Initial commit: Kuntal Sarkar Developer Portfolio"

# Rename branch to main
git branch -M main

# Link remote repository (replace with your repository URL)
git remote add origin https://github.com/kuntalsarkar96744-afk/portfolio.git

# Push code to GitHub
git push -u origin main
```

### 3. Enable GitHub Pages (Instant Live Website)
1. In your repository on GitHub, click **Settings** > **Pages** (in the left sidebar).
2. Under **Build and deployment** > **Source**, select **Deploy from a branch**.
3. Choose branch `main` and folder `/ (root)`, then click **Save**.
4. Within 1–2 minutes, your website will be live at:
   `https://kuntalsarkar96744-afk.github.io/portfolio/`
