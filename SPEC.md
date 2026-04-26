# GreenArc Global Consultants & Contractors Ltd — Website Specification

## Concept & Vision

A refined, editorial website for GreenArc Global Consultants & Contractors Ltd — an indigenous Nigerian multi-disciplinary construction firm serving Nigeria. The design communicates professionalism, trust, and local expertise while maintaining international design standards. This is not just a construction website — it's a statement of capability and partnership in Nigeria's development.

## Company Information

**Legal Name:** GreenArc Global Consultants & Contractors Ltd

**Tagline:** Your Partner in Development

**Headquarters:** 19 Gwani Street, Wuse Zone 4, FCT, Abuja, Nigeria

**Phone:** +234 803 464 4524

**Email:** greenarcglobal@gmail.com

**Business Hours:** Monday - Friday, 8:00 AM - 5:00 PM

**Branches:**
- FCT-Abuja (Headquarters)
- Kano State (Branch Office)
- Kaduna State (Branch Office)

**Services:** Architecture, Urban Planning, Interior Design, Engineering (Civil/Structural/Mechanical/Electrical), Project Management, Construction/Contracting

## Design Language

### Aesthetic Direction
Refined minimalism meets architectural elegance. Inspired by luxury architectural magazines, Japanese minimalism, and Dieter Rams principles. The site feels premium, confident, and quietly impressive — not loud. It communicates "we understand quality" without being flashy.

### Color Palette
- **Black**: `#0a0a0a` (primary text, buttons)
- **White**: `#fafafa` (backgrounds)
- **Green**: `#006634` (accent — used sparingly like punctuation)
- **Green Light**: `#4d994d` (secondary accent)
- **Gray 100**: `#f5f5f5` (section backgrounds)
- **Gray 200**: `#e5e5e5` (borders)
- **Gray 400**: `#999999` (secondary text)
- **Gray 600**: `#666666` (body text)
- **Gray 800**: `#333333` (headings)

### Typography
- **Headlines**: Playfair Display (serif, elegant, editorial)
- **Body**: Inter (clean, professional, highly readable)
- **Numbers**: Playfair Display (for stat counters)
- **Labels**: Inter, 0.7rem, 0.2-0.3em letter-spacing, uppercase

### Spatial System
- Section padding: 8rem vertical (desktop), 5rem (mobile)
- Horizontal padding: 4rem (desktop), 1.5rem (mobile)
- Max content width: 1400px
- Grid gap: 1.5-2rem typical, 8rem between major sections

### Motion Philosophy
- **Entrance**: Elements fade up (opacity 0→1, translateY 20-40px→0)
- **Timing**: 0.6-0.8s duration, ease-out curves
- **Stagger**: 100-200ms between items
- **Hover**: Subtle, natural transitions (0.3-0.5s)
- **Counters**: Smooth count-up with easing when in viewport
- **Philosophy**: Motion should feel like physics — natural weight and momentum

### Visual Assets
- **Images**: High-quality Unsplash photos with subtle grayscale filter (20-30%), lifted on hover
- **Icons**: Minimal stroke icons (1.5px weight), simple line art
- **Decorative**: Almost none — let photography and typography speak
- **Accent line**: Single 60px green line under section headers

## Layout & Structure

### Navigation
- Fixed, transparent on hero, white with blur on scroll
- Logo: Custom SVG mark + Playfair Display wordmark + "Global" subtitle
- Links: 0.85rem, 500 weight, hover underline animation
- CTA: Solid black button, green on hover
- Mobile: Clean hamburger with full-screen slide menu

### Hero Section
- Full viewport height
- Two-column grid: text left, image right
- Text stack: small label → large serif headline → body → buttons
- Image: 85% width, subtle shadow, positioned to overlap
- Floating stat cards: "3 States Covered" and "100+ Projects"
- Scroll indicator: thin animated line at bottom center
- Animation: Staggered fade-up on load

### About Section
- Two-column: image left with green border accent, text right
- Image: Full height with grayscale filter, slight zoom on hover
- Text: Section label, serif title, body paragraphs, checkmarks
- Below fold: Four-column stat row (100 Projects, 50 Team, 3 States, 98% Satisfaction)

### Services Section
- Light gray background (#f5f5f5)
- 3x2 grid with 2px gaps (creates subtle grid lines)
- 6 Services: Architecture, Urban Planning, Interior Design, Engineering, Project Management, Construction
- Each card: large number, icon, title, description
- Interaction: Entire card inverts to black on hover

### Projects Section
- 12-column asymmetric grid (7+5, then 5+7)
- Projects located in FCT, Kano, and Kaduna
- Large images with grayscale → full color on hover
- Overlay: Gradient from bottom, category label, title, location
- Staggered scroll animation

### Branches Section (NEW)
- Dark background (inverted from white sections)
- 3-column grid for the three branch locations
- Each card: green icon, branch name, type (HQ/Branch), address
- Cards have green border on hover

### Why Choose Us Section
- 4-column grid with 1px gray dividers
- Roman numerals as large decorative numbers
- Cards invert to black on hover

### Testimonial Section
- Light gray background
- Large decorative quotation mark in green
- Centered, generous whitespace
- Generic client testimonial appropriate for the Nigerian market

### Contact Section
- Two-column: info left, form right
- Info: label, title, paragraphs, contact items with icon boxes
- Full contact details including phone, email, business hours
- Form: Clean white background, generous padding, subtle borders

### Footer
- Full black background
- 4-column grid: brand + social, Services links, Company links, Contact links
- Copyright with company name and address

## Features & Interactions

### Core Interactions
1. **Navigation scroll**: Transparent → white blur with shadow
2. **Scroll animations**: Elements fade up when entering viewport
3. **Counter animation**: Numbers count up smoothly
4. **Image hover**: Grayscale lifts, subtle zoom
5. **Service card hover**: Inverts to black (text and background)
6. **Branch card hover**: Green border appears
7. **Project hover**: Overlay fades in, image colors
8. **Form submit**: Button state feedback (sending → sent)
9. **Smooth scroll**: All anchor links

### States
- **Hover**: All interactive elements have clear hover states
- **Focus**: Visible focus rings for accessibility
- **Active**: Button press feedback
- **Loading**: Form submission state
- **Success**: Green confirmation on form submit

## Component Inventory

### Navigation
- Default: Transparent background, white text
- Scrolled: White background with blur, subtle shadow
- Links: White text (black when scrolled), green underline on hover
- CTA: White fill, green on hover

### Buttons
- Primary: Green fill, white text, arrow icon, black fill on hover
- Secondary: Transparent fill, white border, white fill on hover
- Hover: Arrow translates right 4px

### Cards
- Service: White bg, number + icon + title + desc, inverts on hover
- Project: Full image, gradient overlay, slides up on hover
- Branch: Dark bg, green icon, text centered, green border on hover
- Stat: Large number in serif, small label below

### Form Elements
- Input: White bg, gray border, green border on focus
- Textarea: Same styling, min-height 140px
- Submit: Full width, black fill, green on hover

### Section Headers
- Label: 0.7rem, uppercase, letter-spacing 0.2-0.3em, green color
- Title: Playfair Display, 2.5-3.5rem, weight 400
- Subtitle: Gray 600, max-width 500px, line-height 1.8
- Line: 60px green line below

## Technical Approach

- **Single HTML file** with embedded CSS and JavaScript
- **Fonts**: Google Fonts (Playfair Display, Inter)
- **Icons**: Inline SVG (Lucide-style, stroke-based)
- **No external dependencies** — fully self-contained
- **Responsive**: Mobile-first breakpoints at 1200px, 768px
- **Accessibility**: Respects prefers-reduced-motion, semantic HTML
- **Performance**: Minimal JS, CSS animations, optimized images
