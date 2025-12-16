# Senior SQA Engineer Portfolio Website

A modern, responsive portfolio website for a Senior Software Quality Assurance Engineer. Built with vanilla HTML, CSS, and JavaScript, featuring a clean design and smooth user experience.

## Features

- **Fully Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Sections Included**:
  - Hero section with introduction
  - About section with experience statistics
  - Skills showcase with categorized expertise
  - Professional experience timeline
  - Featured projects portfolio
  - Contact form and information
- **Interactive Elements**:
  - Smooth scrolling navigation
  - Mobile hamburger menu
  - Scroll-to-top button
  - Active section highlighting
  - Form validation

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript (ES6+)
- Font Awesome icons
- Google Fonts (Inter)

## Getting Started

### Prerequisites

No prerequisites needed! This is a static website that can be opened directly in any modern web browser.

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! The website is ready to use.

### Alternative: Using a Local Server

For the best experience, you can use a local development server:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js:**
```bash
npx http-server
```

Then open `http://localhost:8000` in your browser.

## Customization

### Personal Information

1. **Hero Section** (`index.html`):
   - Update the name in `.hero-title .name`
   - Modify the subtitle and description

2. **About Section**:
   - Edit the about text content
   - Update statistics (years of experience, projects, etc.)

3. **Skills Section**:
   - Add or remove skill tags in each category
   - Modify skill categories as needed

4. **Experience Section**:
   - Update job titles, company names, and dates
   - Edit job descriptions and achievements

5. **Projects Section**:
   - Add your own projects
   - Update project descriptions and technologies
   - Add links to your GitHub repositories

6. **Contact Section**:
   - Update email, phone, and location information
   - Modify social media links
   - Update the contact form action if you have a backend

### Styling

1. **Colors** (`styles.css`):
   - Modify CSS variables in `:root` to change the color scheme
   - Primary color: `--primary-color`
   - Text colors: `--text-dark`, `--text-light`
   - Background colors: `--bg-light`, `--bg-white`

2. **Fonts**:
   - Change the Google Fonts import in `index.html`
   - Update `font-family` in `styles.css`

### Contact Form

The contact form currently shows an alert on submission. To make it functional:

1. Set up a backend service (e.g., Formspree, EmailJS, or your own server)
2. Update the form action in `index.html` or modify the form handler in `script.js`

Example with EmailJS:
```javascript
// In script.js
contactForm.addEventListener('submit', async (e) => {
    e.preventDefault();
    // Add your EmailJS or API call here
});
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## File Structure

```
muntasir-portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## License

This project is open source and available for personal use. Feel free to modify and customize it for your own portfolio.

## Credits

- Icons: [Font Awesome](https://fontawesome.com/)
- Fonts: [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)

---

**Note:** Remember to update all placeholder content with your actual information before publishing your portfolio!

