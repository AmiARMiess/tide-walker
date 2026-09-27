# 🌊 Abyssal Tide-Walker - Dota 2 Workshop Landing Page

A dark, oceanic-themed promotional landing page designed for the "Abyssal Tide-Walker" Juggernaut Immortal set submission. Features an interactive ability showcase with particle effect previews, parallax hero animations, and scroll-triggered fade-ins. Built with zero dependencies using vanilla HTML5, CSS3, and JavaScript.

<img width="1349" height="3214" alt="image" src="https://github.com/user-attachments/assets/2702cb63-e197-4f03-9bfb-caa3395cdabd" />

## ✨ Key Features

-   **🗡️ Interactive Ability Showcase:** Dedicated grid layout highlighting reimagined spells (Blade Fury → Whirlpool, Healing Ward → Coral) with custom icons and descriptions.
-   **✨ Parallax Hero Animation:** The Trench-Cleaver weapon floats and responds to mouse movement for an immersive deep-sea feel.
-   **⚡ Zero Dependencies:** No React, Vue, Tailwind, or build tools required. Pure semantic HTML5, custom CSS variables, and ES6+ JavaScript.
-   **👁️ Scroll Animations:** Elements gracefully fade in using the native `IntersectionObserver` API for buttery-smooth 60fps performance.
-   **📱 Fully Responsive:** Mobile-first design that adapts seamlessly from 4K monitors down to mobile devices.
-   **🔧 Highly Customizable:** All colors, fonts, and spacing are controlled via CSS custom properties at the top of `style.css`.

## 🛠️ Tech Stack

| Technology | Usage |
| :--- | :--- |
| **HTML5** | Semantic structure, accessibility, and SEO-friendly markup |
| **CSS3** | Custom properties, Flexbox/Grid, keyframe animations, responsive queries |
| **JavaScript (ES6+)** | DOM manipulation, Intersection Observer, parallax logic, event listeners |
| **Phosphor Icons** | Lightweight, consistent SVG icon library for UI elements |
| **Cinzel & Inter Fonts** | Cinzel for Dota-esque headings, Inter for clean body text readability |

##  Getting Started

This project has **no build step**. You can run it immediately without installing Node.js, npm, or any package managers.

### Clone the Repository

```bash
git clone https://github.com/AmiARMiess/tide-walker.git
cd tide-walker
```

### Customize Your Brand

All theme colors and typography are managed via CSS variables. Edit style.css:

```css
:root {
    --bg-dark: #050a14;        /* Deep ocean background */
    --primary: #0ea5e9;        /* Main accent color */
    --accent-cyan: #00ffff;    /* Bioluminescent glow */
    --accent-gold: #c5a059;    /* Tarnished gold details */
    --font-heading: 'Cinzel', serif; /* Dota-style heading font */
}
```

## 📂 Project Structure

```text
tide-walker/
├── index.html      # Main markup, semantic sections, and content
├── style.css       # Global styles, CSS variables, animations, responsive queries
├── script.js       # Parallax logic, scroll observer, mobile nav toggle
└── README.md       # Documentation
```
