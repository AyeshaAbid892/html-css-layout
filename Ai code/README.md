<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:ff6ec7,25:ff9a3c,50:f7df1e,75:3d9cd2,100:a855f7&height=240&section=header&text=🛍️%20Shopamp!&fontSize=72&fontColor=ffffff&fontAlignY=42&desc=Clothing%20Store%20Website%20%7C%20HTML5%20•%20CSS3%20•%20JavaScript&descAlignY=62&descSize=16&animation=fadeIn&stroke=ffffff&strokeWidth=1" width="100%" />

<br/>

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/Responsive-Design-38B2AC?style=for-the-badge&logo=google-chrome&logoColor=white" />
<img src="https://img.shields.io/badge/Status-Complete-a855f7?style=for-the-badge&logo=checkmarx&logoColor=white" />

<br/><br/>

<p align="center">
  <img src="https://img.shields.io/badge/Font_Awesome_6-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white" height="24"/>
  <img src="https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white" height="24"/>
  <img src="https://img.shields.io/badge/CSS_Grid_%26_Flexbox-ff6ec7?style=for-the-badge&logo=css3&logoColor=white" height="24"/>
  <img src="https://img.shields.io/badge/Intersection_Observer-FF6B35?style=for-the-badge&logo=javascript&logoColor=white" height="24"/>
  <img src="https://img.shields.io/badge/AI_Assisted-Claude-ff9a3c?style=for-the-badge&logo=anthropic&logoColor=white" height="24"/>
</p>

<br/>

> **A complete, production-ready clothing store website** built with pure HTML5, CSS3, and Vanilla JavaScript.  
> Features scroll animations, hover effects, a testimonial slider, product gallery, newsletter form, and an embedded store map — all without a single framework.

<br/>

![Sections](https://img.shields.io/badge/Sections-12-ff6ec7?style=flat&logo=buffer)
![Animations](https://img.shields.io/badge/Animations-CSS%20%26%20JS-ff9a3c?style=flat&logo=javascript)
![AI Tool](https://img.shields.io/badge/AI_Tool-Claude_by_Anthropic-a855f7?style=flat)
![License](https://img.shields.io/badge/License-MIT-3d9cd2?style=flat)

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
| [07](#-how-i-used-ai-in-this-project) | How I Used AI |
| [08](#-ai-vs-manual-breakdown) | AI vs Manual Breakdown |
| [09](#-key-learnings) | Key Learnings |

---

<br/>

# 🔍 Project Overview

>**Shopamp!** is a static clothing store website template designed to showcase fashion products in a professional, visually engaging layout.

The site is divided into **12 complete sections**:

```
Navbar → Hero → About Us → Sale Banner → Features →
Products → Newsletter → Shop Banners → Latest News →
Last Collection Gallery → Testimonials → Location → Footer
```

>Built with **HTML, CSS, and Vanilla JavaScript**, assisted by **Claude AI** for component architecture, CSS logic, and animation systems — while the design decisions, structure planning, and content were driven by me.

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
| **Claude AI** | Component design assistance, CSS architecture, animation logic |

---

<br/>

# 🎨 UI/UX Breakdown

### 🧭 Navbar

```
Position: fixed  |  Height: 64px  |  Z-index: 1000
──────────────────────────────────────────────────────────────
│ shopamp!   HOME   LIVE DEMO ▾   LIVE DEMO BLOCKS ▾  [Buy Now] │
──────────────────────────────────────────────────────────────
```

- Background transitions from transparent → box-shadow on scroll (`.scrolled` class via JS)
- Dropdown menus use CSS-only hover: `opacity 0→1` + `translateY(6px)→0`
- On mobile (`≤640px`): hamburger toggles `.open`, sliding the nav panel down from the top

## `Visual Reference`

<img width="1253" height="49" alt="image" src="https://github.com/user-attachments/assets/0830a818-df44-4808-ac28-5c85d88bd9bc" />


---

### 🖼️ Hero Section

```
Height: 100vh  |  Background: Image.jpg  |  Overlay: rgba(240,240,235,0.45)
┌────────────────────────────────────────────────┐
│                                                │
│                                                │
│  Clothing                                      │
│  Store                   ← bottom-left anchor  │
│  Clothing Website Template                     │
└────────────────────────────────────────────────┘
```

- `object-fit: cover` keeps the image sharp at every viewport size
- Text anchored with `position: absolute; bottom: 80px; left: 48px`

## `Visual Reference`

<img width="1322" height="671" alt="image" src="https://github.com/user-attachments/assets/04396034-41dd-4a3b-b0bc-7a68e856d268" />

---

## 🃏 About Us Section
 
```
Background: #ffffff  |  Layout: 3-column CSS Grid  |  Gap: 32px
┌──────────────────┬──────────────────┬──────────────────┐
│  [Image: Store]  │ [Image: Clothes] │ [Image: Rack]    │
│  Prices          │ Trends           │ Collections      │
│  Best prices     │ Newest trends    │ Previous collect.│
│  Body text...    │ Body text...     │ Body text...     │
│  Learn more >    │ Learn more >     │ Learn more >     │
└──────────────────┴──────────────────┴──────────────────┘
```
 
**Three cards, each containing:**
 
| Element | CSS / HTML Detail |
|---|---|
| Image container | `height: 200px` · `overflow: hidden` · `border-radius: 4px` |
| Image zoom on hover | `transform: scale(1.05)` · `transition: 0.5s ease` |
| Card label | `font-size: 0.78rem` · `text-transform: uppercase` · `color: #888` · `letter-spacing: 1px` |
| Card heading | `font-family: Montserrat` · `color: var(--primary)` · `font-weight: 600` |
| Body text | `font-size: 0.88rem` · `color: #555` · `line-height: 1.65` |
| "Learn more >" link | `color: #555` → hover `color: var(--primary)` transition |
| Scroll animation | Starts `opacity: 0` + `translateY(24px)` → `.visible` fades in |
 
**Card content breakdown:**
 
```
Card 1 — Prices
  Label:   "Prices"
  Heading: "Best prices"
  Text:    Monthly discounts and sales on certain categories.
  Image:   Unsplash — store interior (photo-1441986300917)
 
Card 2 — Trends
  Label:   "Trends"
  Heading: "Newest trends"
  Text:    Latest fashionable clothes + style magazines.
  Image:   Unsplash — clothing display (photo-1558769132)
 
Card 3 — Collections
  Label:   "Collections"
  Heading: "Previous collections"
  Text:    Best pieces from past collections at huge discounts every Saturday.
  Image:   Unsplash — clothing rack (photo-1567401893414)
```
 
**Responsive behaviour:**
- `≤900px` → `grid-template-columns: 1fr` — all 3 cards stack vertically

## `Visual Reference`

<img width="1122" height="506" alt="image" src="https://github.com/user-attachments/assets/8612bb6f-6c25-4af7-86c6-d07d46a4d68c" />


---

## 💥 Sale Banner (70% OFF Section)
 
```
Height: 800px  |  Background: Image 1.jpg  |  Overlay: rgba(50,50,80,0.5)
┌──────────────────────────────────────────────────────┐
│                                                      │
│            WE ARE GLAD TO SEE YOU                    │
│                                                      │
│         SALE TO -70% LAST 2 DAYS                     │  ← color: var(--primary) blue
│                                                      │
│              [ Watch Now ]                           │  ← rounded blue CTA button
│                                                      │
└──────────────────────────────────────────────────────┘
```
 
**How it's built — layer by layer:**
 
```
Layer 1 (bottom): <img class="sale-bg">
  → position: absolute · inset: 0 · object-fit: cover
  → Source: Image 1.jpg (local file)
 
Layer 2 (middle): <div class="sale-overlay">
  → position: absolute · inset: 0
  → background: rgba(50, 50, 80, 0.5)  ← dark purple-blue tint
 
Layer 3 (top): <div class="sale-content">
  → position: relative · z-index: 1 · text-align: center
```
 
**Typography & styling:**
 
| Element | Style |
|---|---|
| Pre-text "WE ARE GLAD TO SEE YOU" | `font-size: 0.8rem` · `letter-spacing: 3px` · `opacity: 0.85` · uppercase |
| Main heading "SALE TO -70%" | `font-family: Montserrat` · `font-size: 2.6rem` · `color: var(--primary)` · `font-weight: 700` |
| "Watch Now" button | `padding: 12px 36px` · `background: var(--primary)` · `border-radius: 30px` · hover lifts `translateY(-2px)` |
 
> The heading color is intentionally `var(--primary)` blue — not white — to create contrast against the dark overlay and make the sale amount the visual focal point.


## `Visual Reference`

<img width="1224" height="598" alt="image" src="https://github.com/user-attachments/assets/9988bb9d-bd9e-44a4-93ad-222f68d3fa74" />

 
---

### 👕 Product Section

```
Grid: 2 columns × 2 rows  |  Card height: 320px
─────────────────────────────────────────────────────
│  [SHIRT $69.99]        │  [LIGHT SHIRT $89.99]   │
│  [JACKET $129.99]      │  [DENIM SHIRT $179.99]  │
─────────────────────────────────────────────────────
```

Each card on hover:
1. Image zooms via `transform: scale(1.05)`
2. Frosted-glass overlay fades in (`backdrop-filter: blur(2px)`)
3. Product name text pops with `transform: scale(0.9 → 1)`

## `Visual Reference`

<img width="1211" height="672" alt="image" src="https://github.com/user-attachments/assets/efc09073-7fda-41b6-831b-b75a94a42d1c" />

---

### 📧 Newsletter Section

```
Max-width: 650px  |  Centered  |  Background: #f4f6f9
┌──────────────────────────────────────────────────┐
│            Be the first to know?                 │
│  Subscribe Now              * 10% friend invite  │
│  🔍 [Enter your email here...]      SUBSCRIBE    │
└──────────────────────────────────────────────────┘
```

- Input and button share one bordered container
- `focus-within` applies a `3px` blue ring around the whole form on interaction

## `Visual Reference`

<img width="1060" height="671" alt="image" src="https://github.com/user-attachments/assets/14d2037b-e174-4a76-8c42-083c1e2297d3" />



---

## 📰 Latest News Section
 
```
Background: var(--bg-light) #f0f2f7  |  Layout: 3-column CSS Grid
┌──────────────────┬──────────────────┬──────────────────┐
│  [News Image 1]  │  [News Image 2]  │  [News Image 3]  │
│                  │                  │                  │
│  Work Mode       │  New Collections │  Our Stores      │
│                  │       Learn More →│                  │
└──────────────────┴──────────────────┴──────────────────┘
```
 
**Card anatomy:**
 
```
.news-card
  └── .news-img-wrap  (height: 190px · overflow: hidden)
        └── <img>     (object-fit: cover · zoom on hover: scale(1.06))
  └── .news-body      (padding: 20px · display: flex · space-between)
        ├── <h3>      (font-size: 1rem · Montserrat · font-weight: 600)
        └── .news-link ("Learn More" · color: var(--primary) · font-size: 0.82rem)
```
 
**The premium hover lift effect:**
 
```css
/* Normal state — invisible, shifted down */
.news-card {
  opacity: 0;
  transform: translateY(24px);
  box-shadow: 0 4px 16px rgba(0,0,0,0.05);
  transition: opacity 0.5s ease, transform 0.6s cubic-bezier(0.25, 1, 0.5, 1), box-shadow 0.4s ease;
}
 
/* After scroll triggers .visible */
.news-card.visible { opacity: 1; transform: translateY(0); }
 
/* On hover — lifts up with deep shadow */
.news-card.visible:hover {
  transform: translateY(-8px);
  box-shadow: 0 20px 38px rgba(0,0,0,0.22);
}
```
 
**Three news items:**
 
| Card | Title | Image Source |
|---|---|---|
| 1 | Work Mode | Unsplash `photo-1441986300917` |
| 2 | New Collections | Unsplash `photo-1558769132` |
| 3 | Our Stores | Unsplash `photo-1567401893414` |
 
**Responsive:** Collapses to single column at `≤900px`

 ## `Visual Reference`

 <img width="1261" height="394" alt="image" src="https://github.com/user-attachments/assets/c07c635b-9fd3-46b1-a815-daf0092ef957" />

---

## 📷 Last Collection Gallery
 
```
Label: "LAST COLLECTION"   Link: "LEARN MORE" →
┌─────────────┬─────────────┬─────────────┐
│  Image 6    │  Image 8    │  Image 9    │  ← Row 1
│  (square)   │  (square)   │  (square)   │
├─────────────┼─────────────┼─────────────┤
│  Image 10   │  Image 7    │  Image 11   │  ← Row 2
│  (square)   │  (square)   │  (square)   │
└─────────────┴─────────────┴─────────────┘
      Each cell: aspect-ratio: 1/1  |  overflow: hidden
```
 
**Header layout:**
 
```css
.gallery-header {
  text-align: left;
  margin-bottom: 32px;
}
/* "LAST COLLECTION" — large blue heading */
.collection-label { font-size: 1.8rem; font-weight: 700; color: var(--primary-accent); }
/* "LEARN MORE" — small dark uppercase link */
.collection-learn { font-size: 0.8rem; font-weight: 700; letter-spacing: 1.5px; color: #333; }
```
 
**Grid system:**
 
```css
.insta-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 24px;   /* both rows and columns */
}
.insta-item {
  aspect-ratio: 1 / 1;   /* perfect squares at any screen width */
  overflow: hidden;
  position: relative;
}
```
 
**3-layer hover animation system:**
 
```
On hover:
  Layer 1 → Image zooms: scale(1.06) + opacity drops to 0.85
  Layer 2 → Dark overlay fades in: rgba(0,0,0,0.45) opacity 0→1
  Layer 3 → Social icons bounce up:
              translateY(12px) scale(0.92)  →  translateY(0) scale(1)
```
 
**Social icons on each image:**
 
Each `.insta-item` overlay contains 3 circular white buttons:
- `fab fa-facebook-f` → Facebook
- `fab fa-twitter` → Twitter
- `fab fa-instagram` → Instagram
```css
.social-icon {
  width: 42px; height: 42px;
  border-radius: 50%;
  background: #fff;
  color: var(--primary-accent);
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}
/* On icon hover → fills blue, lifts up */
.social-icon:hover {
  background: var(--primary-accent);
  color: #fff;
  transform: translateY(-4px);
}
```
 
**Image order in the grid:**
 
| Position | File |
|---|---|
| Row 1, Col 1 | `Image 6.jpg` |
| Row 1, Col 2 | `Image 8.jpg` |
| Row 1, Col 3 | `Image 9.jpg` |
| Row 2, Col 1 | `Image 10.jpg` |
| Row 2, Col 2 | `Image 7.jpg` |
| Row 2, Col 3 | `Image 11.jpg` |
 
**Responsive:** Collapses to `repeat(2, 1fr)` at `≤900px`

  ## `Visual Reference`

  <img width="1156" height="669" alt="image" src="https://github.com/user-attachments/assets/d4a8cf3c-9c7f-4db0-a037-c0efacb5f3b0" />

---

### 💬 Testimonials Slider

```
Max-width: 700px  |  Centered  |  JS-controlled
◉  ←  [Avatar]  Markus Grecho / Sara Mills  →  ◉
          "Review text..."
```

- `display: none / block` toggle on `.active` class
- `@keyframes fadeIn` animates each incoming slide

## `Visual Reference`

<img width="1010" height="424" alt="image" src="https://github.com/user-attachments/assets/2f52e454-27e2-40e0-8359-e57c70ecde1a" />

---

### 📍 Location Section

```
Grid: 2 columns  |  Height: 400px each
┌──────────────────┬──────────────────────────────┐
│   Store Photo    │   Embedded Google Map iframe  │
│  (object-fit)    │      Manhattan, New York      │
└──────────────────┴──────────────────────────────┘
  Email: company@mobirise.com   Phone: +573 1235 5324
```

## `Visual Reference`

<img width="1070" height="532" alt="image" src="https://github.com/user-attachments/assets/b861a157-937b-4e13-ade9-8a31e73e90bb" />

---

## 🔗 Footer Section
 
```
Background: var(--bg-light) #f0f2f7  |  Padding-top: 64px
┌───────────────────────────────┬──────────────┬──────────────┐
│  shopamp!  (logo)             │  News        │  Shop        │
│                               │              │              │
│  Launched in 2012, the store  │  • Trends    │  • Best jeans│
│  uses a wide range of...      │  • Sales     │  • New skirts│
│  (brand description)          │  • Discounts │  • Tuesday % │
│                               │  • Best Prop │  • Pregnant  │
│  [f]  [tw]  [ig]              │              │              │
└───────────────────────────────┴──────────────┴──────────────┘
   © Copyright 2019 Mobirise – Clothing Website Template
```
 
**CSS Grid layout:**
 
```css
.footer-grid {
  display: grid;
  grid-template-columns: 2fr 1fr 1fr;  /* About column is twice as wide */
  gap: 48px;
  padding-bottom: 48px;
}
```
 
**Column 1 — Brand (2fr width):**
 
| Element | Detail |
|---|---|
| Logo `.footer-logo` | `font-family: Montserrat` · `font-size: 1.6rem` · `color: var(--primary)` · `font-weight: 700` |
| Description `.footer-desc` | `font-size: 0.85rem` · `color: #555` · `line-height: 1.75` · 3 sentences about the brand |
| Social buttons | 3 circular bordered buttons — Facebook, Twitter, Instagram |
 
**Social button hover effect:**
 
```css
.footer-social-btn {
  width: 36px; height: 36px;
  border-radius: 50%;
  border: 1.5px solid #ccc;
  color: #555;
}
/* On hover: border turns blue, bg fills blue, icon turns white */
.footer-social-btn:hover {
  border-color: var(--primary);
  color: var(--white);
  background: var(--primary);
}
```
 
**Column 2 — News links:**
```
Trends · Sales · Discounts · Best Proposals
```
 
**Column 3 — Shop links:**
```
Best jeans in town · New skirts collection · Tuesday discounts · Clothes for pregnant
```
 
**Link hover:** `color: #555` → `color: var(--primary)` with `0.3s ease` transition
 
**Footer bottom bar:**
 
```css
.footer-bottom {
  border-top: 1px solid #dce0e8;
  padding: 20px 24px;
  text-align: center;
}
/* © Copyright 2019 Mobirise – font-size: 0.82rem · color: #888 */
```
 
**Responsive behaviour:**
- `≤900px` → `grid-template-columns: 1fr 1fr` · brand column spans full width (`grid-column: 1 / -1`)
- `≤640px` → `grid-template-columns: 1fr` · all columns stack vertically

  ## `Visual Reference`

  <img width="1233" height="337" alt="image" src="https://github.com/user-attachments/assets/af41a91c-288f-4c0a-8011-8c6ae05a64f3" />

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
| Product Cards | Frosted overlay + `backdrop-filter: blur(2px)` + text scale pop |
| News Cards | `translateY(-8px)` lift + `box-shadow: 0 20px 38px rgba(0,0,0,0.22)` |
| Instagram Items | Image zoom + dark overlay + social icon bounce-in from below |
| Shop Banners | Zoom + overlay fade + Buy Now button reveal |
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

### Instagram Gallery Social Icon Bounce

```css
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
| `position: fixed` | Navbar | Keeps nav visible during scroll |
| `position: absolute` | Hero text, product overlay, banner overlay | Layered content over images |
| `object-fit: cover` | All background images | Fills containers without distortion |
| `CSS custom properties` | Entire stylesheet | Global theming and consistency |
| `@keyframes` | Testimonials | Entrance animation for slides |
| `backdrop-filter: blur()` | Product hover overlay | Frosted glass premium effect |
| `IntersectionObserver` | Scroll animations | Triggers `.visible` class on entry |
| `transition` | All interactive elements | Smooth hover state changes |
| `aspect-ratio: 1/1` | Instagram gallery | Perfect square image cards |
| `transform: scale()` | Image zooms | Smooth zoom without layout shift |
| `rgba() overlays` | Hero, Sale Banner, Instagram | Darkening layers over images |
| Semantic HTML | Entire page | `<section>`, `<article>`, `<header>`, `<footer>`, `<nav>` |
| `aria-*` attributes | Navbar, gallery, forms | Accessibility for screen readers |
| Media queries | Entire stylesheet | Breakpoints at `900px` and `640px` |

---

<br/>

# 🤖 How I Used AI in This Project

This project was built with **Claude AI (by Anthropic)** as a development partner. Rather than copying full templates, I used AI as a targeted tool — directing it with specific goals and reviewing every output to understand the logic before applying it.

### My AI Workflow

```
I describe what I want  →  AI generates the code  →  I review & understand it
       ↓                                                        ↓
I test it in the browser  ←  I modify or fix it  ←  I ask follow-up questions
```

---

### What I Asked AI to Help With

| Task | How AI Helped |
|---|---|
| **Product card hover overlay** | Asked AI to build the frosted-glass overlay system with `backdrop-filter` and centered text pop animation |
| **Intersection Observer setup** | Described the scroll fade-in effect I wanted; AI wrote the observer logic and `.visible` class pattern |
| **Newsletter form layout** | Asked for an inline form with icon + input + button sharing one container and a `focus-within` ring |
| **Instagram gallery overlay** | Requested the social icon bounce-in effect — AI implemented the `translateY + scale` combo |
| **News card hover lift** | Described the "premium lift" effect; AI generated the `translateY(-8px)` + deep shadow combination |
| **CSS variable architecture** | Asked AI to organize all colors, shadows, and transitions into a single `:root` block |
| **Mobile hamburger menu** | AI wrote the JS toggle logic and the `transform: translateY(-110%)` slide-in for the mobile nav |
| **Responsive media queries** | Asked AI to write breakpoints at `900px` and `640px` based on the existing grid structure |

---

### Prompts I Actually Used

> *"Create a product card component where hovering shows a frosted-glass overlay in the center of the image with the product name. The text should scale from 0.9 to 1 on hover. The image should zoom slightly."*

> *"Write an Intersection Observer in vanilla JS that adds a `.visible` class to any element with `.card`, `.product-card`, or `.news-card` when 15% of it enters the viewport."*

> *"Build a newsletter form where the search icon, email input, and submit button all sit inside one bordered container. Add a blue focus ring around the whole form when the input is active."*

---

### What I Decided Myself

- The overall page structure and section order
- Which sections to include and what content to put in each
- Color palette (`#3d9cd2` blue as the brand primary)
- Product names, prices, and copy
- Typography pairing (`Montserrat` + `Open Sans`)
- Layout proportions and spacing decisions
- Which hover effects made sense for which sections
- Image selection and alt text for accessibility

---

<br/>

# 🔀 AI vs Manual Breakdown

```
┌─────────────────────────────────────────────────────────┐
│                  PROJECT CONTRIBUTION                   │
├──────────────────────────┬──────────────────────────────┤
│       🤖 AI Assisted     │       ✍️ Done by Me          │
├──────────────────────────┼──────────────────────────────┤
│ CSS animation systems    │ Page structure & section plan │
│ Intersection Observer JS │ Design decisions & color theme│
│ Hover overlay components │ Content, copy & product data  │
│ Focus-within form ring   │ Image selection & alt text    │
│ Mobile nav slide logic   │ Typography pairing            │
│ CSS variable architecture│ Layout proportions & spacing  │
│ Media query breakpoints  │ Reviewing & testing all code  │
│ Grid & Flexbox patterns  │ Debugging & final integration │
└──────────────────────────┴──────────────────────────────┘
```

> 💡 **Using AI doesn't mean not learning.** Every snippet generated was reviewed, tested, modified, and understood before being added to the project. AI accelerated the process — the thinking behind the project was entirely mine.

---

<br/>

# 📚 Key Learnings

### 01 — CSS Grid + Flexbox Together
Using Grid for page-level sections and Flexbox inside components gave me clarity on when to use each. Grid = two-dimensional layout. Flexbox = one-dimensional alignment.

### 02 — CSS Custom Properties are Game Changers
Defining `--primary`, `--transition`, and `--shadow` as variables meant changing the brand color in one place updated the entire site instantly.

### 03 — Intersection Observer is More Efficient Than Scroll Events
The `IntersectionObserver` API fires only when elements cross a threshold — far more performant than attaching listeners to the scroll event which fires constantly.

### 04 — `position: absolute` + `inset: 0` is the Overlay Pattern
Building product overlays, hero text, and banner CTAs made me deeply comfortable with stacking contexts. `inset: 0` shorthand became my go-to for full-cover layers.

### 05 — `object-fit: cover` is Non-Negotiable for Images
Without it, images stretch or squish inside containers. With it, every photo looks intentional and well-composed regardless of container dimensions.

### 06 — Semantic HTML Costs Nothing and Gains Everything
Using `<section>`, `<article>`, `<header>`, `<nav>`, and `<footer>` with `aria-label` attributes makes the page meaningful to screen readers and search engines — at zero extra effort.

### 07 — How to Use AI Without Losing the Learning
Describing exactly what I wanted, then reading and understanding the output before using it, meant AI made me faster — not dependent. The key is using it as a tool, not a shortcut around understanding.

---

<br/>
<div align="center">

**✦ Author ✦**

**Your Name**
🐙 GitHub: [@your-username]((https://github.com/AyeshaAbid892))
💼 LinkedIn: [your-profile](https://www.linkedin.com/in/ayesha-abid33/)
📧 Email: ayeshaa.abid33@gmail.com

---

**Built with curiosity, styled with intention, assisted by AI — and understood every step of the way.**

<br/>

![Made with HTML](https://img.shields.io/badge/Made%20with-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Styled with CSS](https://img.shields.io/badge/Styled%20with-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Powered by JS](https://img.shields.io/badge/Powered%20by-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![AI Assisted](https://img.shields.io/badge/AI%20Assisted-Claude-a855f7?style=for-the-badge&logo=anthropic&logoColor=white)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:a855f7,25:ff6ec7,50:ff9a3c,75:f7df1e,100:3d9cd2&height=150&section=footer&text=Shopamp!%20—%20Fashion%20Meets%20Clean%20Code&fontSize=22&fontColor=ffffff&fontAlignY=65&animation=twinkling" width="100%" />

</div>
