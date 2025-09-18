# Vilma's Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This portfolio showcases your design work with a clean, professional aesthetic.

## Features

- ✅ **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- ✅ **Fast Loading** - Optimized for performance with minimal dependencies
- ✅ **Modern UI** - Clean, professional design with smooth animations
- ✅ **Project Showcase** - Dedicated pages for each project
- ✅ **Mobile-First** - Built with mobile-first approach
- ✅ **Accessibility** - Keyboard navigation and focus states
- ✅ **SEO Ready** - Semantic HTML structure

## Project Structure

```
portfolio/
├── index.html              # Homepage
├── loyal-app-icons.html    # Loyal App Icons project
├── music-app-design.html   # Music App Design System project
├── design-system.html      # Design System project
├── illustrations.html      # Illustrations project
├── mobile-app-mockup.html  # Mobile App Mockup project
├── styles.css             # Main stylesheet
├── script.js              # JavaScript functionality
└── README.md              # This file
```

## Customization Guide

### 1. Personal Information
Edit the following in `index.html`:
- Replace "Vilma" with your name
- Update the hero subtitle and description
- Change the email address in contact links
- Update social media links in the footer

### 2. Project Content
For each project page, you can add:
- Project descriptions in the `<p>` tags
- Real images by replacing the placeholder divs
- Additional sections as needed

### 3. Colors and Styling
Modify the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;    /* Main brand color */
    --secondary-color: #64748b;  /* Secondary text */
    --accent-color: #f59e0b;     /* Accent color */
    /* ... other variables */
}
```

### 4. Adding Real Images
Replace the placeholder divs with actual images:
```html
<!-- Instead of -->
<div class="work-placeholder loyal-icons"></div>

<!-- Use -->
<img src="path/to/your/image.jpg" alt="Project description" class="work-image">
```

## Deployment

### Option 1: GitHub Pages
1. Upload files to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch and folder
4. Your site will be available at `https://username.github.io/repository-name`

### Option 2: Netlify
1. Drag and drop the folder to [Netlify](https://netlify.com)
2. Your site will be live instantly with a custom URL

### Option 3: Vercel
1. Connect your GitHub repository to [Vercel](https://vercel.com)
2. Deploy with one click

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- Optimized CSS with minimal dependencies
- Efficient JavaScript with debounced scroll events
- Lazy loading support for images
- Compressed and minified code ready
- Fast loading with Google Fonts optimization

## Contact

For questions or customization help, feel free to reach out!

---

Built with ❤️ for showcasing your amazing design work.
