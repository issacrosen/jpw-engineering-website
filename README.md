# JPW Engineering Website

Professional website for JPW Engineering - MEP Engineering Services in NYC and Hudson Valley.

## Features

- Modern, responsive design
- Services showcase
- Contact information
- Comprehensive Terms of Service page
- Mobile-friendly navigation
- Professional color scheme

## Local Setup

1. Clone this repository:
```bash
git clone https://github.com/YOUR-USERNAME/jpw-engineering.git
cd jpw-engineering
```

2. Open `index.html` in your web browser to view the site locally

## GitHub Pages Deployment

### First Time Setup

1. Create a new repository on GitHub named `jpw-engineering` (or any name you prefer)

2. Add your GitHub repository as remote:
```bash
git remote add origin https://github.com/YOUR-USERNAME/jpw-engineering.git
```

3. Commit and push your files:
```bash
git add .
git commit -m "Initial commit - JPW Engineering website"
git branch -M main
git push -u origin main
```

4. Enable GitHub Pages:
   - Go to your repository on GitHub
   - Click on **Settings**
   - Scroll down to **Pages** in the left sidebar
   - Under **Source**, select **main** branch
   - Click **Save**

5. Your site will be live at: `https://YOUR-USERNAME.github.io/jpw-engineering/`

### Updating the Website

After making changes:
```bash
git add .
git commit -m "Description of changes"
git push
```

Changes will appear on your live site within a few minutes.

## File Structure

```
jpw-engineering-website/
├── index.html          # Main homepage
├── terms.html          # Terms of Service page
├── styles.css          # All styling
└── README.md          # This file
```

## Customization

### Contact Form
The contact form is currently frontend-only. To make it functional, you'll need to:
- Add a backend service (e.g., Formspree, EmailJS)
- Or use a serverless function (e.g., Netlify Forms, Vercel)

### Logo
To add your actual logo:
1. Add logo image file to the project
2. Replace the text logo in the navigation with:
```html
<div class="logo">
    <img src="your-logo.png" alt="JPW Engineering">
</div>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2024 JPW Engineering. All rights reserved.
