# JAI - Jamnagar Agro Industries

> Building trust and delivering quality since 2014

## 📋 Overview

Jamnagar Agro Industries (JAI) is a leading manufacturer, supplier, and exporter of premium-quality agricultural products including spices, pulses, oilseeds, and other agro commodities. Based in Jamnagar, Gujarat – a hub for India's finest agricultural produce – we are committed to delivering freshness, purity, and unmatched quality to customers in domestic and international markets.

## 🌟 Key Features

- **11+ Years of Excellence** in agricultural product processing
- **₹33+ Crore Annual Revenue**
- **100+ Trusted Clients** across domestic and international markets
- State-of-the-art processing facilities
- Premium quality spices and agricultural products
- Export capabilities through [JAI Exports](https://jai-exports.com/)

## 🚀 Quick Start

### Prerequisites

Before you begin, ensure you have:
- A modern web browser (Chrome 90+, Firefox 88+, Safari 14+, or Edge 90+)
- A code editor (VS Code, Sublime Text, or similar) - *optional for development*
- Git installed (for version control) - *optional*
- A local web server (Python, Node.js, or PHP) - *optional but recommended*

### Setup Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/abhishekkalme/JAI-Jamnagar-Agro-Industries.git
   cd JAI-Jamnagar-Agro-Industries
   ```

2. **Open the Project**
   - For quick preview: Simply open `index.html` in your browser
   - For development: Use a local server (see options below)

3. **Start a Local Development Server** *(Recommended)*

   **Option A: Using Python**
   ```bash
   # Python 3.x
   python -m http.server 8000
   
   # Python 2.x
   python -m SimpleHTTPServer 8000
   ```

   **Option B: Using Node.js**
   ```bash
   # Install http-server globally (one-time)
   npm install -g http-server
   
   # Start server
   http-server -p 8000
   
   # Or use npx (no installation needed)
   npx http-server -p 8000
   ```

   **Option C: Using PHP**
   ```bash
   php -S localhost:8000
   ```

   **Option D: Using VS Code Live Server**
   - Install "Live Server" extension in VS Code
   - Right-click on `index.html` and select "Open with Live Server"

4. **Access the Website**
   - Open your browser and navigate to: `http://localhost:8000`
   - The homepage should load automatically

5. **Explore the Site**
   - Navigate through different sections using the menu
   - Test responsive design by resizing your browser window
   - Check all product pages, about sections, and contact forms

### Project Assumptions

This project is built with the following assumptions:

#### Technical Assumptions
- **No Build Process**: This is a static HTML/CSS/JavaScript website with no build step required
- **No Backend**: All forms are configured for client-side validation; backend integration needed for production
- **Asset Paths**: All asset paths are relative and should work when served from any directory
- **Browser Support**: Assumes modern browser features (ES6+, CSS Grid, Flexbox)
- **No Database**: Content is hardcoded in HTML files; CMS integration would require refactoring

#### Content Assumptions
- **Product Information**: Product details and pricing are placeholders and should be updated with actual data
- **Contact Forms**: Form submissions currently use placeholder endpoints (`assets/mail/contact.php`)
- **Images**: Some images use placeholder paths and should be replaced with actual product images
- **Social Media Links**: Social media links in header/footer point to `#` and need actual URLs
- **External Links**: Export link points to `https://jai-exports.com/` (verify this is correct)

#### Design Assumptions
- **Responsive Design**: Optimized for desktop, tablet, and mobile viewports
- **Accessibility**: Basic accessibility features included but may need WCAG 2.1 AA compliance review
- **Performance**: Images should be optimized for web before deployment
- **SEO**: Basic meta tags included; comprehensive SEO audit recommended before launch

#### Deployment Assumptions
- **Static Hosting**: Can be deployed to any static hosting service (GitHub Pages, Netlify, Vercel, etc.)
- **HTTPS**: Production deployment should use HTTPS for security
- **CDN**: Consider using a CDN for faster asset delivery in production
- **Domain**: Custom domain configuration needed for production

## 🏗️ Project Structure

```
JAI/
├── index.html                 # Main homepage
├── style.css                  # Custom styles
├── About-us/                  # Company information pages
│   ├── About-Us.html
│   ├── Our-History.html
│   ├── Our-Presence.html
│   ├── Mission-Vision-Values.html
│   ├── Infrastructure.html
│   ├── Certificates.html
│   ├── Company-Financials.html
│   └── Company-Financials/    # Financial details
├── products/                  # Product catalog pages
│   ├── spices.html
│   ├── spices/                # Individual spice product pages
│   ├── agarbatti.html
│   ├── agarbatti/             # Individual agarbatti product pages
│   └── products.html
├── services/                  # Service pages
│   ├── brands.html
│   └── manufacturing.html
├── contact/                   # Contact and inquiry pages
│   ├── become-partner.html
│   ├── enquiry.html
│   └── work-with-us.html
├── organic-farm-shop/         # Organic farm and shop sections
├── assets/                    # Static assets
│   ├── css/                   # Stylesheets
│   ├── js/                    # JavaScript files
│   └── img/                   # Images
└── .vscode/                   # VS Code configuration
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Installation

1. **Clone or download the repository**
   ```bash
   git clone <repository-url>
   cd JAI
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser, or
   - Use a local development server:

   **Using Python:**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```

   **Using Node.js (http-server):**
   ```bash
   npx http-server -p 8000
   ```

   **Using PHP:**
   ```bash
   php -S localhost:8000
   ```

3. **Access the website**
   - Open your browser and navigate to `http://localhost:8000`

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Styling and animations
- **JavaScript** - Interactive functionality
- **Bootstrap** - Responsive grid system
- **Font Awesome** - Icons
- **Swiper.js** - Carousels and sliders
- **jQuery** - DOM manipulation

## 📦 Key Dependencies

- Bootstrap 5.x
- Font Awesome
- Themify Icons
- Elegant Icons
- Swiper Bundle
- Magnific Popup
- Animate.css
- ValidNavs

## 🎨 Features

### Homepage
- Hero banner with image carousel
- Company overview and mission
- Key statistics and achievements
- Featured products showcase
- Product carousel
- Testimonials section
- Contact form

### Product Pages
- **Spices**: Ajwain, Fennel, Cumin, Sesame Seeds, and more
- **Agarbatti**: Incense products
- Complete product catalog

### About Us
- Company profile and history
- Geographic presence
- Mission, vision, and values
- Infrastructure details
- Certifications and quality standards
- Financial information and projections

### Services
- **Brands**: SKP Raja Rani and Parampara
- **Manufacturing**: White labeling and quality assurance
- **Wholesale Supplies**: Bulk product distribution

### Contact & Partnerships
- Product inquiry forms
- Supplier/Distributor partnership opportunities
- Media contact information

## 📱 Responsive Design

The website is fully responsive and optimized for:
- Desktop (1920px and above)
- Laptop (1024px - 1919px)
- Tablet (768px - 1023px)
- Mobile (320px - 767px)

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 📞 Contact Information

- **Location**: Jamnagar, Gujarat, India
- **Phone**: +91 92654 00092
- **Website**: [JAI Exports](https://jai-exports.com/)

## 🤝 Contributing

If you're working on this project:

1. Create a feature branch
2. Make your changes
3. Test thoroughly across different browsers
4. Submit for review

## 📄 License

© 2014-2026 Jamnagar Agro Industries. All rights reserved.

## 🔧 Development Notes

### File Naming Conventions
- Use kebab-case for HTML files (e.g., `company-profile.html`)
- Use camelCase for JavaScript files
- Use lowercase for CSS files

### Code Standards
- Maintain consistent indentation (4 spaces)
- Comment complex sections
- Keep HTML semantic
- Optimize images before adding to assets

### Asset Management
- Images should be optimized for web
- Use appropriate image formats (WebP, PNG, JPG)
- Maintain aspect ratios for consistency

## 🐛 Known Issues

None currently reported.

## 📝 Changelog

### Version 1.0.0 (Current)
- Initial website launch
- Complete product catalog
- Responsive design implementation
- Multi-page navigation structure
- Contact and inquiry forms

# ⏱️ Development Time Tracking

**Task Assigned:** 30 January 2026, 23:19  
**Deadline:** 2 February 2026  

---

## Project Summary

This task involved updating and stabilizing an existing website, focusing on content updates, layout consistency, navigation fixes, and final quality checks.

---

## Time Breakdown

| Area | Time Spent | Details |
|------|-----------|--------|
| **Layout & Structure Updates** | ~6 hours | Header/footer standardization, minor layout cleanup |
| **Content Updates** | ~6 hours | Company info, financials, product content |
| **Navigation & Link Fixes** | ~4 hours | Menu restructuring, broken links |
| **Responsive Adjustments** | ~4 hours | Mobile fixes and cross-browser testing |
| **Testing & Final Cleanup** | ~3–4 hours | QA checks, UI fixes |
| **Documentation & Repo Setup** | ~1–2 hours | Git setup, README, `.gitignore` |
| **Total Time** | **~24–26 hours** | Enhancements on an existing website |

---

## Key Work Completed

- Fixed broken links on the homepage (banners, carousel, footer)
- Standardized header and footer across all pages
- Reworked navigation structure
- Updated company and financial information
- Initialized repository and added documentation
- Performed final testing and cleanup

---

## Maintenance Notes

- Minor content updates: ~1–2 hours per month
- Bug fixes as needed
- Image optimization when required
- SEO improvements handled gradually


---

**Tagline**: *हर गृहीणीका अपना* (Every Homemaker's Own)

For more information, visit our [export website](https://jai-exports.com/) or contact us directly.

