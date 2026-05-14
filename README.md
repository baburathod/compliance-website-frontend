# CompliGuard — Professional Compliance Solutions Frontend

A pixel-perfect, fully responsive static frontend website built from a provided design. This project was developed as a frontend internship assignment demonstrating expertise in creating visually striking, scalable, and responsive web interfaces without relying on heavy frameworks.

**🔗 Live Demo:** [https://compliance-website-frontend.vercel.app/](https://compliance-website-frontend.vercel.app/)

## 🚀 Project Overview

The **CompliGuard** website is a modern, professional web interface for a compliance solutions provider. It features dynamic layouts, engaging micro-animations, and a highly polished UI. 

### Key Highlights & QA Polish:
- **Pixel-Perfect UI:** Accurately matches design spacing, typography, and visual hierarchy.
- **Fully Responsive:** Adapts seamlessly across desktop, tablet, and mobile devices (down to 375px) without breaking layouts or horizontal scrolling.
- **Premium Visual Polish:** Features crisp font antialiasing (`-webkit-font-smoothing`), buttery-smooth hover transitions (`transform: translateX`), and premium soft layering shadows.
- **Accessibility & UX Fixes:** Includes strict mobile background scroll-locking when the mobile menu is active, preventing layout jitter.
- **Clean Architecture:** Semantic HTML5, structured CSS with CSS Variables, and modular Vanilla JS for interactivity.
- **Asset Integration:** Utilizes all provided custom assets (PNGs, floating vectors, custom checkmarks, and icons).

---

## 🛠️ Tech Stack & Implementation Details

- **HTML5:** Semantic structure (`<header>`, `<main>`, `<section>`, `<footer>`).
- **CSS3:** 
  - Flexbox and CSS Grid for complex, responsive section layouts.
  - CSS Variables (`:root`) for maintaining a consistent design system (colors, typography, spacing).
  - Custom utility classes (`.container`, `.grid-2`, `.btn`) for scalable development.
  - Avoided inline styles and external CSS frameworks (e.g., no Bootstrap or Tailwind).
- **JavaScript (Vanilla):**
  - Minimal, clean JS for DOM manipulation.
  - Features: Mobile hamburger menu toggle, active section scroll spy, FAQ accordion logic, and contact form submission simulation.
- **Typography:** `Nunito` (via Google Fonts) with precise font-weight matching.

---

## 📂 Folder Structure

```
project/
├── index.html       # Main HTML document containing all sections
├── css/
│   └── style.css    # Global styles, variables, components, and media queries
├── js/
│   └── script.js    # Interactivity (nav toggle, accordion, scroll spy)
├── assets/
│   ├── images/      # Provided image assets (banners, vectors, icons)
│   └── icons/       # Additional icon assets
└── README.md        # Project documentation
```

---

## 📐 Responsive Breakpoints

The layout has been manually tested and optimized for the following breakpoints to ensure a stable layout during resizing:

- **1400px** ✅ (Ultra-wide screens)
- **1280px** ✅ (Standard desktop)
- **1024px** ✅ (Laptops / Landscape tablets)
- **768px** ✅ (Portrait tablets)
- **576px** ✅ (Large mobile phones)
- **375px** ✅ (Small mobile phones)

---

## 🧩 Sections Included

1. **Navbar:** Sticky behavior on scroll, seamless active state highlighting, responsive mobile hamburger menu using `Menu.png`.
2. **Hero Section:** Engaging headline with custom `underline-Vector.png` highlight, CTA buttons, statistics, and floating vectors (`Vector1.png`, `Vector2.png`) around the `Banner-Image.png`.
3. **About / Why Compliance Matters:** 2-column grid layout with custom feature icons (`Risk-Protection.png`, `Regulatory-Clarity.png`, `Hassle-Free-Filings-Clarity.png`).
4. **Our Services:** 3-card grid with hover effects and smooth transitions.
5. **Pricing:** 3-tier pricing table highlighting the "Most Popular" plan. Features custom checkmark icons (`check-sign.png`).
6. **FAQ:** Interactive accordion with smooth height transitions.
7. **Contact:** Grid layout with contact details and a fully styled contact form.
8. **Footer:** Clean 4-column layout linking to internal sections.

---

## 📦 Deployment Instructions

This is a static frontend project that requires zero build steps. It is production-ready and can be deployed instantly.

**To deploy on Vercel / Netlify / GitHub Pages:**
1. Drag and drop the `project/` folder directly into the deployment dashboard.
2. The site will be live instantly.

**To run locally:**
1. Open the `project` folder.
2. Double-click `index.html` to open it in any modern web browser.
3. Alternatively, use a local server extension (like VSCode Live Server) for hot-reloading.
