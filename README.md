# CV Website

## Project Information

This project is a personal CV website developed as part of a web programming assignment. The website presents academic, technical, and professional information in a clean and responsive layout using modern web standards.

---

## Student Information

| Field           | Details                      |
| --------------- | ---------------------------- |
| **Name**        | Nayab Shahbaz                |
| **Roll Number** | 23L-3008                     |
| **Assignment**  | Web Programming - CV Website |

---

## Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Responsive layout and styling
- **JavaScript** - Dynamic theme toggle and interactivity

---

## Live Website

🔗 **Website URL:** [https://YOUR-VERCEL-LINK.vercel.app](https://YOUR-VERCEL-LINK.vercel.app)

---

## Overview

A modern, responsive Curriculum Vitae website showcasing professional presentation of academic qualifications, technical skills, project portfolio, and work experience. The application features a professional layout with dark/light mode toggle, smooth animations, and accessibility considerations. This project demonstrates front-end web development skills including responsive design, theme management, and semantic HTML.

---

## Features

### 🎨 **Responsive Design**

- Mobile-first approach using CSS Flexbox
- Adaptive layout for all screen sizes (mobile, tablet, desktop)
- Maintains readability and usability across devices

### 🌓 **Theme Toggle**

- Light and dark mode implementation
- User preference persistence using local storage
- Smooth color transitions between themes
- WCAG-compliant contrast ratios

### ✨ **Animations & Interactions**

- Smooth scroll behavior
- CSS transitions for interactive elements
- Hover effects on links and buttons
- Fade-in animations on page load

### ♿ **Accessibility Features**

- Semantic HTML structure
- Skip-to-content link for keyboard navigation
- ARIA labels for interactive elements
- Proper heading hierarchy
- Color contrast compliance

### 📱 **Contact Section**

- Direct email and phone contact links
- Social media integration (LinkedIn, GitHub)
- Location information
- Download CV functionality

---

## Project Structure

```
CV_NayabShahbaz/
├── index.html                 # Main CV page structure
├── css/
│   └── style.css             # Styling with CSS variables and theme support
├── images/
│   ├── profile.jpeg          # Profile photograph
│   └── NAYAB-SHAHBAZ-CV.pdf  # Downloadable CV document
├── README.md                 # Project documentation
└── .git/                     # Version control
```

---

## Installation & Usage

### Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No server or build tools required

### Setup

1. Clone or download the project directory
2. Open `index.html` in a web browser
3. No installation dependencies needed

### Running Locally

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx http-server

# Or simply open index.html directly in your browser
```

---

## Key Sections

### Header

- Professional profile section with name and current affiliation
- Contact information grid with icons
- Quick navigation menu
- Profile photograph
- Theme toggle button
- CV download link

### Main Content Areas

- **About Me** - Personal introduction
- **Education** - Academic background and qualifications
- **Skills** - Technical and professional competencies
- **Projects** - Portfolio of completed work
- **Experience** - Professional background
- **Contact** - Direct communication methods

---

## CSS Architecture

### Color Variables

The design uses CSS custom properties (variables) for consistent theming:

```css
:root[data-theme="light"] {
  --bg: #f3f5f7;
  --paper: #ffffff;
  --ink: #0e1b23;
  --muted: #5b6b77;
}

:root[data-theme="dark"] {
  --bg: #0b1419;
  --paper: #0f1e25;
  --ink: #e7eef4;
  --muted: rgba(231, 238, 244, 0.72);
}
```

### Layout System

- **Flexbox** for flexible, responsive layouts
- **CSS Grid** for structured content
- **Media queries** for responsive breakpoints
- **Backdrop filters** for modern UI effects

---

## JavaScript Functionality

### Theme Management

- Detects system theme preference
- Stores user selection in local storage
- Provides manual toggle control
- Applies smooth color transitions

### Key Features

- DOM event listeners for interactivity
- Local storage API for persistence
- Accessible button controls
- Data attributes for theme management

---

## Browser Compatibility

| Browser | Support | Notes           |
| ------- | ------- | --------------- |
| Chrome  | ✅ Full | Latest versions |
| Firefox | ✅ Full | Latest versions |
| Safari  | ✅ Full | iOS 12+         |
| Edge    | ✅ Full | Chromium-based  |

---

## Accessibility Compliance

- ✅ Semantic HTML markup
- ✅ Keyboard navigation support
- ✅ ARIA labels on interactive elements
- ✅ Skip-to-content link
- ✅ Sufficient color contrast ratios
- ✅ Responsive text sizing
- ✅ Alt text for images

---

## Performance Considerations

- Lightweight CSS with no external dependencies
- Optimized image sizes
- Efficient flexbox layouts
- Minimal JavaScript footprint
- Fast load times on all devices

---

## Customization Guide

### Changing Colors

Edit CSS variables in `style.css`:

```css
:root[data-theme="light"] {
  --ink: #0e1b23; /* Text color */
  --bg: #f3f5f7; /* Background */
  --paper: #ffffff; /* Card background */
}
```

### Updating Content

1. Open `index.html` in a text editor
2. Modify content within sections
3. Save changes
4. Refresh browser

### Adding Sections

1. Add new HTML section with appropriate ID
2. Update navigation links
3. Style with existing CSS classes
4. Adjust layout as needed

---

## Contact Information

**Nayab Shahbaz**

- 📧 Email: nayab.shahbaz003@gmail.com
- 📞 Phone: +92 334-1272765
- 📍 Location: Lahore, Pakistan
- 🔗 LinkedIn: [linkedin.com/in/nayab-shahbaz-0281b5319/](https://linkedin.com/in/nayab-shahbaz-0281b5319/)
- 🐙 GitHub: [github.com/NayabShahbaz](https://github.com/NayabShahbaz)

---

## Assignment Requirements Met

- ✅ HTML5 semantic markup
- ✅ CSS3 Flexbox layout
- ✅ JavaScript interactivity
- ✅ Responsive design (mobile, tablet, desktop)
- ✅ Dark/Light theme toggle
- ✅ Accessibility features (ARIA, semantic HTML, keyboard navigation)
- ✅ Professional presentation
- ✅ Complete CV information
- ✅ Contact section with multiple methods

---

## Version History

| Version | Date          | Changes                            |
| ------- | ------------- | ---------------------------------- |
| 1.0     | February 2026 | Initial release with core features |

---

## License

This project is provided as educational material and personal portfolio work.

---

**Last Updated:** February 2026  
**Status:** Complete and Production-Ready
