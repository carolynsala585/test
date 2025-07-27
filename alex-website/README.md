# Alex sets9ve - Personal Website

A clean, professional personal website with light and dark theme support.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Theme Toggle**: Switch between light and dark themes with persistent preference
- **Professional Layout**: Clean, modern design with smooth animations
- **Social Links**: Easy access to Twitter, GitHub, LinkedIn, and Blog
- **Expertise Showcase**: Highlighting cybersecurity and software security skills

## Files

- `index.html` - Main HTML structure
- `styles.css` - CSS styling with theme variables
- `script.js` - JavaScript for theme switching and animations
- `README.md` - This file

## Customization

### Update Social Links
Edit the social media URLs in `index.html`:

```html
<a href="https://twitter.com/YOUR_USERNAME" target="_blank" rel="noopener noreferrer" class="social-link">
<a href="https://github.com/YOUR_USERNAME" target="_blank" rel="noopener noreferrer" class="social-link">
<a href="https://linkedin.com/in/YOUR_USERNAME" target="_blank" rel="noopener noreferrer" class="social-link">
<a href="https://YOUR_BLOG_URL" target="_blank" rel="noopener noreferrer" class="social-link">
```

### Change the Quote
Replace the quote in `index.html`:

```html
<blockquote class="quote">
    <p>"Your new quote here"</p>
    <cite>— Author Name</cite>
</blockquote>
```

### Modify Expertise
Update the expertise list in `index.html`:

```html
<ul>
    <li>Your Expertise 1</li>
    <li>Your Expertise 2</li>
    <li>Your Expertise 3</li>
</ul>
```

### Customize Colors
Modify the CSS variables in `styles.css` to change the color scheme:

```css
:root {
    --accent: #3b82f6; /* Primary accent color */
    --bg-primary: #ffffff; /* Background color */
    --text-primary: #1e293b; /* Text color */
}
```

## Usage

1. Open `index.html` in a web browser
2. Click the theme toggle button (moon/sun icon) to switch themes
3. Your theme preference will be saved for future visits

## Deployment

You can deploy this website to any static hosting service:

- **GitHub Pages**: Push to a GitHub repository and enable Pages
- **Netlify**: Drag and drop the folder to Netlify
- **Vercel**: Connect your repository to Vercel
- **Any web server**: Upload the files to your web server

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the [MIT License](LICENSE).