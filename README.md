# Personal Portfolio Website

A fully responsive, modern personal portfolio website built with pure HTML, CSS, and JavaScript (no frameworks).

## Features

- ✨ Modern, elegant, and minimal design
- 📱 Fully responsive for all screen sizes
- 🎨 Smooth CSS animations and transitions
- 🖱️ Interactive hover effects
- 📜 Smooth scrolling navigation
- 🎯 Scroll-triggered animations
- 🌈 Gradient color scheme (deep teal, aquamarine, indigo)
- ⚡ Lightweight and fast

## Sections

1. **Home / Intro** - Fullscreen hero section with animated background
2. **About Me** - Personal introduction with photo placeholder
3. **Skills** - Interactive skill tags with hover effects
4. **Projects** - 4 project cards with animations
5. **Achievements** - Certifications and achievements display
6. **Resume** - Download button with preview option
7. **Contact** - Contact form and social links

## Getting Started

1. Simply open `index.html` in your web browser
2. No build process or dependencies required!

## Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #0b1d26;
    --secondary-color: #133c55;
    --accent-color: #22d1b2;
    /* ... */
}
```

### Content
- Update personal information in `index.html`
- Modify project details in the Projects section
- Add your resume PDF link in the Resume section
- Update social media links in the Contact section

### Adding Your Photo
Place your headshot (for example `dp.1.jpg`) in the project root and keep the `<img>` reference in the About section pointing to it. The markup already falls back to a neutral placeholder if the file is missing.
```html
<img src="dp.1.jpg"
     alt="Dharun Prakash G T"
     onerror="this.onerror=null; this.src='https://via.placeholder.com/400x400.png?text=Dharun+Prakash+G+T';">
```

### Resume Download
Update the resume download link in `script.js`:
```javascript
downloadResume.addEventListener('click', (e) => {
    e.preventDefault();
    window.open('path-to-your-resume.pdf', '_blank');
});
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2025 Dharun Prakash G T. All rights reserved.

