# Little Fern Early Learning - Website Clone

A production-ready, self-contained HTML file that clones the design language and motion patterns of maximatherapy.com, adapted for a fictional daycare school with a warm, nature-inspired Scandi aesthetic.

## File Details

- **Filename:** `clone-maximatherapy.html`
- **Size:** 45KB
- **Lines:** 1,304
- **Format:** Single self-contained HTML file (HTML, CSS, and JavaScript all inline)

## Design Language

### Color Palette
- **Background:** Warm off-white cream (#F7F3EC)
- **Primary Accent:** Sage/forest green (#5B7B5D)
- **Secondary:** Warm terracotta (#C4724E)
- **Accent:** Soft gold/mustard (#D4A853)
- **Light Card Backgrounds:** #E8DFD0 (cream) and #D5E3D5 (sage light)
- **Text:** Dark charcoal (#2C2C2C)

### Typography
- **Display Font:** Google Font "Baloo 2" (bold, rounded, playful)
- **Body Font:** Google Font "DM Sans" (clean, modern)
- **Responsive sizing** using CSS clamp() for fluid scaling

## Page Structure (Maximatherapy Clone)

1. **Sticky Navigation Bar** - Pill-shaped with logo left, nav links + CTA right. Becomes fixed with background + shadow on scroll.

2. **Hero Section** - Full-width gradient background with floating CSS blob animations. Large display heading, subtitle, description, and dual CTAs. Animated staggered entrance on page load.

3. **Programme Cards Section** - Three stacked cards with slight rotation transforms (like scattered deck). Each card has different background gradient, icon, title, and description. Hover effect: straightens and lifts with shadow.

4. **Big Statement Section** - Centered display text on white background with decorative floating blob elements. Communicates core philosophy.

5. **About Section** - Split layout: left side has stacked large display typography ("The Early Years Matter Most"), right side has body text + placeholder image. Image has rotation transform on hover.

6. **Trust Signals / Stats** - Horizontal grid band on light sage background showing 4 key stats (licensed capacity, ERO rating, funding acceptance, hours).

7. **Getting Started / Process Section** - White card with two columns: left has heading + CTA button, right has 3 numbered steps with circular avatar icons and descriptions.

8. **Pricing Section** - Full-width sage green section with large display heading, pricing table grid, and note about subsidies.

9. **Testimonial Section** - Single card with quoted testimonial text and author attribution, left border accent.

10. **Footer** - Multi-column link grid, contact information, social media icons, logo, and legal text on dark background.

## Motion Patterns Implemented

- **Hero load animation:** Staggered fadeUp keyframes (0.1s, 0.2s, 0.3s, 0.4s delays)
- **Scroll reveals:** IntersectionObserver-based fade-up animations
- **Navbar scroll behavior:** Background/shadow added at 60px scroll threshold
- **Button hover:** translateY(-2px) + shadow elevation
- **Card hover:** translateY(-4px) + enhanced shadow, rotation reset
- **Floating elements:** Subtle infinite float animation (6-9s duration) on decorative blobs
- **Timing:** 0.6-0.8s durations with ease-out curves for warm, friendly feel
- **Smooth scroll:** Native scroll-behavior: smooth on html element

## Features

- **Fully responsive** - Mobile-first design with breakpoints at 768px and 1024px
- **Accessible** - Semantic HTML, proper heading hierarchy, focus states
- **No external libraries** - Pure vanilla JavaScript with IntersectionObserver API
- **CSS Custom Properties** - All colors, spacing, shadows defined as variables for easy theming
- **Performance optimized** - Single file = single HTTP request, minimal JavaScript
- **SEO friendly** - Proper semantic markup, meta tags, accessible alt text

## Content

### Navigation
Logo "Little Fern" (with 🌿 emoji) | Programmes | About | Pricing | Contact | CTA: "Book a Visit"

### Programme Rooms
1. **Pīwakawaka Room** (3 months – 2 years) - 1:3 ratio, gentle routines, sensory play
2. **Kererū Room** (2 – 3 years) - Art, music, water play, early social skills
3. **Kākāpō Room** (3 – 5 years) - Project-based learning, literacy, outdoor exploration

### Key Sections
- Core philosophy statement
- About the centre (founded 2019, Te Whāriki + nature-based curriculum)
- Trust signals (75 capacity, ERO rating, 20-hour ECE, extended hours)
- Enrollment process (3 simple steps)
- Transparent pricing by age group
- Parent testimonial
- Full footer with contact details

## Browser Compatibility

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Android)

## How to Use

1. Open `clone-maximatherapy.html` in any modern web browser
2. All styles and scripts are inline - no dependencies
3. Google Fonts are loaded via CDN link tags
4. All images pull from picsum.photos (placeholder service)
5. Fully self-contained and production-ready

## Customization

To customize:
1. Edit CSS Custom Properties in `:root` selector for colors/spacing
2. Update content in HTML sections (hero, about, pricing, etc.)
3. Replace placeholder image URL (picsum.photos) with real images
4. Modify contact details in footer
5. All animations can be adjusted by modifying `@keyframes` and transition durations

---

Created: March 30, 2026
Version: 1.0
Status: Production-ready
