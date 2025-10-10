# Infotech - Professional Resume Services Website

A pixel-perfect conversion of a Figma design into a static HTML/CSS website. This project features a modern, responsive design for a professional resume services company.

## 📋 Project Overview

This website showcases Infotech's professional resume writing services with:
- Hero section with call-to-action buttons
- Statistics and rating cards
- Four service offerings with detailed cards
- Fully responsive design for desktop, tablet, and mobile

## 🎨 Design Specifications

### Desktop Base Design
- **Width**: 1440px
- **Total Height**: 1683px
- **Header**: 100px height
- **Hero Section**: 909px height
- **Features Section**: 774px height

### Color Palette
- **Primary Color**: `#FA1239` (Brand Red)
- **Gradient Background**: `linear-gradient(261.18deg, #FFE7EB -0.46%, #FFBFCA 100.67%)`
- **Text Primary**: `#000000` (Black)
- **Text Secondary**: `#595959`, `#666666` (Gray shades)
- **White**: `#FFFFFF`
- **Accent Green**: `#1CB098` (Rating)
- **Accent Gold**: `#FFAB00` (Stars)

### Typography
- **Font Family**: Figtree (Primary), Inter (Rating score)
- **Weights**: 400 (Regular), 500 (Medium), 600 (Semibold), 700 (Bold), 800 (Extrabold)

#### Font Sizes (Pixel Perfect)
- Hero Heading: 64px / line-height: 78px
- Section Title: 44px / line-height: 55px
- Card Title: 20px / line-height: 30px
- Body Text: 16-18px / line-height: 28-34px
- Navigation: 18px / line-height: 22px
- Rating Score: 64px / line-height: 77px
- Stats Number: 30px / line-height: 36px

## 📁 File Structure

```
infotech/
├── index.html          # Main HTML structure
├── styles.css          # Complete CSS styling with responsive design
└── README.md          # Project documentation
```

## 🚀 Features

### 1. Navigation Header
- Fixed 100px height
- White background
- Logo with brand colors
- 5 navigation links (Home, Services, Testimonials, Pricing, FAQs)
- Primary CTA button

### 2. Hero Section
- Beautiful gradient background (#FFE7EB to #FFBFCA)
- Compelling headline and description
- Dual CTA buttons (Outline and Filled)
- Decorative circles and lines
- Placeholder for hero image
- Floating stats card (260+ Online Resume Created)
- Rating card with 5-star display (4.9 Instructor Rating)

### 3. Features Section
- "What you Get" badge
- Compelling section headline
- 4 service cards with:
  - Icon/illustration placeholder
  - Service title
  - Service description
  - Hover effects
  - Box shadows

### 4. Responsive Design
- **Desktop**: 1440px base width
- **Tablet**: 768px - 1024px (2-column card grid)
- **Mobile**: Below 767px (single column, stacked layout)
- **Small Mobile**: Below 480px (optimized typography)

## 🎯 Pixel-Perfect Implementation

All measurements match the Figma specifications exactly:
- ✅ Font sizes as specified (14px = 14px, not 15px)
- ✅ Padding values exact (24px = 24px, not 20px)
- ✅ Line heights maintained
- ✅ Colors with exact hex codes
- ✅ Border radius values
- ✅ Box shadows with precise rgba values
- ✅ Gap and spacing measurements

## 💻 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Responsive Breakpoints

```css
/* Tablet */
@media screen and (max-width: 1024px) { }

/* Mobile */
@media screen and (max-width: 767px) { }

/* Small Mobile */
@media screen and (max-width: 480px) { }
```

## 🎨 CSS Architecture

The stylesheet is organized into clear sections:
1. Reset & Base Styles
2. Desktop Container
3. Header/Navigation
4. Buttons (Reusable)
5. Hero Section
6. Hero Image & Decorative Elements
7. Stats Card
8. Rating Card
9. Features Section
10. Feature Cards Grid
11. Responsive Design

## 🔧 Customization

### Changing Colors
Update the color variables in `styles.css`:
```css
/* Primary Brand Color */
background: #FA1239;

/* Gradient Background */
background: linear-gradient(261.18deg, #FFE7EB -0.46%, #FFBFCA 100.67%);
```

### Adding Real Images
Replace the placeholder elements with actual images:
```html
<!-- Replace illustration placeholders -->
<div class="illustration illustration-1">
    <img src="path/to/your/image.png" alt="Resume Service">
</div>
```

### Modifying Content
All text content is in `index.html` and can be easily edited:
- Update navigation links
- Change hero heading and description
- Modify service card titles and descriptions
- Update statistics and ratings

## 📝 Code Quality

- ✅ Clean, semantic HTML5
- ✅ Well-organized CSS with comments
- ✅ Consistent naming conventions
- ✅ No inline styles
- ✅ Maintainable code structure
- ✅ Responsive design patterns
- ✅ Cross-browser compatible

## 🚀 Getting Started

1. **Clone or Download** the project files
2. **Open `index.html`** in your web browser
3. **No build process required** - pure HTML/CSS

## 📦 Deployment

This is a static website and can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

Simply upload the HTML and CSS files to your hosting provider.

## 🔄 Future Enhancements

Potential improvements:
- [ ] Add actual images for illustrations
- [ ] Add smooth scroll navigation
- [ ] Implement contact form functionality
- [ ] Add animation effects (AOS, GSAP)
- [ ] Add more sections (testimonials, pricing, footer)
- [ ] Integrate with backend services
- [ ] Add accessibility improvements (ARIA labels)
- [ ] Performance optimization (lazy loading)

## 📄 License

This is a design implementation project. Please check with the original Figma design owner for usage rights.

## 👨‍💻 Development Notes

### Pixel-Perfect Approach
- All measurements converted exactly from Figma
- Used absolute positioning where specified in design
- Maintained exact font sizes and line heights
- Preserved gradient directions and color stops
- Implemented exact border radius values
- Matched shadow specifications (blur, spread, opacity)

### Responsive Strategy
- Desktop-first approach (1440px base)
- Graceful degradation for smaller screens
- Flexible layouts using flexbox
- Maintained visual hierarchy across breakpoints
- Optimized typography scaling
- Card grid adapts from 4 columns to 2 to 1

## 🐛 Known Limitations

- Illustrations use emoji placeholders (replace with actual images)
- Backdrop filter has limited browser support for rating card
- Student image is a placeholder gradient

## 📞 Support

For questions or issues with this implementation:
1. Check the CSS comments for specific styling details
2. Verify browser compatibility
3. Test responsive breakpoints at different screen sizes

---

**Built with ❤️ following pixel-perfect standards**