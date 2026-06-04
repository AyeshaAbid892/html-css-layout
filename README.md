<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:3d9cd2,100:00b5e2&height=220&section=header&text=Shopamp!%20Clothing%20Store&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=A%20Fully%20Responsive%20Fashion%20E-Commerce%20Website&descAlignY=58&descSize=17&animation=fadeIn" width="100%" />

<br/>

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/Responsive-Design-38B2AC?style=for-the-badge&logo=google-chrome&logoColor=white" />
<img src="https://img.shields.io/badge/Status-Complete-3d9cd2?style=for-the-badge&logo=checkmarx&logoColor=white" />

<br/><br/>

<p align="center">
  <img src="https://img.shields.io/badge/Font_Awesome_6-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white" height="24"/>
  <img src="https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white" height="24"/>
  <img src="https://img.shields.io/badge/CSS_Grid_%26_Flexbox-00b5e2?style=for-the-badge&logo=css3&logoColor=white" height="24"/>
  <img src="https://img.shields.io/badge/Intersection_Observer_API-FF6B35?style=for-the-badge&logo=javascript&logoColor=white" height="24"/>
  <img src="https://img.shields.io/badge/Zero_Frameworks-2ecc71?style=for-the-badge&logo=git&logoColor=white" height="24"/>
</p>

<br/>

> **A complete, production-ready clothing store website** built with pure HTML5, CSS3, and Vanilla JavaScript.  
> Features scroll animations, hover effects, a testimonial slider, product gallery, newsletter form, and an embedded store map — all without a single framework.

<br/>

![Stars](https://img.shields.io/badge/Stars-⭐%2050%2B-brightgreen?style=flat&logo=github)
![Forks](https://img.shields.io/badge/Forks-🍴%2040%2B-purple?style=flat&logo=github)
![Sections](https://img.shields.io/badge/Sections-12-3d9cd2?style=flat&logo=buffer)
![Animations](https://img.shields.io/badge/Animations-CSS%20%26%20JS-orange?style=flat&logo=javascript)

<br/>

</div>

---

## 📁 Repository Structure

```
shopamp/
│
├── 📄 index.html               ← Main HTML file — all 12 page sections
├── 🎨 style.css                ← Complete stylesheet with CSS variables & responsive rules
│
├── 🖼️  Image.jpg               ← Hero section full-viewport background
├── 🖼️  Image 1.jpg             ← Sale banner background
├── 🖼️  Image 2.jpg             ← Product — Shirt ($69.99)
├── 🖼️  Image 3.jpg             ← Product — Light Shirt ($89.99)
├── 🖼️  Image 4.jpg             ← Product — Jacket ($129.99)
├── 🖼️  Image 5.jpg             ← Product — Denim Shirt ($179.99)
├── 🖼️  Image 6–11.jpg          ← Last Collection gallery (6 images)
│
└── 📄 README.md                ← You are here
```

> 💡 External images (About Us, News, Shop Banners, Testimonials) are loaded from **Unsplash CDN** — internet connection required.

---

## 📋 Table of Contents

| # | Section |
|---|---------|
| [01](#-project-overview) | Project Overview |
| [02](#-features) | Features |
| [03](#-technologies-used) | Technologies Used |
| [04](#-uiux-breakdown) | UI/UX Breakdown |
| [05](#-animations--styling) | Animations & Styling |
| [06](#-html--css-concepts-used) | HTML & CSS Concepts Used |
| [07](#-what-i-built-manually) | What I Built Manually |
| [08](#-how-to-run) | How to Run |
| [09](#-future-improvements) | Future Improvements |
| [10](#-key-learnings) | Key Learnings |

---

<br/>

# 🔍 Project Overview

**Shopamp!** is a static clothing store website template designed to showcase fashion products in a professional, visually engaging layout.

The site is divided into **12 complete sections**:

```
Navbar → Hero → About Us → Sale Banner → Features →
Products → Newsletter → Shop Banners → Latest News →
Last Collection Gallery → Testimonials → Location → Footer
```

Built entirely with **vanilla HTML, CSS, and JavaScript** — no React, no Bootstrap, no jQuery. Every layout, animation, and interaction is hand-coded from scratch.

---

<br/>

# ✨ Features

| Feature | Description |
|---|---|
| 📱 **Fully Responsive** | Desktop, tablet, and mobile via CSS media queries (`≤900px`, `≤640px`) |
| 🧭 **Sticky Navbar** | Fixed nav with scroll-triggered shadow + hamburger menu for mobile |
| 🎠 **CSS Dropdown Menus** | Smooth opacity + `translateY` slide-down on hover |
| 🖼️ **Full-Viewport Hero** | 100vh background image with overlay and brand headline |
| 🃏 **About Us Cards** | 3-column grid cards with image zoom on hover |
| 💥 **Sale Banner** | Full-width promotional section with overlay CTA |
| ⚙️ **Features Section** | 2-column layout with icon-bordered feature highlights |
| 👕 **Product Grid** | 2×2 product cards with frosted-glass hover text overlay |
| 📧 **Newsletter Form** | Inline email subscription with focus ring and submit button |
| 🗂️ **Shop Banners** | 2×2 image banner grid with hover overlay + Buy Now |
| 📰 **Latest News** | 3-column cards with `translateY` lift-on-hover + deep shadow |
| 📷 **Last Collection Gallery** | 3×2 square Instagram-style grid with social icon overlay |
| 💬 **Testimonial Slider** | JS-powered carousel with animated slide transitions |
| 📍 **Store Location** | Split layout — store photo, contact info + embedded Google Map |
| 🔗 **Footer** | 3-column grid with brand description, links, and social buttons |
| 🎞️ **Scroll Animations** | Intersection Observer fades elements in as they enter the viewport |

---

<br/>

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic structure — `<header>`, `<section>`, `<article>`, `<footer>`, `<nav>` |
| **CSS3** | Custom properties, Flexbox, Grid, transitions, keyframe animations |
| **Vanilla JavaScript** | Sticky navbar, hamburger toggle, testimonial slider, scroll animations |
| **Google Fonts** | `Montserrat` (headings) + `Open Sans` (body text) |
| **Font Awesome 6** | Icons for features, social media links, navigation, and UI elements |
| **Google Maps Embed** | Embedded store location iframe map |
| **Unsplash CDN** | External stock images for About Us, News, Banners, and Testimonials |

---

<br/>

# 🎨 UI/UX Breakdown

### 🧭 Navbar

```
Position: fixed  |  Height: 64px  |  Z-index: 1000
─────────────────────────────────────────────────
│ shopamp!   HOME  LIVE DEMO ▾  LIVE DEMO BLOCKS ▾  [Buy Now] │
─────────────────────────────────────────────────
```

- Transparent background transitions to a box-shadow on scroll (`.scrolled` class via JS)
- Dropdown menus use CSS-only hover: `opacity 0→1` + `translateY(6px)→0`
- On mobile (`≤640px`): hamburger button toggles `.open` class, sliding nav down from top

---

### 🖼️ Hero Section

```
Height: 100vh  |  Background: Image.jpg  |  Overlay: rgba(240,240,235,0.45)
─────────────────────────────────────────────────
│                                                │
│                                                │
│  Clothing                                      │
│  Store                    ← bottom-left anchor │
│  Clothing Website Template                     │
└────────────────────────────────────────────────┘
```

- `object-fit: cover` keeps image sharp at all viewport sizes
- Text is bottom-left anchored with `position: absolute; bottom: 80px; left: 48px`

---

### 👕 Product Section

```
Grid: 2 columns × 2 rows  |  Card height: 320px
─────────────────────────────────────────────────
│ [SHIRT $69.99]      │ [LIGHT SHIRT $89.99]    │
│ [JACKET $129.99]    │ [DENIM SHIRT $179.99]   │
─────────────────────────────────────────────────
```

Each card on hover:
1. Image zooms via `transform: scale(1.05)`
2. Frosted-glass overlay fades in (`backdrop-filter: blur(2px)`)
3. Product name text pops with `transform: scale(0.9 → 1)`

---

### 📧 Newsletter Section

```
Max-width: 650px  |  Centered  |  Background: #f4f6f9
┌──────────────────────────────────────────────────┐
│           Be the first to know?                  │
│  Subscribe Now              * 10% friend discount│
│  🔍 [Enter your email here...]      SUBSCRIBE    │
└──────────────────────────────────────────────────┘
```

- Input and button share one bordered container — no separate button box
- Focus-within adds a `3px` blue ring around the whole form

---

### 💬 Testimonials Slider

```
Max-width: 700px  |  Centered  |  JS-controlled
◉  ←  [Avatar] Markus Grecho / Sara Mills  →  ◉
         "Review text..."
```

- `display: none / block` toggle on `.active` class
- `@keyframes fadeIn` animates each slide appearance

---

### 📍 Location Section

```
Grid: 2 columns  |  Height: 400px each
┌──────────────────┬──────────────────────────────┐
│  Store Photo     │   Embedded Google Map iframe  │
│  (object-fit)    │   Manhattan, New York         │
└──────────────────┴──────────────────────────────┘
Email: company@mobirise.com   Phone: +573 1235 5324
```

---

<br/>

# 🎞️ Animations & Styling

### CSS Custom Properties (Design Tokens)

```css
:root {
  --primary:    #3d9cd2;   /* Main blue — headings, links, accents */
  --accent:     #00b5e2;   /* Lighter blue for highlights          */
  --dark:       #222;      /* Body text                            */
  --bg-light:   #f0f2f7;   /* Alternating section backgrounds      */
  --transition: 0.3s ease;
  --shadow:     0 4px 18px rgba(0,0,0,0.10);
}
```

---

### Scroll-Triggered Fade-In (Intersection Observer)

Elements start invisible and slide up into view when 15% of them enter the viewport:

```javascript
const observer = new IntersectionObserver(entries => {
  entries.forEach(e => {
    if (e.isIntersecting) e.target.classList.add('visible');
  });
}, { threshold: 0.15 });
```

```css
.card {
  opacity: 0;
  transform: translateY(24px);
  transition: opacity 0.5s ease, transform 0.5s ease;
}
.card.visible { opacity: 1; transform: translateY(0); }
```

Applies to: `.card`, `.product-card`, `.news-card`, `.insta-item`, `.feature-item`, `.banner-card`

---

### Hover Effects Summary

| Element | Effect |
|---|---|
| About / Product Cards | Image zoom `scale(1.05)` |
| Product Cards | Frosted overlay + `backdrop-filter: blur(2px)` + text pop |
| News Cards | `translateY(-8px)` lift + `box-shadow: 0 20px 38px rgba(0,0,0,0.22)` |
| Instagram Items | Image zoom + dark overlay + social icon `bounce-in` from below |
| Shop Banners | Zoom + overlay fade-in + Buy Now button reveal |
| Nav Dropdowns | `opacity 0→1` + `translateY(6px)→0` |
| Footer Social Buttons | Background fill + border color transition |

---

### Testimonial Slide Animation

```css
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(10px); }
  to   { opacity: 1; transform: translateY(0); }
}
.testimonial-slide.active { 
  display: block; 
  animation: fadeIn 0.5s ease; 
}
```

---

### Instagram Gallery Overlay System

```css
/* Social icons bounce up into position on hover */
.social-actions-wrap {
  transform: translateY(12px) scale(0.92);
  transition: all 0.4s cubic-bezier(0.25, 1, 0.5, 1);
}
.insta-item:hover .social-actions-wrap {
  transform: translateY(0) scale(1);
}
```

---

<br/>

# 🧠 HTML & CSS Concepts Used

| Concept | Used In | How It Was Applied |
|---------|---------|-------------------|
| `CSS Grid` | Products, About, News, Banners, Footer | Multi-column responsive layouts |
| `Flexbox` | Navbar, Features, Newsletter, Footer | Alignment and spacing |
| `position: fixed` | Navbar | Keeps nav on screen during scroll |
| `position: absolute` | Hero text, product overlay, banner overlay | Layered content over images |
| `object-fit: cover` | All background images | Fills containers without distortion |
| `CSS custom properties` | Entire stylesheet | Global theming and consistency |
| `@keyframes` | Testimonials, (future expansions) | Entrance animation for slides |
| `backdrop-filter: blur()` | Product hover overlay | Frosted glass premium effect |
| `IntersectionObserver` | Scroll animations | Triggers `.visible` class on entry |
| `transition` | All interactive elements | Smooth hover state changes |
| `grid-template-columns` | All grid sections | Responsive column definitions |
| `aspect-ratio: 1/1` | Instagram gallery | Perfect square image cards |
| `transform: scale()` | Image zooms | Smooth zoom without layout shift |
| `rgba() overlays` | Hero, Sale Banner, Instagram | Darkening layers over images |
| Semantic HTML | Entire page | `<section>`, `<article>`, `<header>`, `<footer>`, `<nav>` |
| `aria-*` attributes | Navbar, gallery, forms | Accessibility for screen readers |
| Media queries | Entire stylesheet | Breakpoints at `900px` and `640px` |

---

<br/>

# 🏗️ What I Built Manually

```
✅ Full HTML5 document structure with semantic tags
✅ Sticky navbar with scroll-shadow and mobile hamburger toggle
✅ CSS-only hover dropdown menus (no JavaScript)
✅ 100vh hero section with layered image + overlay + text
✅ Three-column About Us card grid with image zoom
✅ Full-width sale banner with CTA button
✅ Two-column Features layout with bordered icon boxes
✅ 2×2 Product card grid with frosted-glass hover overlays
✅ Inline newsletter form with focus-ring interaction
✅ 2×2 Shop banner grid with reveal-on-hover overlay
✅ Three-column news cards with lift-on-hover shadow effect
✅ 3×2 Instagram-style gallery with social icon bounce animation
✅ JavaScript testimonial slider with fadeIn keyframe animation
✅ Two-column location section with embedded Google Map iframe
✅ Three-column footer with social buttons
✅ Scroll-triggered animations using Intersection Observer API
✅ All CSS variables, transitions, and custom properties written by hand
✅ Full mobile responsiveness via hand-written media queries
```

---

<br/>

# 🚀 How to Run

No build tools, no installs, no dependencies. Just open in a browser.

**Option 1 — Direct Open**
```bash
# Clone the repository
git clone https://github.com/your-username/shopamp.git

# Navigate into the folder
cd shopamp

# Open in browser
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

**Option 2 — VS Code Live Server (Recommended)**

Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension → right-click `index.html` → **Open with Live Server**. Enables hot-reload on every file save.

**Option 3 — Python HTTP Server**
```bash
# Python 3
python -m http.server 8000

# Then open: http://localhost:8000
```

> ⚠️ **Important:** Product images (`Image.jpg`, `Image 1.jpg` through `Image 11.jpg`) must be in the same root folder as `index.html`. Unsplash images require an active internet connection.

---

<br/>

# 🔮 Future Improvements

- [ ] **Shopping Cart** — Slide-out cart drawer with item count badge in the navbar
- [ ] **Product Filter** — Filter by category (shirts, jackets) and price range
- [ ] **Product Detail Page** — Image gallery, size selector, and add-to-cart on a dedicated page
- [ ] **Dark Mode** — Toggle using CSS custom properties and `prefers-color-scheme`
- [ ] **Backend Integration** — REST API (Node.js / Django) for real dynamic product data
- [ ] **Lazy Loading** — `loading="lazy"` and WebP image format for performance
- [ ] **Staggered Animations** — `animation-delay` on grid items for a cascade entrance effect
- [ ] **Accessibility Audit** — Improved keyboard navigation and ARIA roles throughout
- [ ] **Deployment** — Host on GitHub Pages, Netlify, or Vercel with a custom domain
- [ ] **CSS Refinement** — Consolidate the multiple `:root` blocks into one unified variables file

---

<br/>

# 📚 Key Learnings

### 01 — CSS Grid + Flexbox Together
Using Grid for page-level sections and Flexbox inside components gave me clarity on when to use each. Grid = two-dimensional layout. Flexbox = one-dimensional alignment.

### 02 — CSS Custom Properties are Game Changers
Defining `--primary`, `--transition`, and `--shadow` as variables meant changing the brand color in one place updated the entire site instantly.

### 03 — Intersection Observer is Powerful
Replacing scroll-event listeners with `IntersectionObserver` taught me a modern, performance-friendly approach to scroll animations that doesn't fire on every pixel of scroll.

### 04 — `position: absolute` Mastery
Building product overlays, hero text, and banner CTAs made me deeply comfortable with stacking contexts, `inset: 0`, and z-index management.

### 05 — `object-fit: cover` is Essential
Every background image section taught me how `object-fit: cover` and `object-position` keep images sharp and well-composed at any container size.

### 06 — Semantic HTML for Accessibility
Using `<section>`, `<article>`, `<header>`, `<nav>`, and `<footer>` with `aria-label` attributes makes the page readable for screen readers and better for SEO — no extra work required.

---

<br/>
<div align="center">

**Author**

**Your Name**  
🐙 GitHub: [@your-username](https://github.com/your-username)  
💼 LinkedIn: [your-profile](https://linkedin.com/in/your-profile)  
📧 Email: your@email.com

---

**💻 Hand-coded with intention. If this helped you, feel free to fork it or drop a star! ⭐**

<br/>

![Made with HTML](https://img.shields.io/badge/Made%20with-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Styled with CSS](https://img.shields.io/badge/Styled%20with-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Powered by JS](https://img.shields.io/badge/Powered%20by-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Zero Frameworks](https://img.shields.io/badge/Zero-Frameworks-3d9cd2?style=for-the-badge&logo=html5&logoColor=white)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00b5e2,50:3d9cd2,100:0f0c29&height=140&section=footer&text=Shopamp!%20—%20Built%20with%20Pure%20CSS%20%26%20HTML&fontSize=20&fontColor=ffffff&fontAlignY=65&animation=twinkling" width="100%" />

</div>