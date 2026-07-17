# Blue Ridge Realty Group Website

A modern, responsive real estate website for Blue Ridge Realty Group showcasing Western North Carolina mountain properties and communities.

## 📋 Project Overview

This is a professional real estate website featuring:
- Property listings and detailed property pages
- Community guides (Asheville, etc.)
- Agent profiles and directory
- Blog with market insights
- Buying/selling resources
- Responsive design for all devices

## Target Audience

- Buyers looking for mountain/rural properties in Western NC
- Local sellers wanting to list properties
- Relocation clients from other states
- Second-home buyers interested in the region

## 🎨 Design System

### Color Palette

- **Navy**: `#0D2F4F` - Primary brand color (Headings, primary buttons, text)
- **Blue**: `#1E4F7A` - Secondary (text, accent borders)
- **Evergreen**: `#2E5E3E` - Accent (CTA sections, accent borders)
- **Copper**: `#B9794C` - Highlight (Tags, hover states, highlights)
- **Warmwhite** (`#F2F4F2`): Subtle backgrounds
- **Paper**: `#FBFAF7` - Background
- **Ink**: `#1B2A2F` - Text

### Typography
- **Headings**: Playfair Display (serif) - 500, 600, 700 weights
- **Body**: Lato (sans-serif) - 400, 700, 900 weights

### Spacing & Components
- Container max-width: 1180px
- Border radius: 4px
- Box shadow: `0 18px 40px -22px rgba(13, 47, 79, 0.35)`

## Design Pattern Usage

### Hero Sections
- **Homepage**: Search bar overlay on gradient background
- **Interior pages**: Community/topic imagery with gradient overlay
- **Property pages**: Gallery spotlight

### Card Components
- **Properties**: Image + price + address + stats
- **Communities**: Image + label overlay
- **Agents**: Avatar + bio + contact

### CTAs
- Primary: Solid navy button ("Contact", "Search")
- Secondary: Ghost outline ("View All", "Learn More")
- Tertiary: Light background on dark sections



## 📄 Key Pages

### Homepage (`index.html`)
- Hero section with search bar
- Featured properties grid
- Why choose us pillars
- Communities carousel
- Team showcase
- Testimonials
- CTA sections

### Property Detail (`property-detail.html`)
- Full property gallery
- Quick stats (beds, baths, sqft)
- Feature checklist
- Mortgage calculator
- Agent contact card
- Similar properties
- Location map

### Blog (`blog.html`, `blog-nc-market-update.html`)
- Featured post spotlight
- Blog grid with filtering
- Author bios
- Related articles
- Newsletter signup

### Community Guide (`community-asheville.html`)
- Hero with community imagery
- Lifestyle overview
- Market snapshot with statistics
- Featured listings in area
- Map

### Agent Profile (`agent-desmond-hale.html`)
- Agent hero card
- Bio and expertise areas
- Market specialties
- Contact form
- Active listings grid

## 🔧 Technical Features

- **Responsive Design**: Mobile-first approach with breakpoints at 600px, 760px, 820px, 900px, 920px, 960px
- **Smooth Scrolling**: HTML `scroll-behavior: smooth`
- **SVG Graphics**: Vector-based illustrations for properties, communities, and UI elements
- **Base64 Logo**: Logo embedded in HTML as base64 image data
- **Mobile Navigation**: Hamburger menu toggle
- **Intersection Observer**: Lazy-load animations for reveal elements

## 📱 Responsive Breakpoints

```css
Mobile: < 520px
Tablet: 520px - 760px
Desktop: 760px - 920px
Wide Desktop: > 920px
```
## Responsive Behavior

### Desktop (> 920px)
- 3-column grids for properties/blog
- 4-column for team
- Full navigation menu
- Sidebars visible

### Tablet (760px - 920px)
- 2-column grids
- Sidebar moves below content
- Navigation adjusts

### Mobile (< 760px)
- 1-column layouts
- Hamburger menu
- Stacked sections
- Optimized touch targets

## Interaction Patterns

- **Hover states**: Cards lift with shadow increase
- **Navigation**: Underline animation on hover
- **Forms**: Focus states with border color change
- **Buttons**: Color/background swap on hover
- **Mobile menu**: Slide-down animation

## Future Enhancement Priorities

1. **Backend Integration**: Property database, CMS for blog
2. **Search & Filter**: Dynamic property filtering
3. **Contact Forms**: Email backend integration
4. **Authentication**: Agent login for listings
5. **Mobile App**: Responsive property search
6. **Map Integration**: Interactive map with listings
7. **Live Chat**: Customer support widget
8. **Analytics**: Google Analytics integration
