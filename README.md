# 🌍 AuraEscapes Agency - Premium Travel Platform

A stunning, glassmorphic travel agency landing page built as **Project 1** for DecodeLabs internship. Focuses on semantic HTML, external CSS, grid/flexbox layouts, and responsive design.

---

## 🎯 Project Overview

This project demonstrates a **static webpage design** with modern UI/UX principles including:
- Glassmorphism design language
- Semantic HTML structure
- CSS Grid & Flexbox mastery
- Accessible components

---

## ✅ Project Requirements Met

| Requirement | Status |
|-------------|--------|
| Semantic tags (`<header>`, `<main>`, `<footer>`) | ✅ |
| One `<h1>` per page | ✅ |
| External CSS only (no inline styles) | ✅ |
| DRY principle | ✅ |
| No IDs for styling | ✅ |
| Grid for macro page layout | ✅ |
| Flexbox for micro components | ✅ |
| Assets with explicit width/height | ✅ |

---

## ✨ Features

### Core Features
- 🏠 **Hero Section** - Main banner with call-to-action button
- 📦 **Packages Grid** - 4 premium travel packages with details
- 📍 **Destinations Grid** - Trending global locations
- ❤️ **Why Choose Us** - Key selling points
- 📝 **Travel Planner** - Interactive booking form
- 🗺️ **Global Itinerary Hub** - Interactive map with location nodes
- 📋 **Booking Section** - Simple travel booking form
- ⭐ **Testimonials** - Customer reviews with ratings
- 📞 **Footer** - Contact information and social links

### Design Features
- 🪟 **Glassmorphism Effect** - Modern blurred background cards
- ✨ **Ambient Orbs** - Floating light effects in background
- 🎨 **Gradient Elements** - Beautiful color transitions
- 🔘 **Animated Buttons** - Hover effects with transforms
- 📱 **Fully Responsive** - Works on all screen sizes

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Semantic page structure |
| CSS3 | Styling, Grid, Flexbox, Animations |
| Font Awesome 6.4.0 | Icons for visual enhancement |
| Google Fonts (fallback) | Typography |

---

## 🚀 How to Run

1. **Download or Clone** the repository
2. Make sure the `images/` folder is in the same directory as `index.html`
3. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari)
4. No build steps or dependencies required

---

## 📱 Responsive Breakpoints

| Breakpoint | Target Device |
|------------|---------------|
| 950px | Tablet Landscape |
| 900px | Tablet Portrait / Mobile |

---

## 🎨 Color Palette

| Color | Hex Code | Usage |
|-------|----------|-------|
| Primary Blue | `#38bdf8` | Accents, buttons, hover states |
| Dark Navy | `#0c131a` | Text shadows, overlays |
| Light Gray | `#cbd5e1` | Secondary text |
| White | `#ffffff` | Primary text |
| Gold | `#facc15` | Pricing, currency |
| Green | `#22c55e` | Status indicators |

---

## 🔧 Key CSS Components

### Glassmorphism Card
```css
.glass-card {
    background: rgba(255, 255, 255, 0.05);
    backdrop-filter: blur(16px) saturate(140%);
    border: 1px solid rgba(255, 255, 255, 0.12);
    border-radius: 14px;
}