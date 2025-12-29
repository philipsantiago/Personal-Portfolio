# Mechanical Engineer Portfolio Website

A professional portfolio website showcasing mechanical engineering projects, skills, and expertise. Built with clean HTML, CSS, and vanilla JavaScript.

## Features

### 🎯 Main Sections

1. **Hero/Landing Section**
   - Professional introduction with name and title
   - Headshot placeholder
   - Call-to-action button

2. **About Me**
   - Educational background and experience summary
   - Core competencies list
   - CAD/simulation software proficiencies with skill bars
   - Engineering philosophy statement

3. **Projects Portfolio**
   - 6 featured engineering projects with detailed case studies
   - Each project includes:
     - Technical challenges
     - Tools and software used
     - Key outcomes and metrics
     - Detailed project pages with comprehensive write-ups

4. **Contact Section**
   - Functional contact form
   - LinkedIn and email links
   - Professional contact information

### 🎨 Design Features

- **Clean & Minimal**: Professional aesthetic suitable for engineering portfolio
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Subtle fade-in effects and smooth scrolling
- **Professional Color Scheme**: Blue primary color with clean typography
- **Modern UI**: Gradient backgrounds, card-based layouts, interactive elements

### 🛠 Technical Implementation

- **Pure HTML5**: Semantic markup for accessibility
- **CSS3**:
  - CSS Grid and Flexbox for layouts
  - CSS Custom Properties for theming
  - Responsive design with mobile-first approach
  - Smooth transitions and animations
- **Vanilla JavaScript**:
  - Mobile navigation toggle
  - Smooth scroll behavior
  - Active navigation highlighting
  - Form validation and handling
  - Intersection Observer for scroll animations
  - Debounced scroll events for performance

### 📱 Responsive Breakpoints

- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: < 768px

## File Structure

```
Personal-Portfolio/
│
├── index.html                  # Main homepage
├── styles.css                  # Main stylesheet
├── script.js                   # JavaScript functionality
│
├── project-heat-sink.html      # Heat sink design project
├── project-suspension.html     # Suspension system project
├── project-gripper.html        # Robotic gripper project
├── project-aerospace.html      # Aerospace lightweighting project
├── project-medical.html        # Medical device project
├── project-hvac.html           # HVAC optimization project
│
└── README.md                   # This file
```

## Projects Featured

### 1. Advanced Heat Sink Design
High-performance computing thermal management solution
- **Key Achievement**: 28% thermal resistance improvement
- **Tools**: SolidWorks, ANSYS Fluent, MATLAB

### 2. Automotive Suspension System
Electric vehicle suspension optimization
- **Key Achievement**: 22% unsprung mass reduction
- **Tools**: CATIA, ANSYS Mechanical, MSC Adams

### 3. Industrial Robotic Gripper
Multi-purpose gripper for manufacturing automation
- **Key Achievement**: 99.8% success rate across 50+ part types
- **Tools**: SolidWorks, ANSYS, Python

### 4. Aerospace Component Lightweighting
Topology optimization for aircraft interior components
- **Key Achievement**: 42% weight reduction achieved
- **Tools**: CATIA, ANSYS, Altair OptiStruct

### 5. Medical Device Mechanism
Precision mechanism for minimally invasive surgery
- **Key Achievement**: FDA 510(k) clearance obtained
- **Tools**: SolidWorks, ANSYS, MATLAB

### 6. HVAC System Optimization
Energy efficiency improvement for commercial building
- **Key Achievement**: 32% energy consumption reduction
- **Tools**: ANSYS Fluent, EnergyPlus, AutoCAD

## Customization Guide

### Updating Personal Information

1. **Name and Title**: Edit the hero section in `index.html`
2. **About Me Content**: Update the about section with your background
3. **Contact Information**: Change email and LinkedIn URLs in contact section
4. **Projects**: Modify project cards and detail pages with your actual projects

### Changing Colors

Edit CSS custom properties in `styles.css`:

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --primary-dark: #1e40af;       /* Darker shade */
    --secondary-color: #475569;    /* Secondary elements */
    --text-primary: #0f172a;       /* Main text color */
    --text-secondary: #64748b;     /* Secondary text */
}
```

### Adding New Projects

1. Create a new project detail page (e.g., `project-name.html`)
2. Add a project card in the projects section of `index.html`
3. Link the card to your new detail page
4. Use existing project pages as templates

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Optimizations

- Debounced scroll event handlers
- Intersection Observer for efficient scroll animations
- Minimal external dependencies
- Optimized CSS with efficient selectors
- Progressive enhancement approach

## Accessibility Features

- Semantic HTML5 elements
- ARIA labels where appropriate
- Keyboard navigation support
- Proper heading hierarchy
- Focus states for interactive elements
- Alt text for images (when added)

## Future Enhancements

Potential additions to consider:

- [ ] Add actual project images
- [ ] Integrate with email service (EmailJS, Formspree)
- [ ] Add professional headshot photo
- [ ] Include downloadable resume/CV
- [ ] Add testimonials section
- [ ] Implement dark mode toggle
- [ ] Add blog/articles section
- [ ] Include certifications and awards
- [ ] Add analytics (Google Analytics)
- [ ] Optimize images and add lazy loading

## Deployment

This is a static website that can be deployed to:

- **GitHub Pages**: Push to GitHub and enable Pages
- **Netlify**: Drag and drop the folder or connect to Git
- **Vercel**: Import from Git repository
- **Traditional hosting**: Upload files via FTP

No build process or server-side code required.

## License

This portfolio template is free to use and modify for personal or commercial purposes.

## Contact

For questions or feedback about this portfolio:

- Email: john.smith@email.com
- LinkedIn: linkedin.com/in/johnsmith

---

**Note**: This is a template portfolio. Replace all placeholder content with your actual information, projects, and images.
