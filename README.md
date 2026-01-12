# Mechanical Engineer Portfolio Website

A professional, responsive portfolio website designed for mechanical engineers to showcase their projects, skills, and experience.

## Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Hero Section**: Eye-catching landing page with name, title, and call-to-action
- **About Me**: Comprehensive background, skills, and software proficiencies
- **Projects Showcase**: 6 detailed project cards with individual project pages
- **Contact Section**: Contact form with validation and social media links
- **Modern UI**: Clean, minimal design with smooth animations and transitions
- **Accessibility**: Semantic HTML and ARIA labels for better accessibility

## Project Structure

```
PersonalPortfolio/
├── index.html              # Main homepage
├── css/
│   └── styles.css         # All styles and responsive design
├── js/
│   └── main.js           # Interactive functionality
├── images/               # Placeholder for project images
└── projects/            # Individual project detail pages
    ├── project1.html    # Automotive Suspension Component
    ├── project2.html    # HVAC System Design
    ├── project3.html    # Manufacturing Fixture Design
    ├── project4.html    # Vibration Analysis System
    ├── project5.html    # Automated Material Handling
    └── project6.html    # Thermal Management System
```

## Customization Guide

### 1. Personal Information

**Update your name and contact information in `index.html`:**

- Line 39-41: Update name and title in the hero section
- Line 303-313: Update email address and LinkedIn URL
- All project pages: Update footer and navigation as needed

### 2. About Me Section

**Edit `index.html` (lines 60-140):**

- Update your educational background
- Modify years of experience
- Customize your engineering philosophy
- Add/remove core competencies
- Update software proficiencies

### 3. Projects

**Main page (`index.html`):**
- Lines 150-330: Update project titles, descriptions, challenges, tools, and outcomes

**Individual project pages (`projects/project*.html`):**
- Update project details, methodologies, results, and learnings
- Customize technical specifications
- Add your own metrics and achievements

### 4. Adding Your Own Images

Replace the SVG placeholders with real images:

1. Add your professional headshot:
   - Replace the SVG in the hero section (index.html, line 46)
   - Recommended size: 350x350px, format: JPG or PNG

2. Add project images:
   - Save images to the `images/` folder
   - Replace SVG placeholders in project cards
   - Recommended size: 800x500px for detail pages, 400x300px for cards

Example:
```html
<!-- Replace this: -->
<div class="image-placeholder">
    <svg>...</svg>
</div>

<!-- With this: -->
<img src="../images/project1-main.jpg" alt="Project description">
```

### 5. Color Scheme

Customize colors in `css/styles.css` (lines 9-20):

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --primary-dark: #1e40af;       /* Hover states */
    --text-primary: #1e293b;       /* Main text */
    --text-secondary: #475569;     /* Secondary text */
    /* ... more colors ... */
}
```

### 6. Contact Form

The contact form currently displays a success message locally. To make it functional:

**Option 1: Using Formspree (Recommended for beginners)**
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

**Option 2: Using EmailJS**
Add EmailJS library and configure in `js/main.js`

**Option 3: Backend Integration**
Connect to your own backend API endpoint

### 7. Adding/Removing Projects

To add a new project:

1. Create a new file: `projects/project7.html`
2. Copy structure from existing project page
3. Add new project card to `index.html` in the projects section
4. Update navigation links in adjacent project pages

To remove a project:

1. Delete the project file from `projects/` folder
2. Remove the corresponding project card from `index.html`
3. Update navigation links in adjacent project pages

## Deployment

### GitHub Pages (Free)

1. Create a GitHub repository
2. Push your code to the repository
3. Go to Settings → Pages
4. Select main branch as source
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify (Free)

1. Create account at netlify.com
2. Drag and drop your project folder
3. Your site will be live instantly with a custom URL
4. Optional: Connect custom domain

### Traditional Web Hosting

1. Upload all files via FTP to your hosting provider
2. Ensure `index.html` is in the root directory
3. Access your site at your domain

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips

1. **Optimize Images**: Use WebP format for better compression
2. **Minify CSS/JS**: Use tools like UglifyJS and CSSNano for production
3. **Enable Caching**: Configure cache headers on your server
4. **Use CDN**: Consider using a CDN for faster global delivery

## Accessibility

The website follows WCAG 2.1 guidelines:

- Semantic HTML structure
- ARIA labels for interactive elements
- Keyboard navigation support
- Sufficient color contrast ratios
- Responsive font sizes

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Google Fonts**: Inter font family
- **SVG**: Scalable placeholder graphics

## Future Enhancements

Consider adding:

- [ ] Blog section for technical articles
- [ ] Downloadable resume/CV
- [ ] Testimonials section
- [ ] Dark mode toggle
- [ ] Project filtering by category
- [ ] Animation on scroll (AOS library)
- [ ] Analytics integration (Google Analytics)
- [ ] SEO optimization (meta tags, schema markup)

## License

This template is free to use for personal and commercial projects. Attribution is appreciated but not required.

## Support

For questions or issues:
- Review the customization guide above
- Check browser console for JavaScript errors
- Ensure all file paths are correct
- Verify HTML structure is valid

---

**Built with care for mechanical engineers by mechanical engineers.**

Good luck with your portfolio! 🚀
