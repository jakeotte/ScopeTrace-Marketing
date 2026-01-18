# ScopeTrace Marketing Website

A modern, responsive marketing website for ScopeTrace - the audit evidence management platform.

## Features

- 🎨 Modern, sleek SaaS design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Fast loading with optimized assets
- 🎯 SEO-friendly structure
- ✨ Smooth animations and interactions
- 🔒 Security-focused messaging

## Deployment to GitHub Pages

This site is designed to be deployed via GitHub Pages. Here's how to set it up:

### Option 1: Using GitHub Actions (Recommended)

1. Push this repository to GitHub
2. Go to your repository Settings → Pages
3. Select "GitHub Actions" as the source
4. Create a `.github/workflows/deploy.yml` file (see below)

### Option 2: Using the gh-pages branch

1. Push this repository to GitHub
2. Go to your repository Settings → Pages
3. Select the `gh-pages` branch as the source
4. GitHub Pages will automatically serve the files

### Option 3: Using GitHub CLI

```bash
# Install gh-pages if you haven't already
npm install -g gh-pages

# Deploy to GitHub Pages
gh-pages -d . -b gh-pages
```

## File Structure

```
.
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript for interactivity
├── README.md           # This file
└── .nojekyll          # Prevents Jekyll processing (if needed)
```

## Local Development

To view the site locally:

1. Clone the repository
2. Open `index.html` in a web browser, or
3. Use a local server:

```bash
# Python 3
python -m http.server 8000

# Node.js (with http-server)
npx http-server

# PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Customization

### Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary: #4F46E5;        /* Main brand color */
    --primary-dark: #4338CA;   /* Darker shade */
    --primary-light: #6366F1;  /* Lighter shade */
    /* ... */
}
```

### Content

- Update text content in `index.html`
- Modify sections as needed
- Add or remove feature cards
- Update framework information

### Images/Icons

- Replace emoji icons with SVG or image files if desired
- Update the logo SVG in the navigation and footer

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

Copyright © 2024 ScopeTrace. All rights reserved.
# ScopeTrace-Marketing
