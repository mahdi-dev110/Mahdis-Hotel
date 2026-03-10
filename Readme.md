
<!-- Banner -->
<div align="center">
  
  <h1>🏨 Mahdi's Hotel</h1>
  <p><em>A quiet kind of extraordinary</em></p>
  
  <!-- Badges -->
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/AOS-Animation-FF6B6B?style=for-the-badge" alt="AOS" />
  
  <br/>
  
  <img src="https://img.shields.io/badge/Status-Production%20Ready-success?style=flat-square" alt="Status" />
  <img src="https://img.shields.io/badge/Version-2.0.0-blue?style=flat-square" alt="Version" />
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=flat-square" alt="License" />
</div>

---

## ✨ Overview

**Mahdi's Hotel** is a luxury hotel landing page featuring a sophisticated dark theme with gold accents. Built with pure HTML, CSS, and vanilla JavaScript — no frameworks, no dependencies (except AOS for animations). The design emphasizes elegance, performance, and user experience.

> *"We've been doing this since 2000. We've gotten pretty good at it."*

---

## 🚀 Live Demo

**[View Live Site →](https://mahdishotel.com)** *(Deploy to your hosting)*

---

## 🎯 Key Features

| Feature | Description |
|---------|-------------|
| 🌓 **Dark/Light Mode** | Seamless theme switching with localStorage persistence |
| 📱 **Fully Responsive** | Optimized for mobile, tablet, and desktop |
| 🎨 **Modern UI/UX** | Glassmorphism effects, smooth animations, gold gradient accents |
| 🖼️ **Image Gallery** | Interactive lightbox with keyboard navigation |
| 🛏️ **Room Booking** | Functional booking modal with form validation |
| 💱 **Multi-Currency** | Real-time price conversion (USD, PKR, GBP, EUR) |
| ♿ **Accessibility** | ARIA labels, keyboard navigation, skip links |
| ⚡ **Performance** | Lazy loading, optimized assets, smooth scrolling |

---

## 🛠️ Tech Stack

```
Frontend:     HTML5, CSS3 (Custom Properties), Vanilla JavaScript
Animations:   AOS (Animate On Scroll), CSS Transitions
Icons:        SVG (Inline)
Fonts:        Cormorant Garamond (Headings), Lato (Body)
```

---

## 📂 Project Structure

```
mahdis-hotel/
├── 📄 index.html          # Main HTML file
├── 📁 assets/
│   ├── 🖼️ images/         # Hotel imagery (Unsplash)
│   └── 📜 README.md       # This file
└── 📄 manifest.json       # PWA manifest (embedded)
```

---

## 🎨 Design System

### Color Palette

| Token | Dark Mode | Light Mode | Usage |
|-------|-----------|------------|-------|
| **Primary** | `#B8860B` | `#B8860B` | Gold accents, CTAs |
| **Background** | `#0D0D0D` | `#FAFAFA` | Page background |
| **Surface** | `#1A1A1A` | `#FFFFFF` | Cards, modals |
| **Text** | `#F5F0E8` | `#1A1A1A` | Primary text |
| **Muted** | `#888888` | `#777777` | Secondary text |

### Typography

- **Headings:** Cormorant Garamond (Serif) — *Elegant, timeless*
- **Body:** Lato (Sans-serif) — *Clean, readable*

---

## ⚡ Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local server (recommended) for full functionality

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/mahdis-hotel.git

# Navigate to project
cd mahdis-hotel

# Open in browser (or use Live Server)
open index.html
```

### Development

```bash
# No build process required!
# Edit index.html directly
# Refresh browser to see changes
```

---

## 🎯 Core Sections

```
┌─────────────────────────────────────┐
│  🏠 Hero Section                    │
│  - Parallax background              │
│  - Booking widget                   │
│  - Animated text reveal             │
├─────────────────────────────────────┤
│  📊 Stats Counter                   │
│  - Animated number counting         │
│  - Intersection Observer triggered  │
├─────────────────────────────────────┤
│  🎁 Special Offers                  │
│  - Promotional cards                │
│  - Hover effects                    │
├─────────────────────────────────────┤
│  🛏️ Room Types                      │
│  - 3 tiers (Standard/Deluxe/Suite)  │
│  - Dynamic pricing                  │
│  - Currency converter               │
├─────────────────────────────────────┤
│  🏊 Amenities                       │
│  - 8 feature cards                  │
│  - Staggered animations             │
├─────────────────────────────────────┤
│  🖼️ Gallery                         │
│  - Masonry grid layout              │
│  - Lightbox modal                   │
│  - Keyboard navigation              │
├─────────────────────────────────────┤
│  ⭐ Testimonials                    │
│  - Auto-rotating carousel           │
│  - Pause on hover                   │
├─────────────────────────────────────┤
│  📞 Contact & Footer                │
│  - Functional contact form          │
│  - Embedded Google Maps             │
│  - Social links                     │
└─────────────────────────────────────┘
```

---

## 🌟 Highlights

### 🎭 Theme Toggle
```javascript
// Persistent dark/light mode
const theme = localStorage.getItem('theme') || 'dark';
document.documentElement.setAttribute('data-theme', theme);
```

### 💰 Currency Converter
```javascript
// Real-time conversion rates
const rates = { USD: 1, PKR: 278.5, GBP: 0.79, EUR: 0.92 };
// Updates all prices instantly
```

### 🖼️ Lightbox Gallery
- **Keyboard Support:** Arrow keys navigation, ESC to close
- **Touch Friendly:** Click to open/close
- **Smooth Transitions:** Scale and fade animations

### 📱 Mobile Navigation
- Slide-out drawer menu
- Overlay backdrop
- Focus trap for accessibility

---

## ♿ Accessibility Features

- ✅ Semantic HTML5 structure
- ✅ ARIA labels and roles
- ✅ Keyboard navigation support
- ✅ Skip-to-content link
- ✅ Focus visible indicators
- ✅ Reduced motion support (`prefers-reduced-motion`)
- ✅ Color contrast compliance (WCAG AA)

---

## 🚀 Performance Optimizations

| Technique | Implementation |
|-----------|---------------|
| **Lazy Loading** | `loading="lazy"` on images |
| **Will-Change** | GPU acceleration for parallax |
| **Debounced Events** | Scroll handlers optimized |
| **CSS Variables** | Efficient theme switching |
| **Minimal Dependencies** | Only AOS library loaded |

---

## 🐛 Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 90+ | ✅ Fully Supported |
| Firefox | 88+ | ✅ Fully Supported |
| Safari | 14+ | ✅ Fully Supported |
| Edge | 90+ | ✅ Fully Supported |
| IE11 | — | ❌ Not Supported |

---

## 📝 License

This project is licensed under the **MIT License** — feel free to use for personal or commercial projects.

```
MIT License

Copyright (c) 2025 Mahdi's Hotel

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software...
```

---

## 🙏 Credits

- **Images:** [Unsplash](https://unsplash.com) — Royalty-free photography
- **Icons:** Custom SVG icons
- **Fonts:** [Google Fonts](https://fonts.google.com) — Cormorant Garamond & Lato
- **Animations:** [AOS Library](https://michalsnik.github.io/aos/) — Animate On Scroll

---

## 📬 Contact

Have questions or want to collaborate?

- 📧 **Email:** [hello@mahdishotel.com](mailto:hello@mahdishotel.com)
- 🐦 **Twitter:** [@mahdishotel](https://twitter.com/mahdishotel)
- 📸 **Instagram:** [@mahdishotel](https://instagram.com/mahdishotel)

---

<div align="center">

**[⬆ Back to Top](#-overview)**

Made with 💛 and ☕ by Mahdi's Hotel Team

*Est. 2000 · New York*

</div>
```