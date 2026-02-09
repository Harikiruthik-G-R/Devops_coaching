# KEC × GUVI Collaboration Website

A modern, responsive website showcasing the strategic partnership between Kongu Engineering College (KEC) and GUVI coaching centre.

## 🎯 Features

- **Modern Design**: Vibrant gradients, smooth animations, and premium aesthetics
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scrolling, hover effects, and animated counters
- **Contact Form**: Functional form with validation and user feedback
- **SEO Optimized**: Proper meta tags, semantic HTML, and accessibility features

## 📁 Project Structure

```
GUVI/
├── index.html          # Main HTML file
├── styles.css          # Complete styling with animations
├── script.js           # Interactive functionality
└── README.md           # This file
```

## 🚀 Getting Started

### Option 1: Direct Browser Opening
Simply open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge)

### Option 2: Local Development Server
For the best experience, use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server -p 8000

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 📋 Sections

1. **Hero Section**: Eye-catching introduction with key statistics
2. **About Section**: Information about both KEC and GUVI
3. **Programs Section**: 6 comprehensive tech programs offered
4. **Benefits Section**: Key advantages of the collaboration
5. **Contact Section**: Interactive form for inquiries
6. **Footer**: Quick links and contact information

## 🎨 Design Highlights

- **Color Scheme**: 
  - KEC Blue: #1e40af
  - GUVI Cyan: #00d9ff
  - Accent Purple: #8b5cf6
  - Accent Pink: #ec4899

- **Typography**: 
  - Headings: Outfit (Google Fonts)
  - Body: Inter (Google Fonts)

- **Animations**:
  - Fade-in effects on scroll
  - Smooth hover transitions
  - Animated statistics counter
  - Parallax hero background

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript (ES6+)**: Interactive features and form handling
- **Google Fonts**: Professional typography

## 📱 Responsive Breakpoints

- Desktop: 1200px and above
- Tablet: 768px - 1199px
- Mobile: Below 768px

## ✨ Key Features

### Interactive Navigation
- Fixed navbar with scroll effect
- Mobile-friendly hamburger menu
- Smooth scroll to sections

### Form Validation
- Real-time input validation
- Email format checking
- Phone number validation
- Success/error notifications

### Performance Optimizations
- Lazy loading for images
- Intersection Observer for animations
- Optimized CSS and JavaScript
- Minimal external dependencies

## 🎓 Programs Offered

1. Full Stack Development (6 months)
2. Data Science & AI (8 months)
3. Cloud Computing & DevOps (5 months)
4. Mobile App Development (4 months)
5. Cybersecurity (6 months)
6. IoT & Embedded Systems (5 months)

## 📞 Contact Information

**KEC Campus**
- Address: Perundurai, Erode - 638060, Tamil Nadu, India
- Email: info@kec.edu
- Phone: +91 4294 226000

**GUVI**
- Email: support@guvi.in
- Phone: +91 44 4855 4555

## 🔧 Customization

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-kec: #1e40af;
    --primary-guvi: #00d9ff;
    /* ... other variables */
}
```

### Adding New Programs
Add a new program card in the `programs-grid` section of `index.html`

### Modifying Contact Form
Update the form fields in the contact section and corresponding JavaScript validation in `script.js`

## 📄 License

This project is created for educational purposes as part of the KEC-GUVI collaboration.

## 🤝 Contributing

For suggestions or improvements, please contact the development team.

---

**Built with ❤️ for KEC × GUVI Collaboration**
