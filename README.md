# Aaron Paddy - Personal Portfolio

A modern, responsive personal portfolio website showcasing my skills, projects, and experience as a Computer Science student and software developer.

## Features

- **Responsive Design**: Optimized for all devices and screen sizes
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Mobile Navigation**: Intuitive navigation with mobile-first approach
- **Contact Form**: Functional contact form integrated with Formspree
- **Skills Showcase**: Interactive skills section with technology icons
- **Project Portfolio**: Detailed project cards with GitHub links
- **Professional About Section**: Comprehensive background and experience

## Technologies Used

- HTML5 & CSS3
- JavaScript (ES6+)
- Bootstrap 5
- Bootstrap Icons
- AOS (Animate On Scroll)
- Typed.js for dynamic text
- Formspree for contact form handling

## Setup and Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd portfolio-website
   ```

2. **Open locally**
   - Option 1: Double-click `index.html`
   - Option 2: Use a local server:
     ```bash
     python3 -m http.server 8000
     ```
     Then visit `http://localhost:8000`

3. **Customize content**
   - Update personal information in `index.html`
   - Replace profile image (`assets/img/my-profile-img.jpg`)
   - Modify projects, skills, and contact information

## Deployment

This portfolio is designed for easy deployment to static hosting services:

### Netlify (Recommended)
1. Connect your GitHub repository to Netlify
2. Automatic deployments on every push
3. Custom domain support available

### GitHub Pages
1. Enable GitHub Pages in repository settings
2. Select source branch
3. Access via `username.github.io/repository-name`

### Vercel
1. Import project from GitHub
2. Automatic deployments
3. Excellent performance optimization

## Project Structure

```
portfolio-website/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── main.css         # Custom styles
│   ├── js/
│   │   └── main.js          # JavaScript functionality
│   ├── img/
│   │   ├── my-profile-img.jpg
│   │   └── hero-bg-aaron.jpg
│   └── vendor/             # Third-party libraries
├── README.md
└── ...
```

## Contact Form

The contact form is integrated with Formspree for reliable email delivery. No backend server required.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- Optimized images and assets
- Lazy loading for better performance
- Minified CSS and JavaScript
- Responsive image handling

## Customization

### Personal Information
Edit the following sections in `index.html`:
- Hero section (name, titles, typed text)
- About section (biography, experience)
- Skills section (technologies and tools)
- Projects section (portfolio items)
- Contact section (email, location, opportunities)

### Styling
Modify `assets/css/main.css` for:
- Color schemes
- Typography
- Layout adjustments
- Animation effects

### Adding Projects
Follow the existing project card structure:
```html
<div class="col-lg-4 col-md-6 portfolio-item">
  <!-- Project content -->
</div>
```

## License

This project is open source and available under the MIT License.

## Contact

For questions or collaboration opportunities:
- Email: aaronpaddy4@gmail.com
- Open to: Internships, Open Source, Research & Collaborative Projects