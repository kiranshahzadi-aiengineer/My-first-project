# Alfalah Rice Traders Landing Page

Single-page responsive website for Alfalah Rice Traders SMC Private Limited, a premium rice supplier and exporter. Showcases products, quality standards, and includes contact form for quote requests.

## File Structure
```
/
├── CLAUDE.md           # Project context and quick reference
└── doc/
    ├── index.html      # Main landing page (9 sections)
    ├── styles.css      # Complete stylesheet with CSS custom properties
    └── README.md       # Comprehensive documentation
```

## Documentation Reference

**doc/README.md** - Complete guide covering setup, customization, deployment, SEO, accessibility, troubleshooting, and maintenance (15KB, comprehensive)

**doc/index.html** - Single-page site with: Header, Hero, Stats, About, Products (6 rice varieties), Quality, Testimonials, Contact/CTA, Footer (20KB)

**doc/styles.css** - Modern CSS with custom properties, responsive design, accessibility features (16KB)

## Tech Stack

HTML5 (semantic) • CSS3 (custom properties, no frameworks) • Vanilla JS (smooth scroll, form handling) • Google Fonts (Inter, Playfair Display) • Unsplash images (replace for production)

## Design System

**Colors:** Primary #2d5016 (green), Accent #f4a259 (orange), Neutral grays
**Spacing:** 8px base unit (xs:8px → 3xl:96px)
**Breakpoints:** Mobile <640px, Tablet 641-767px, Desktop 768px+
**Typography:** Responsive with clamp(), mobile-first

## Key Features

• Fully responsive (mobile/tablet/desktop) • WCAG AA accessibility (skip links, ARIA, keyboard nav) • SEO optimized (meta tags, Open Graph) • Performance optimized (lazy loading, minimal JS) • Browser support: Chrome, Firefox, Safari, Edge 90+

## Important Notes

1. **Contact Form** - Demo mode (alert on submit). See README.md for integration options (Formspree, EmailJS, custom backend)
2. **Images** - Using Unsplash URLs. Replace with local images for production
3. **Contact Info** - Update placeholders at doc/index.html:302 and footer section
4. **No Build** - Static HTML/CSS, open doc/index.html directly in browser

## Quick Tasks

**Local dev:** `python -m http.server 8000` or `npx http-server`
**Update content:** Edit doc/index.html directly
**Change colors:** Edit CSS custom properties in doc/styles.css:4-16
**Full docs:** See doc/README.md
