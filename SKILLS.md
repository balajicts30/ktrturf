# KTRTURF - Technical Skills & Architecture

This document outlines the technical skills, stack, and concepts required to build and maintain the KTRTURF landing page. It is structured into three main categories: Design, Core Web Technologies, and Developer Workflow.

## 🎨 1. Design & UI Implementation
*   **Web Typography:** Integration of specialized Google Fonts (Inter, Space Grotesk, Orbitron) to establish a distinct, modern sports aesthetic.
*   **Vector Graphics (SVG):** Implementation of inline SVGs for resolution-independent, crisp icons that can be styled (e.g., stroke, fill) dynamically with CSS.
*   **Responsive Design & Constraints:** Utilizing native CSS features like `clamp()`, `minmax()`, and viewport units (`vw`, `vh`) to ensure the design fluidly adapts to any screen size without rigid breakpoints.
*   **Accessibility (a11y):** Integration of `@media (prefers-reduced-motion: reduce)` to respect user device preferences by minimizing or removing heavy animations automatically.
*   **Modern UI Effects:** Implementing glassmorphism effects using CSS properties like `backdrop-filter: blur(12px)` for the sticky navigation bar.

## 🌐 2. Core Web Technologies
*   **Advanced HTML5:**
    *   Semantic structuring of content (e.g., `<section>`, `<nav>`, `<footer>`).
    *   Proper configuration of SEO meta tags and Open Graph (`og:`) metadata for rich social media sharing previews.
*   **CSS3 (Modern Features):**
    *   **CSS Variables:** Extensive use of root custom properties for a robust and easily updatable theming system (colors, spacing, typography).
    *   **Advanced Layouts:** Mastery of **CSS Grid** and **Flexbox** for complex component positioning (e.g., auto-fitting sports cards).
    *   **Animations & Keyframes:** Complex background logic, including 3D perspective transformations (e.g., `perspective(1000px) rotateX(60deg)`) and smooth infinite glowing/pulsing animations.
*   **Vanilla JavaScript (ES6):**
    *   **Intersection Observer API:** Efficient, high-performance logic to trigger "scroll reveal" animations only when elements enter the user's viewport.
    *   **DOM Manipulation:** Toggling classes for the mobile hamburger menu and detecting scroll depth to update the navigation bar styling dynamically.
    *   **Smooth Scrolling:** Custom JavaScript fallbacks to calculate header heights and smoothly offset anchor links when clicked.

## 🛠️ 3. Developer Workflow & Tooling
*   **Zero-Build Architecture:** The project relies entirely on native HTML/CSS/JS without needing Node.js, Webpack, or external bundlers, ensuring immediate execution and maximum simplicity.
*   **Version Control (Git):** Managing source code, tracking changes, resolving merge conflicts, and utilizing branching strategies.
*   **Static Hosting Readiness:** Optimized structure that is instantly ready to be deployed to fast edge networks like GitHub Pages, Vercel, or Netlify with zero configuration.
