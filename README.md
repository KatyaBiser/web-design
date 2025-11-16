# Rehab from Vibe - Web Design Project

**Student Project** | Web Design Course 2025 | Created by Katya Biser

## Project Overview

"Rehab from Vibe" is a fictional rehabilitation center website designed to help developers break free from AI-assisted coding dependency (vibe-coding). This project was created as a student assignment to demonstrate mastery of HTML5 and CSS3 fundamentals without relying on frameworks or AI-generated code.

The website concept is intentionally ironic - it's about recovering from AI dependency, yet the project itself showcases what can be achieved through thoughtful, manual coding practices.

## Live Website

Open `html/index.html` in any modern web browser to view the website.

## Project Structure

```
web-design/
├── html/                   # All HTML pages
│   ├── index.html              # Homepage
│   ├── therapists.html         # Therapist listing page
│   ├── therapist-detail.html   # Individual therapist profile
│   ├── programs.html           # Program listing page
│   ├── program-detail.html     # Individual program details
│   ├── search-results.html     # Search results page
│   ├── contact.html           # Contact page with form
│   └── booking.html           # Booking/reservation form
├── css/
│   └── style.css         # Main stylesheet (839 lines)
├── images/
│   └── therapist-placeholder.jpg  # Placeholder image
└── README.md             # This file
```

## Technical Specifications

### HTML5 Features
- **Semantic Elements**: Extensive use of `<header>`, `<footer>`, `<main>`, `<nav>`, `<article>`, `<section>`, `<aside>`, `<time>`
- **Forms**: Multiple forms with proper `<label>`, `<input>`, `<textarea>`, `<select>` elements
- **Tables**: Semantic tables with `<thead>`, `<tbody>`, `<caption>` for schedule data
- **Accessibility**: ARIA labels, skip links, proper heading hierarchy
- **Valid HTML5**: No deprecated elements, proper DOCTYPE

### CSS Architecture
- **No Frameworks**: Pure CSS, no Bootstrap, Tailwind, or other frameworks
- **CSS Variables**: Extensive use of custom properties for maintainability
- **Mobile-First**: Responsive design starting from mobile breakpoints
- **CSS Grid**: Used for main layouts with 9+ grid items, some spanning multiple cells
- **Flexbox**: Used for component-level layouts and alignment
- **BEM Methodology**: Block-Element-Modifier naming convention for classes
- **File Size**: 839 lines of well-organized CSS (exceeds 400-line requirement)

### Accessibility (WCAG 2.0 AA)
- ✅ Keyboard navigation support
- ✅ Sufficient color contrast ratios
- ✅ Alt text for all meaningful images
- ✅ Semantic HTML structure
- ✅ Form labels properly associated with inputs
- ✅ Skip to main content link
- ✅ ARIA attributes where needed
- ✅ Screen reader friendly

### Responsive Design
- **Mobile**: 320px - 767px
- **Tablet**: 768px - 1023px
- **Desktop**: 1024px+

## Pages Overview

1. **Homepage** (`index.html`)
   - Hero banner with call-to-action
   - About section
   - Programs grid (9 items with CSS Grid)
   - Testimonials section

2. **Therapists** (`therapists.html`)
   - Grid of 8 therapist cards
   - Professional profiles

3. **Therapist Detail** (`therapist-detail.html`)
   - Full biography
   - Publications list
   - Credentials and approach

4. **Programs** (`programs.html`)
   - Complete program catalog
   - Duration and difficulty levels

5. **Program Detail** (`program-detail.html`)
   - Detailed curriculum
   - Weekly schedule table
   - Pricing and outcomes

6. **Search Results** (`search-results.html`)
   - Example search interface
   - Sample results for "accessibility"

7. **Contact** (`contact.html`)
   - Contact information
   - Contact form
   - Office hours table

8. **Booking** (`booking.html`)
   - Comprehensive booking form
   - Multiple fieldsets
   - Form validation

## Design Decisions

### Color Palette
- **Primary**: Medical blues (#2c7da0, #014f86, #61a5c2)
- **Secondary**: Calming greens (#52b788, #2d6a4f)
- **Accent**: Warning orange (#f48c06)
- **Neutrals**: Grays and whites

This palette was chosen to evoke a professional, medical/therapeutic environment while maintaining accessibility standards.

### Typography
- **Body**: System font stack for performance
- **Headings**: Georgia serif for authority and tradition
- **Sizes**: Responsive with clamp() and rem units

### Layout Philosophy
1. **Mobile-First**: All styles start mobile, enhanced for larger screens
2. **Progressive Enhancement**: Works without JavaScript
3. **Semantic Structure**: Meaningful HTML that works with assistive tech
4. **Performance**: Minimal CSS, no external dependencies

## Browser Compatibility

Tested and working in:
- Chrome 120+
- Firefox 121+
- Safari 17+
- Edge 120+

Requires a modern browser with CSS Grid and Custom Properties support.

## Accessibility Testing

This website has been designed to meet WCAG 2.0 Level AA standards:
- Color contrast ratios exceed 4.5:1 for normal text
- All interactive elements are keyboard accessible
- Focus indicators visible on all focusable elements
- Forms include proper labels and error hints
- Semantic HTML provides meaningful document structure

## Educational Purpose

This is a **student project** created for educational purposes to demonstrate:
- Understanding of semantic HTML5
- Mastery of modern CSS layout techniques
- Ability to create accessible, responsive designs
- Clean code organization and architecture
- Following web standards and best practices

**No AI was used to generate the core structure or styling.** While AI tools may have been consulted for syntax questions or best practices, all architectural decisions, design choices, and implementation were done manually to ensure deep understanding of the fundamentals.

## Future Enhancements

If this were a real project, these features could be added:
- JavaScript for interactive search
- Form validation and submission
- Image optimization and lazy loading
- Service worker for offline functionality
- Dark mode toggle
- Animated transitions
- Backend integration for booking system

## Credits

**Author**: Katya Biser
**Course**: Web Design Course 2025
**Concept**: Rehabilitation from AI-assisted coding dependency

## License

This is an educational project. All content is fictional and created for demonstration purposes only.

---

© 2025 Rehab from Vibe - Student Project
