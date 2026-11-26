# 🔘 BUTTONARIUM

> **A meticulously crafted specimen library of 122 copy-paste buttons.**  
> Pure HTML + CSS. Zero dependencies. No frameworks. No build steps. Just copy, paste, and ship.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-brightgreen?style=for-the-badge)](#)
[![Made by Khdxsohee](https://img.shields.io/badge/Made%20by-khdxsohee-blueviolet?style=for-the-badge)](https://github.com/khdxsohee)

---

## 📖 Table of Contents
1. [Introduction](#-introduction)
2. [Key Features](#-key-features)
3. [Quick Start (3 Steps)](#-quick-start)
4. [The 15 Button Families](#-the-15-button-families)
5. [Usage Examples](#-usage-examples)
6. [Customization](#-customization)
7. [Browser Support](#-browser-support)
8. [Contributing](#-contributing)
9. [License](#-license)
10. [Author](#-author)

---

## 🧪 Introduction

**Buttonarium** is a comprehensive, open-source UI specimen library featuring **122 unique button designs**. Built entirely with semantic HTML and modern CSS, it eliminates the need for heavy UI frameworks, JavaScript libraries, or complex build pipelines. 

Whether you need a subtle ghost button, a brutalist hard-shadow component, a glassmorphic pill, or a special FX glitch button, Buttonarium has a preserved, production-ready specimen waiting for you. Every button is designed to be accessible, responsive, and effortlessly integrated into any web project.

---

## ✨ Key Features

- 🧬 **122 Unique Specimens**: A massive variety of styles for every conceivable UI need.
- 🗂️ **15 Distinct Families**: Categorized logically (Solid, Neon, Brutalist, Glass, etc.) for easy browsing.
- ⚡ **Zero Dependencies**: No React, no Tailwind, no Bootstrap. Just pure, vanilla HTML & CSS.
- 📋 **One-Click Copy**: The built-in showcase allows you to copy the exact HTML of any button instantly.
- 🎨 **Inline SVG Icons**: Icon buttons come with lightweight, inline SVGs. No external icon font libraries required.
- ♿ **Accessible**: Built with proper `<button>` semantics, `:focus-visible` outlines, and `disabled` states.
- 📱 **Responsive**: Fluid typography and flexible layouts that adapt to any screen size.
- 🪶 **Lightweight**: The entire CSS kit is under a few kilobytes when minified.

---

## 🚀 Quick Start

Getting started with Buttonarium is as easy as 1-2-3. No `npm install` required.

### Step 1: Get the CSS
Copy the entire CSS block from the `<style id="kit-css">` tag in the repository, or download the `buttonarium.css` file. Link it in your project's `<head>`:
```html
<link rel="stylesheet" href="buttonarium.css">
```

### Step 2: Copy a Specimen
Visit the [live showcase](#) (or open `index.html` locally). Hover over any button specimen and click the yellow **COPY** button. The exact HTML is now in your clipboard.

### Step 3: Paste & Ship
Paste the HTML directly into your markup. Every button uses a base class `.bn` combined with a specific variant class.
```html
<button class="bn bn-solid-primary">Click Me</button>
```
*That’s it. You’re done.*

---

## 🗂️ The 15 Button Families

Buttonarium is organized into 15 distinct design families:

| # | Family | Count | Description |
|---|--------|-------|-------------|
| 01 | **Solid Essentials** | 12 | The workhorses. Flat fills, sharp hovers, ready for real UI (Primary, Success, Danger, etc.). |
| 02 | **Outline & Ghost** | 8 | All shape, no weight. Quieter siblings for secondary actions. |
| 03 | **Gradients** | 10 | Color in motion. From calm oceans to full fireworks, including animated rainbow rings. |
| 04 | **Soft Tonal** | 6 | Quiet tints for calm interfaces. Low volume, high polish. |
| 05 | **3D Press** | 8 | Push them, they push back. Satisfying tactile depth with hard shadows. |
| 06 | **Neumorph** | 4 | Soft plastic aesthetics, extruded from the page itself (Raised, Pressed, Convex). |
| 07 | **Glass** | 5 | Frosted panes using `backdrop-filter`. Looks best sitting on top of colorful backgrounds. |
| 08 | **Neon** | 7 | For dark rooms and loud ideas. Glowing borders, text shadows, and pulsing rings. |
| 09 | **Brutalist** | 8 | Concrete borders. Hard shadows. Zero apologies. Raw, high-contrast, and bold. |
| 10 | **Hover Motion** | 12 | Interactive delight. Underline slides, sweeps, shines, tilts, elastic pops, and orbital rings. |
| 11 | **With Icons** | 10 | Words plus pictures. Inline SVGs for Download, Cart, Heart, Play, Send, and more. |
| 12 | **Pills & Shapes** | 8 | Geometry class. Pills, squares, circles, squircles, tags, and arrow shapes. |
| 13 | **States** | 6 | The honest ones. Disabled, loading spinners, success confirmations, and error states. |
| 14 | **Social** | 8 | Brand colors baked in. GitHub, X (Twitter), YouTube, LinkedIn, Instagram, WhatsApp, Discord, Dribbble. |
| 15 | **Special FX** | 10 | The show-offs. Pulse, heartbeat, glitch, flow borders, typing dots, shimmer, 3D flip, and hue shifts. |

---

## 💻 Usage Examples

### Basic Solid Button
```html
<button class="bn bn-solid-primary">Primary Action</button>
```

### Button with Inline SVG Icon
```html
<button class="bn bn-ic-download">
  <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round">
    <path d="M12 3v12"/><path d="M7 11l5 5 5-5"/><path d="M5 21h14"/>
  </svg>
  Download
</button>
```

### Disabled / Loading States
```html
<!-- Disabled -->
<button class="bn bn-disabled-solid" disabled>Disabled</button>

<!-- Loading -->
<button class="bn bn-loading">Saving…</button>
```

### Brutalist Style
```html
<button class="bn bn-brut-yellow">DO IT</button>
```

---

## 🎨 Customization

Buttonarium is built with standard CSS, making it highly customizable. You can easily override variables or add your own utility classes.

### Changing the Font
The base `.bn` class uses `'IBM Plex Sans', sans-serif`. To use your project's font, simply override it:
```css
.bn {
  font-family: 'Your Custom Font', sans-serif !important;
}
```

### Creating Your Own Variant
You can extend the kit by adding your own CSS classes that build upon the `.bn` base:
```css
.bn-custom-purple {
  background: #8b5cf6;
  color: #ffffff;
}
.bn-custom-purple:hover {
  background: #7c3aed;
  transform: translateY(-2px);
  box-shadow: 0 10px 15px -3px rgba(139, 92, 246, 0.4);
}
```
```html
<button class="bn bn-custom-purple">My Custom Button</button>
```

---

## 🌐 Browser Support

Buttonarium relies on modern, widely-supported CSS features. 
- ✅ **Chrome, Edge, Firefox, Safari**: Full support.
- ⚠️ **Glassmorphism (`.bn-glass`)**: Requires `backdrop-filter` support (Safari requires the `-webkit-` prefix, which is included in the kit).
- ⚠️ **Special FX (`.bn-fx-glitch`, `.bn-fx-shimmer`)**: Uses CSS `clip-path` and `@keyframes`, supported in all modern browsers.

---

## 🤝 Contributing

Contributions, issues, and feature requests are highly welcome! If you have an idea for a new button specimen or find a bug:

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/AmazingButton`).
3. **Commit** your changes (`git commit -m 'Add some AmazingButton'`).
4. **Push** to the branch (`git push origin feature/AmazingButton`).
5. **Open** a Pull Request.

*Please ensure your CSS follows the existing naming convention (`.bn-[family]-[variant]`).*

---

## 📜 License

This project is licensed under the **MIT License**.  
You are free to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, even in commercial projects. No attribution is strictly required, but a star ⭐ on the repository is always appreciated!

---

## 👨‍💻 Author

Built with ❤️, 1 file, 0 frameworks, and too many `box-shadow`s by:

**Khdxsohee**  
[![GitHub](https://img.shields.io/badge/GitHub-khdxsohee-181717?style=for-the-badge&logo=github)](https://github.com/khdxsohee)

---

> *"Design is not just what it looks like and feels like. Design is how it works."* – Steve Jobs  
> **Buttonarium** makes sure it works beautifully, right out of the box. 🔘

--- 
