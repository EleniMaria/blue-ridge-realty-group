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

## 🎨 Design System

### Color Palette
- **Navy**: `#0D2F4F` - Primary brand color
- **Blue**: `#1E4F7A` - Secondary
- **Evergreen**: `#2E5E3E` - Accent
- **Copper**: `#B9794C` - Highlight
- **Paper**: `#FBFAF7` - Background
- **Ink**: `#1B2A2F` - Text

### Typography
- **Headings**: Playfair Display (serif) - 500, 600, 700 weights
- **Body**: Lato (sans-serif) - 400, 700, 900 weights

### Spacing & Components
- Container max-width: 1180px
- Border radius: 4px
- Box shadow: `0 18px 40px -22px rgba(13, 47, 79, 0.35)`

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
