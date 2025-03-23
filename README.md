# Personal Portfolio Website

This is a modern, responsive portfolio website built with HTML, CSS, and JavaScript. It features a clean design with smooth animations and interactive elements.

## Features

- Responsive design that works on all devices
- Smooth scrolling navigation
- Animated sections on scroll
- Contact form
- Skills showcase
- Experience timeline
- Social media links
- Modern UI with clean typography

## Customization

### 1. Update Personal Information
Edit the `index.html` file to update:
- Your name
- Professional title
- About section content
- Skills list
- Work experience
- Contact information
- Social media links

### 2. Change Colors
In the `styles.css` file, you can modify the color scheme by updating the CSS variables in the `:root` selector:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --text-color: #1f2937;
    --light-text: #6b7280;
    --background: #ffffff;
    --section-bg: #f3f4f6;
}
```

### 3. Add Your Projects
To add a projects section, you can create a new section in `index.html` and style it in `styles.css`.

## Deployment Options

### 1. GitHub Pages (Free)
1. Create a new repository on GitHub
2. Push your code to the repository
3. Go to repository Settings > Pages
4. Select the main branch as the source
5. Your site will be available at `https://yourusername.github.io/repository-name`

### 2. Netlify (Free)
1. Sign up for a Netlify account
2. Connect your GitHub repository
3. Deploy your site with one click
4. Your site will be available at `https://your-site-name.netlify.app`

### 3. Vercel (Free)
1. Sign up for a Vercel account
2. Connect your GitHub repository
3. Deploy your site with one click
4. Your site will be available at `https://your-site-name.vercel.app`

## Local Development

To run the website locally:
1. Clone this repository
2. Open `index.html` in your web browser
3. Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

## Browser Support

The website is compatible with all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

Feel free to submit issues and enhancement requests! 