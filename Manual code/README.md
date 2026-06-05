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
  <img src="https://img.shields.io/badge/Built_Manually-Self_Made-3d9cd2?style=for-the-badge&logo=checkmarx&logoColor=white" height="24"/>
</p>

<br/>

> **A complete, production-ready clothing store website** built with pure HTML5, CSS3, and Vanilla JavaScript.  
> Features scroll animations, hover effects, a testimonial slider, product gallery, newsletter form, and an embedded store map — all without a single framework.

<br/>

![Sections](https://img.shields.io/badge/Sections-12-ff6ec7?style=flat&logo=buffer)
![Animations](https://img.shields.io/badge/Animations-CSS%20%26%20JS-ff9a3c?style=flat&logo=javascript)
![Built By](https://img.shields.io/badge/Built_By-Self_Made-3d9cd2?style=flat)
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
├── 🖼️  Image 1.jpg             ← Sale banner background (v1 local)
├── 🖼️  Image 2.jpg             ← Product — Shirt ($69.99)
├── 🖼️  Image 3.jpg             ← Product — Light Shirt ($89.99)
├── 🖼️  Image 4.jpg             ← Product — Jacket ($129.99)
├── 🖼️  Image 5.jpg             ← Product — Denim Shirt ($179.99)
├── 🖼️  Image 6–11.jpg          ← Last Collection gallery (6 images)
│
└── 📄 README.md                ← You are here
```

> 💡 External images (About Us, News, Shop Banners, Sale Banner, Testimonials) are loaded from **Unsplash CDN** — internet connection required.

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
| [07](#-how-i-built-this-project) | How I Built This Project |
| [08](#-what-i-built-myself) | What I Built Myself |
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

>Built entirely with **HTML, CSS, and Vanilla JavaScript** — every component, animation system, layout decision, and accessibility attribute was written and structured manually.

---

<br/>

# ✨ Features

| Feature | Description |
|---|---|
| 📱 **Fully Responsive** | Desktop, tablet, and mobile via CSS range media queries (`width <= 900px`, `width <= 768px`, `width <= 640px`) |
| 🧭 **Sticky Navbar** | Fixed nav with `backdrop-filter: blur(8px)` + scroll-triggered shadow + accessible hamburger menu |
| 🎠 **CSS Dropdown Menus** | Smooth opacity + `translateY` slide-down with `aria-haspopup`, `aria-expanded`, `role="menu"` |
| 🖼️ **Full-Viewport Hero** | 100vh background image with `rgba(240,240,235,0.45)` overlay and anchored brand headline |
| 🃏 **About Us Cards** | 3-column grid cards with image zoom on hover + Intersection Observer scroll fade-in |
| 💥 **Sale Banner** | Full-width promotional section with Unsplash CDN background + `rgba(255,255,255,0.85)` overlay + CTA |
| ⚙️ **Features Section** | 2-column layout with 4 icon-bordered feature highlights (Sale, Delivery, Clients, Warranty) |
| 👕 **Product Grid** | 2×2 product cards with frosted-glass hover text overlay (`backdrop-filter: blur(2px)`) |
| 📧 **Newsletter Form** | Inline email subscription with `focus-within` blue ring + `fa-envelope` icon + SUBSCRIBE button |
| 🗂️ **Shop Banners** | 2×2 image banner grid with hover overlay + accessible BUY NOW buttons |
| 📰 **Latest News** | 3-column cards with `translateY(-8px)` lift-on-hover + `box-shadow: 0 20px 38px rgba(0,0,0,0.22)` |
| 📷 **Last Collection Gallery** | 3×2 square Instagram-style grid with `rel="noopener"` social icon overlay |
| 💬 **Testimonial Slider** | JS-powered carousel with `role="group"`, `aria-roledescription="slide"`, `aria-label="N of 2"` |
| 📍 **Store Location** | Split layout — store photo + contact (email/phone) + Google Map with `title` attribute |
| 🔗 **Footer** | 3-column grid (`2fr 1fr 1fr`) with brand description, News links, Shop links, and social buttons |
| 🎞️ **Scroll Animations** | Intersection Observer (`threshold: 0.15`) fades 6 element types in as they enter the viewport |

---

<br/>

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic structure — `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<nav>`, `<blockquote>` |
| **CSS3** | Custom properties design system, Flexbox, Grid, `clamp()`, `inset`, logical properties, range breakpoints |
| **Vanilla JavaScript** | Sticky navbar, hamburger + ARIA toggle, dropdown `aria-expanded`, testimonial slider, Intersection Observer |
| **Google Fonts** | `Montserrat` (headings, weight 400/600/700) + `Open Sans` (body, weight 400/600) via `preconnect` |
| **Font Awesome 6** | Icons for features (`fa-tag`, `fa-truck`, `fa-heart`, `fa-thumbs-up`), social media, nav caret, envelope |
| **Google Maps Embed** | Embedded iframe — Manhattan, New York (`z=13`), `loading="lazy"`, `title` for accessibility |
| **Unsplash CDN** | External stock images for About Us, Sale Banner, News, Banners, and Testimonials |

---

<br/>

# 🎨 UI/UX Breakdown

### 🧭 Navbar

```
Position: fixed  |  Height: 64px (--nav-height)  |  Z-index: 1000
backdrop-filter: blur(8px)  |  background: rgba(255,255,255,0.97)
──────────────────────────────────────────────────────────────────────
│ shopamp!   HOME   LIVE DEMO ▾   LIVE DEMO BLOCKS ▾  [Buy Now] │
──────────────────────────────────────────────────────────────────────
```

- Scroll shadow: `box-shadow: var(--shadow-sm)` triggered via `.scrolled` at `scrollY > 60`
- Dropdown items use `<button type="button">` with `aria-haspopup="true"`, `aria-expanded="false"`, `aria-controls` pointing to menu `id`
- Dropdown menus: `role="menu"` + children use `role="menuitem"` — full keyboard + screen-reader support
- Live Demo items: `CLOTHING STORE`, `FOOD STORE` · Live Demo Blocks: `Header`, `Content`, `Shop`, `Slider`
- On mobile (`width <= 640px`): hamburger toggles `.open` + updates `aria-expanded` programmatically via JS


## `Visual Reference`

<img width="1253" height="49" alt="Screenshot 2026-06-04 at 5 12 46 PM" src="https://github.com/user-attachments/assets/f45b1d5f-4b25-4d3e-bb58-5a880e2f7e7a" />


---

### 🖼️ Hero Section

```
Height: 100vh  |  min-height: 560px  |  margin-block-start: var(--nav-height)
Background: Image.jpg  |  Overlay: rgba(240,240,235,0.45)
loading="eager"  (priority load — above fold)
┌────────────────────────────────────────────────┐
│                                                │
│                                                │
│  Clothing                                      │
│  Store                   ← bottom-left anchor  │
│  Clothing Website Template                     │
└────────────────────────────────────────────────┘
```

- `object-fit: cover` + `object-position: center top` keeps image sharp at every viewport
- Text anchored with `position: absolute; inset-block-end: 80px; inset-inline-start: 48px`
- Hero title: `var(--font-display)`, `3.8rem`, `font-weight: 700`, `color: var(--clr-dark) #1e293b`
- Hero subtitle: `font-size: 0.95rem`, `color: var(--clr-primary) #3d9cd2`, `font-weight: 600`
- Section uses `aria-label="Welcome Banner"` for screen readers


## `Visual Reference`

<img width="1322" height="671" alt="Screenshot 2026-06-04 at 5 13 44 PM" src="https://github.com/user-attachments/assets/16bcc29c-c56e-4b65-97f6-33da71b5770e" />


---

## 🃏 About Us Section

```
Background: #ffffff  |  Layout: 3-column CSS Grid  |  Gap: 32px
aria-labelledby="about-title"
┌──────────────────┬──────────────────┬──────────────────┐
│  [Store Image]   │ [Clothes Image]  │ [Rack Image]     │
│  Prices          │ Trends           │ Collections      │
│  Best prices     │ Newest trends    │ Previous collect.│
│  Body text...    │ Body text...     │ Body text...     │
│  Learn more >    │ Learn more >     │ Learn more >     │
└──────────────────┴──────────────────┴──────────────────┘
```

**Three cards, each containing:**

| Element | CSS / HTML Detail |
|---|---|
| Image container | `height: 200px` · `overflow: hidden` · `border-radius: var(--radius-sm) 4px` |
| Image zoom on hover | `transform: scale(1.05)` · `transition: 0.5s ease` |
| Card label | `font-size: 0.78rem` · `text-transform: uppercase` · `color: var(--clr-text-light) #888` · `letter-spacing: 1px` |
| Card heading | `font-family: var(--font-display)` · `color: var(--clr-primary)` · `font-weight: 600` |
| Body text | `font-size: 0.88rem` · `color: var(--clr-text-gray) #555` · `line-height: 1.65` |
| "Learn more >" link | Descriptive `aria-label` on each · `color: #555` → hover `color: var(--clr-primary)` |
| Scroll animation | `opacity: 0` + `translateY(24px)` → `.visible` via Intersection Observer |
| Images | `loading="lazy"` on all three |

**Card content breakdown:**

```
Card 1 — Prices
  Label:   "Prices"
  Heading: "Best prices"
  Text:    Monthly discounts and sales on certain categories.
  Alt:     "Clothing neatly hanging on commercial store racks"
  Image:   Unsplash — photo-1441986300917-64674bd600d8

Card 2 — Trends
  Label:   "Trends"
  Heading: "Newest trends"
  Text:    Latest fashionable clothes + style magazines.
  Alt:     "Latest dynamic clothing trends on display"
  Image:   Unsplash — photo-1558769132-cb1aea458c5e

Card 3 — Collections
  Label:   "Collections"
  Heading: "Previous collections"
  Text:    Best pieces from past collections at huge discounts every Saturday.
  Alt:     "Curated previous season outfits arrangement"
  Image:   Unsplash — photo-1567401893414-76b7b1e5a7a5
```

**Responsive behaviour:**
- `width <= 900px` → `grid-template-columns: 1fr` — all 3 cards stack vertically



## `Visual Reference`

<img width="1122" height="506" alt="Screenshot 2026-06-04 at 5 22 48 PM" src="https://github.com/user-attachments/assets/21baae6b-6263-48ca-af00-383ca805e89b" />


---

## 💥 Sale Banner Section

```
Section class: .sale-promo-banner  |  padding-block: 120px
Background: Unsplash CDN photo-1441986300917 (no-repeat center/cover)
Overlay: rgba(255,255,255,0.85)  ← light white wash
aria-label="Limited Flash Sale Countdown"
┌──────────────────────────────────────────────────────┐
│                                                      │
│         WE ARE GLAD TO SEE YOU                       │
│                                                      │
│      SALE TO -70% LAST 2 DAYS                        │  ← color: #111111
│                                                      │
│           [ Watch Now ]                              │  ← rounded blue CTA
│                                                      │
└──────────────────────────────────────────────────────┘
```

**How it's built — layer by layer:**

```
Layer 1 (bottom): CSS background-image on .sale-promo-banner
  → background: url('unsplash...') no-repeat center center/cover

Layer 2 (middle): <div class="promo-bg-overlay">
  → position: absolute · inset: 0
  → background-color: rgba(255, 255, 255, 0.85)  ← bright white overlay

Layer 3 (top): <div class="promo-content-block">
  → position: relative · z-index: 2 · max-width: 800px · margin-inline: auto
```

**Typography & styling:**

| Element | Style |
|---|---|
| Tag "WE ARE GLAD TO SEE YOU" | `font-size: 13px` · `font-weight: 600` · `letter-spacing: 2px` · `color: var(--clr-muted) #64748b` · `display: block` |
| Main heading "SALE TO -70% LAST 2 DAYS" | `font-size: clamp(28px, 5vw, 44px)` · `font-weight: 800` · `color: #111111` · `letter-spacing: 1px` |
| "Watch Now" button | `padding: 12px 36px` · `background: var(--clr-primary)` · `border-radius: 25px` · hover `transform: scale(1.03)` |

> This version uses a **light overlay** (`rgba(255,255,255,0.85)`) instead of dark — the heading is `#111111` black for strong contrast on the bright background.



## `Visual Reference`

<img width="1325" height="315" alt="image" src="https://github.com/user-attachments/assets/1b322a0b-3cf3-4033-aca4-502a079050de" />



---

### ⚙️ Features Section

```
Background: var(--clr-bg-light) #f0f2f7  |  Layout: 2-column CSS Grid  |  Gap: 60px
aria-labelledby="features-title"
┌───────────────────────┬────────────────────────────────────┐
│  FEATURES             │  [tag] Sale      [truck] Delivery  │
│  Features Our         │                                    │
│  Store                │  [heart] Clients [thumb] Warranty  │
└───────────────────────┴────────────────────────────────────┘
```

- Left: `FEATURES` label (`0.75rem`, `letter-spacing: 2.5px`, `color: var(--clr-text-light)`) + `<h2>` heading `Features Our Store` (`2.2rem`, `font-weight: 700`, `color: var(--clr-dark)`)
- Right: `grid-template-columns: 1fr 1fr`, `gap: 32px`, 4 `.feature-item` blocks
- Feature icon box: `44px × 44px`, `border: 1.5px solid var(--clr-primary)`, `border-radius: var(--radius-sm)`
- Icons all have `aria-hidden="true"` — decorative, not announced by screen readers
- Heading inside each item uses `<h3>` tag for correct document outline
- Scroll animation: `opacity: 0` + `translateY(20px)` → `.visible` via Intersection Observer

**Four feature items:**

| Icon | Title | Description |
|---|---|---|
| `fas fa-tag` | Sale | Check out our best sales and discounts. |
| `fas fa-truck` | Delivery | We provide delivery within 3 days. |
| `fas fa-heart` | Our Clients | Our clients are always satisfied with our work. |
| `fas fa-thumbs-up` | Warranty | You can bring back the clothes within 1 month. |


## `Visual Reference`

<img width="1219" height="196" alt="Screenshot 2026-06-05 at 12 09 06 AM" src="https://github.com/user-attachments/assets/0b13f130-226b-41a0-9da9-baf8de4392b0" />



---

### 👕 Product Section

```
Grid: 2 columns × 2 rows  |  Card height: 320px
aria-labelledby="products-main-title"
─────────────────────────────────────────────────────
│  [SHIRT $69.99]          │  [LIGHT SHIRT $89.99]  │
│  [JACKET $129.99]        │  [DENIM SHIRT $179.99] │
─────────────────────────────────────────────────────
```

Each card on hover:
1. Image zooms via `transform: scale(1.05)` (transition: `0.6s cubic-bezier(0.25, 1, 0.5, 1)`)
2. Frosted-glass overlay fades in (`backdrop-filter: blur(2px)`, `background: rgba(255,255,255,0.25)`)
3. Overlay text pops with `transform: scale(0.9 → 1)` (transition: `0.4s cubic-bezier`)

**Product card data:**

| Image | Alt Text | Name | Price |
|---|---|---|---|
| Image 2.jpg | "Premium tailored formal shirt" | SHIRT | $69.99 |
| Image 3.jpg | "Light breathable casual summer shirt" | LIGHT SHIRT | $89.99 |
| Image 4.jpg | "Modern slim tailored outdoor jacket" | JACKET | $129.99 |
| Image 5.jpg | "Classic rugged durable denim shirt" | DENIM SHIRT | $179.99 |

- All product images: `loading="lazy"`
- Product name: `<h3>` tag · `0.8rem` · `font-weight: 600` · `color: var(--clr-primary)` · `letter-spacing: 1.5px` · uppercase
- Product price: `0.95rem` · `color: var(--clr-text-gray) #555`



## `Visual Reference`

<img width="1211" height="672" alt="Screenshot 2026-06-04 at 5 14 53 PM" src="https://github.com/user-attachments/assets/9ff76374-a5dc-49bb-91f6-3455ac6ea8da" />


---

### 📧 Newsletter Section

```
Max-width: 650px  |  Centered  |  Background: var(--clr-bg-app) #f4f6f9
aria-label="Newsletter Subscription"
┌──────────────────────────────────────────────────┐
│            Be the first to know?                 │
│  Subscribe Now    * Invite a friend - 10% off   │
│  ✉ [Enter your email here...]      SUBSCRIBE    │
└──────────────────────────────────────────────────┘
```

- Wrapper: `display: flex; flex-direction: column; align-items: center; gap: 20px`
- Title: `var(--font-display)`, `font-size: clamp(1.8rem, 4vw, 2.4rem)`, `color: var(--clr-primary)`, `font-weight: 500`
- Meta row: `justify-content: space-between` — `<span>` "Subscribe Now" (bold, dark) + `<strong>` "* Invite a friend and get a discount - 10%" (muted)
- Icon changed to `fas fa-envelope` (vs `fa-search` in v1)
- `<label for="newsletter-secure-email">` hidden with `.modern-sr-only` — accessible but invisible
- Form: `display: flex`, `border: 1px solid var(--clr-border)`, `border-radius: var(--radius-sm)`, `overflow: hidden`
- `focus-within`: `border-color: var(--clr-primary)` + `box-shadow: 0 0 0 3px rgba(59,130,246,0.15)`
- Submit: `padding-inline: 24px`, white bg, `color: var(--clr-primary)`, `border-inline-start: 1px solid #f1f5f9`, `font-weight: 700`


## `Visual Reference`

<img width="1057" height="187" alt="Screenshot 2026-06-05 at 12 07 55 AM" src="https://github.com/user-attachments/assets/4752fe44-d5e6-4fc2-820b-576e04768af5" />


---

## 🗂️ Shop Banners Section

```
Layout: 2×2 CSS Grid  |  gap: 0  |  Banner height: 280px
aria-label="Product Categories Showcase"
┌──────────────────────┬──────────────────────┐
│  [Women Banner]      │  [Collection Banner] │
│  item!  [BUY NOW]    │  item!  [BUY NOW]    │
├──────────────────────┼──────────────────────┤
│  [Style Banner]      │  [Fashion Banner]    │
│  2em!   [BUY NOW]    │  2em!   [BUY NOW]    │
└──────────────────────┴──────────────────────┘
```

- Each `.banner-card`: `position: relative`, `overflow: hidden`, `height: 280px`
- Hover: image zooms `scale(1.05)` + overlay fades in `rgba(0,0,0,0.35)`
- Overlay aligns `flex-end / flex-end` (bottom-right) with `padding: 20px 24px`
- "BUY NOW" each has a descriptive `aria-label` (e.g. `"Buy items from women's lookbook now"`)
- All images: `loading="lazy"` + descriptive alt text

**Unsplash image sources:**

| Position | Alt Text | Unsplash Photo ID |
|---|---|---|
| Banner 1 | "Women's modern collection style apparel preview" | photo-1525507119028-ed4c629a60a3 |
| Banner 2 | "Curated top-tier boutique catalog highlights" | photo-1567401893414-76b7b1e5a7a5 |
| Banner 3 | "Trendy comfortable everyday streetwear styles" | photo-1512436991641-6745cdb1723f |
| Banner 4 | "High-end luxury premium retail fashion lines" | photo-1490481651871-ab68de25d43d |


## `Visual Reference`

<img width="1057" height="486" alt="Screenshot 2026-06-05 at 12 07 27 AM" src="https://github.com/user-attachments/assets/4a700ac7-2563-4553-a7a2-2344002bb654" />


---

## 📰 Latest News Section

```
Background: var(--clr-bg-light) #f0f2f7  |  Layout: 3-column CSS Grid
aria-labelledby="news-main-title"
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
  └── .news-img-wrap  (height: 190px · overflow: hidden · bg: #000000)
        └── <img>     (object-fit: cover · zoom on hover: scale(1.06) · loading="lazy")
  └── .news-body      (padding: 20px 20px 24px · display: flex · space-between)
        ├── <h3>      (font-size: 1rem · var(--font-display) · font-weight: 600)
        └── .news-link ("Learn More" · aria-label on each · color: var(--clr-primary))
```

**The premium hover lift effect:**

```css
.news-card {
  opacity: 0;
  transform: translateY(24px);
  box-shadow: var(--shadow-normal);           /* 0 4px 16px rgba(0,0,0,0.05) */
  transition: opacity 0.5s ease,
              transform 0.6s cubic-bezier(0.25, 1, 0.5, 1),
              box-shadow 0.4s ease;
  will-change: transform, box-shadow;
}

.news-card.visible { opacity: 1; transform: translateY(0); }

.news-card.visible:hover {
  transform: translateY(-8px);
  box-shadow: var(--shadow-hover);            /* 0 20px 38px rgba(0,0,0,0.22) */
}
```

**Three news items:**

| Card | Heading | Alt Text | Image Source |
|---|---|---|---|
| 1 | Work Mode | "Corporate office operations and fashion studio workflow coverage" | Unsplash `photo-1441986300917-64674bd600d8` |
| 2 | New Collections | "Professional runway models displaying premium seasonal apparel lines" | Unsplash `photo-1558769132-cb1aea458c5e` |
| 3 | Our Stores | "Brick and mortar high-end luxury retail showroom layout" | Unsplash `photo-1567401893414-76b7b1e5a7a5` |

**Responsive:** Collapses to `grid-template-columns: 1fr` at `width <= 900px`


## `Visual Reference`

<img width="1261" height="394" alt="Screenshot 2026-06-04 at 5 25 34 PM" src="https://github.com/user-attachments/assets/b4f827c7-64e7-4bc9-90d7-0dc768db2d64" />


---

## 📷 Last Collection Gallery

```
aria-label="Social Media Catalog Feed"
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
.gallery-header { margin-block-end: 32px; text-align: left; }
.collection-label {
  font-family: var(--font-display);
  font-size: 1.8rem; font-weight: 700;
  color: var(--clr-primary) #3d9cd2;
  margin: 0 0 8px 0;
}
.collection-learn {
  font-size: 0.8rem; font-weight: 700;
  letter-spacing: 1.5px; color: #333333;
}
```

**Grid system:**

```css
.insta-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: var(--grid-gap-main);   /* 24px */
}
.insta-item {
  position: relative;
  overflow: hidden;
  aspect-ratio: 1 / 1;
  background-color: #000000;
  border-radius: 2px;
}
```

**3-layer hover animation system:**

```
On hover:
  Layer 1 → Image zooms: scale(1.06) + opacity drops to 0.85
  Layer 2 → Dark overlay fades in: rgba(0,0,0,0.45) opacity 0→1
  Layer 3 → Social icons bounce up:
              translateY(12px) scale(0.92)  →  translateY(0) scale(1)
              transition: var(--transition-premium) — 0.4s cubic-bezier(0.25,1,0.5,1)
```

**Social icons on each image (with full accessibility):**

Each `.insta-item` overlay contains 3 circular white buttons with `gap: 12px` and `rel="noopener"`:
- `fab fa-facebook-f` → aria-label: `"Share this post on Facebook"`
- `fab fa-twitter` → aria-label: `"Share this post on Twitter"`
- `fab fa-instagram` → aria-label: `"View original item on Instagram"`

```css
.social-icon {
  width: 42px; height: 42px;
  border-radius: 50%;
  background: var(--clr-white);
  color: var(--clr-primary);
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  transition: var(--transition-premium);
}
.social-icon:hover {
  background: var(--clr-primary);
  color: var(--clr-white);
  transform: translateY(-4px);
  box-shadow: 0 6px 16px rgba(59,130,246,0.35);
}
```

**Image order in the grid:**

| Position | File | Alt Text |
|---|---|---|
| Row 1, Col 1 | `Image 6.jpg` | "...seasonal accessory design" |
| Row 1, Col 2 | `Image 8.jpg` | "...high-end dynamic outerwear styles" |
| Row 1, Col 3 | `Image 9.jpg` | "...minimal structured summer collection" |
| Row 2, Col 1 | `Image 10.jpg` | "...street-wear retail apparel design" |
| Row 2, Col 2 | `Image 7.jpg` | "...aesthetic knitwear design coordination" |
| Row 2, Col 3 | `Image 11.jpg` | "...luxury tailored suits and custom fashion fabrics" |

**Responsive:** Collapses to `repeat(2, 1fr)` at `width <= 900px`


## `Visual Reference`

<img width="1156" height="669" alt="Screenshot 2026-06-04 at 5 26 34 PM" src="https://github.com/user-attachments/assets/a7f6d39b-3145-43d0-9112-502365a227b7" />

---

### 💬 Testimonials Slider

```
aria-labelledby="testimonials-title"  |  Max-width: 700px  |  Centered
min-height: 300px  |  JS-controlled
◉  ←  [Avatar]  Markus Grecho / Sara Mills  →  ◉
          "Review text..."
```

- `display: none / block` toggle on `.active` class
- `@keyframes fadeIn` animates each slide (`opacity 0→1`, `translateY(10px)→0`, `0.5s ease`)
- Each slide uses `role="group"`, `aria-roledescription="slide"`, `aria-label="1 of 2"` / `"2 of 2"`
- Quote text wrapped in `<blockquote class="testi-quote-wrap">` for semantic meaning
- Prev button: `aria-label="Go to Previous Testimonial"` · Next: `aria-label="Go to Next Testimonial"`
- Arrow positions: `inset-inline-start: -48px` / `inset-inline-end: -48px`

**Two testimonial slides:**

| Slide | Name | Role | Image Source |
|---|---|---|---|
| 1 | Markus Grecho | Clients | Unsplash `photo-1544005313-94ddf0286df2` |
| 2 | Sara Mills | Clients | Unsplash `photo-1534528741775-53994a69daeb` |

- Avatar: `72px × 72px`, `border-radius: 50%`, `border: 3px solid #eeeeee`, `loading="lazy"`
- Name: `<p class="testi-name">` · `Montserrat` · `1rem` · `font-weight: 700`
- Role: `<p class="testi-role">` · `0.82rem` · `color: var(--clr-text-light)` · `margin-block: 4px 18px`
- Text: `0.9rem` · `color: var(--clr-text-gray)` · `line-height: 1.75`

## `Visual Reference`

<img width="1010" height="424" alt="Screenshot 2026-06-04 at 5 16 40 PM" src="https://github.com/user-attachments/assets/db9ac3cd-0b9a-4684-8c37-3c42f8c40fc4" />


---

### 📍 Location Section

```
Background: var(--clr-white)  |  padding-block: 60px
aria-labelledby="location-heading"
┌──────────────────────────────────────────────────────┐
│  Email                        Phone                  │
│  company@mobirise.com         +573 1235 5324         │
└──────────────────────────────────────────────────────┘
┌──────────────────┬──────────────────────────────────┐
│   Store Photo    │   Embedded Google Map iframe      │
│  (object-fit)    │      Manhattan, New York z=13     │
│  height: 400px   │      height: 400px               │
└──────────────────┴──────────────────────────────────┘
```

- Contact header uses `<span class="contact-label">` with `id` values + `aria-labelledby` on links
- Email `href="mailto:company@mobirise.com"` · Phone `href="tel:+57312355324"`
- Location grid: `grid-template-columns: repeat(2, 1fr)`, `box-shadow: 0 4px 20px rgba(0,0,0,0.05)`, `border-radius: 4px`, `overflow: hidden`
- Store photo: Unsplash `photo-1441986300917` · `object-fit: cover` · detailed alt text
- Map iframe: `title="Interactive Store Location Geographic Map"` · `loading="lazy"` · `referrerpolicy="no-referrer-when-downgrade"`

## `Visual Reference`

<img width="1070" height="532" alt="Screenshot 2026-06-04 at 5 17 14 PM" src="https://github.com/user-attachments/assets/dbceed4e-cbe4-4f43-bbd6-26fe63bc6360" />


---

## 🔗 Footer Section

```
Background: var(--clr-bg-light) #f0f2f7  |  Padding-top: 64px
┌───────────────────────────────┬──────────────┬──────────────┐
│  shopamp!  (logo)             │  News        │  Shop        │
│  aria-label="...Footer Ref"   │  <h2> title  │  <h2> title  │
│  (brand description)          │  • Trends    │  • Best jeans│
│                               │  • Sales     │  • New skirts│
│  [f]  [tw]  [ig]              │  • Discounts │  • Tuesday % │
│  (all with aria-labels)       │  • Best Prop │  • Pregnant  │
└───────────────────────────────┴──────────────┴──────────────┘
   © 2026 Mobirise – Clothing Website Template – All Rights Reserved
```

**CSS Grid layout:**

```css
.footer-grid {
  display: grid;
  grid-template-columns: 2fr 1fr 1fr;
  gap: 48px;
  padding-block-end: 48px;
}
```

**Column 1 — Brand (2fr width):**

| Element | Detail |
|---|---|
| Logo `.footer-logo` | `var(--font-display)` · `1.6rem` · `color: var(--clr-primary)` · `font-weight: 700` · `aria-label` set |
| Description `.footer-desc` | `0.85rem` · `color: var(--clr-text-gray)` · `line-height: 1.75` · 4 sentences about brand |
| Social buttons | 3 circular bordered buttons — each with descriptive `aria-label` + `rel="noopener"` |

**Social button hover effect:**

```css
.footer-social-btn {
  width: 36px; height: 36px;
  border-radius: 50%;
  border: 1.5px solid #cccccc;
  color: var(--clr-text-gray);
}
.footer-social-btn:hover {
  border-color: var(--clr-primary);
  color: var(--clr-white);
  background: var(--clr-primary);
}
```

**Column 2 — News links (heading uses `<h2 class="footer-links-title">`):**
```
Trends · Sales · Discounts · Best Proposals
```

**Column 3 — Shop links (heading uses `<h2 class="footer-links-title">`):**
```
Best jeans in town · New skirts collection · Tuesday discounts · Clothes for pregnant
```

**Footer bottom bar — updated copyright year:**
```
© 2026 Mobirise – Clothing Website Template – All Rights Reserved
```

**Responsive behaviour:**
- `width <= 900px` → `grid-template-columns: 1fr 1fr` · brand column `grid-column: 1 / -1`
- `width <= 640px` → `grid-template-columns: 1fr` · all columns stack vertically

## `Visual Reference`

<img width="1233" height="337" alt="Screenshot 2026-06-04 at 5 27 53 PM" src="https://github.com/user-attachments/assets/bc601562-622f-48c5-b559-5fb45258aca4" />

---

## `YouTube URL :` https://youtu.be/-TJ8hoG0Hys

<br/>

# 🎞️ Animations & Styling

### CSS Design System (Global Token Architecture)

```css
:root {
  /* Core Color Palette */
  --clr-primary:         #3d9cd2;
  --clr-primary-hover:   #2a7fb5;
  --clr-accent:          #00b5e2;
  --clr-dark:            #1e293b;
  --clr-text-gray:       #555555;
  --clr-text-light:      #888888;
  --clr-bg-light:        #f0f2f7;
  --clr-bg-app:          #f4f6f9;
  --clr-white:           #ffffff;
  --clr-border:          #cbd5e1;
  --clr-muted:           #64748b;

  /* Layout */
  --nav-height:          64px;
  --radius-sm:           4px;
  --radius-lg:           30px;
  --layout-max-width:    1140px;
  --container-width:     1100px;
  --grid-gap-main:       24px;

  /* Typography */
  --font-display:        'Montserrat', sans-serif;
  --font-body:           'Open Sans', sans-serif;

  /* Motion */
  --transition-fast:     0.2s cubic-bezier(0.4, 0, 0.2, 1);
  --transition-normal:   0.3s ease;
  --transition-premium:  0.4s cubic-bezier(0.25, 1, 0.5, 1);

  /* Shadow Elevation */
  --shadow-sm:           0 2px 12px rgba(0, 0, 0, 0.12);
  --shadow-md:           0 4px 18px rgba(0, 0, 0, 0.10);
  --shadow-normal:       0 4px 16px rgba(0, 0, 0, 0.05);
  --shadow-hover:        0 20px 38px rgba(0, 0, 0, 0.22);
  --shadow-overlay:      rgba(0, 0, 0, 0.45);
}
```

---

### Scroll-Triggered Fade-In (Intersection Observer)

Elements start invisible and slide up into view when 15% of them enter the viewport:

```javascript
const animatedEls = document.querySelectorAll(
  '.card, .product-card, .news-card, .insta-item, .feature-item, .banner-card'
);
const observer = new IntersectionObserver(
  entries => {
    entries.forEach(e => {
      if (e.isIntersecting) e.target.classList.add('visible');
    });
  },
  { threshold: 0.15 }
);
animatedEls.forEach(el => observer.observe(el));
```

```css
.card {
  opacity: 0;
  transform: translateY(24px);
  transition: opacity 0.5s ease, transform 0.5s ease;
}
.card.visible { opacity: 1; transform: translateY(0); }
```

---

### Hover Effects Summary

| Element | Effect |
|---|---|
| About Cards | Image zoom `scale(1.05)` · `transition: 0.5s ease` |
| Product Cards | Frosted overlay (`backdrop-filter: blur(2px)`) + `rgba(255,255,255,0.25)` + text `scale(0.9→1)` |
| News Cards | `translateY(-8px)` lift + `var(--shadow-hover)` (`0 20px 38px rgba(0,0,0,0.22)`) |
| Instagram Items | Image `scale(1.06)` + `opacity 0.85` + dark overlay + social icon `translateY(12px)→0` |
| Shop Banners | Zoom `scale(1.05)` + overlay `rgba(0,0,0,0.35)` fade + Buy Now reveal |
| Nav Dropdowns | `opacity 0→1` + `translateY(6px)→0` + `border-top: 2px solid var(--clr-primary)` |
| Footer Social | Background fill `var(--clr-primary)` + border-color transition |
| Watch Now Button | `transform: scale(1.03)` on hover (sale banner) |
| Buy Now Nav | `transform: translateY(-1px)` on hover |

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

### Accessible Dropdown JS System

```javascript
const dropdownToggles = document.querySelectorAll('.dropdown-toggle');
dropdownToggles.forEach(toggle => {
  toggle.addEventListener('click', () => {
    const isExpanded = toggle.getAttribute('aria-expanded') === 'true';
    toggle.setAttribute('aria-expanded', !isExpanded);
  });
  document.addEventListener('click', (e) => {
    if (!toggle.contains(e.target)) {
      toggle.setAttribute('aria-expanded', 'false');
    }
  });
});
```

---

<br/>

# 🧠 HTML & CSS Concepts Used

| Concept | Used In | How It Was Applied |
|---------|---------|-------------------|
| `CSS Grid` | Products, About, News, Banners, Footer, Location | Multi-column responsive layouts |
| `Flexbox` | Navbar, Features, Newsletter, Footer socials | Alignment and spacing |
| `CSS Logical Properties` | Entire stylesheet — `margin-inline`, `padding-block`, `inset-inline-start` etc. | Writing-mode-aware modern CSS |
| `CSS Custom Properties` | Entire stylesheet — full token system in `:root` | Global theming, consistency, dark mode readiness |
| `clamp()` | Sale banner heading, newsletter title | Fluid responsive typography without media queries |
| `position: fixed` | Navbar | Keeps nav visible during scroll with `z-index: 1000` |
| `position: absolute` + `inset: 0` | Hero text, overlays, sale banner content | Full-cover layering shorthand |
| `object-fit: cover` | Hero, all card images, location photo | Fills containers without distortion |
| `backdrop-filter: blur()` | Product hover overlay (`blur(2px)`) | Frosted glass premium effect |
| `@keyframes` | Testimonials `fadeIn` | Entrance animation for slides |
| `IntersectionObserver` | Scroll animations on 6 element types (`threshold: 0.15`) | Triggers `.visible` class on entry |
| `aspect-ratio: 1/1` | Instagram gallery | Perfect square image cards |
| `transition` | All interactive elements — using `var(--transition-fast/normal/premium)` | Smooth, consistent hover states |
| `transform: scale()` | Image zooms, text pop, Watch Now, Buy Now | Smooth zoom without layout shift |
| `rgba() overlays` | Hero, Sale Banner, Instagram, Shop Banners | Darkening/lightening layers over images |
| `focus-within` | Newsletter form container | Blue ring around whole form on input focus |
| `focus-visible` | Nav links, all anchor elements | Keyboard-only focus ring (`2px dashed var(--clr-primary)`) |
| `will-change` | News cards | Browser performance hint for `transform` + `box-shadow` |
| `range media queries` | Entire stylesheet | Modern `@media (width <= 900px)` syntax |
| `preconnect` | Google Fonts `<link>` | Faster font loading via early connection |
| `loading="lazy"` / `"eager"` | All images | Hero = `eager` (above fold), all others = `lazy` |
| `aria-label` / `aria-labelledby` | Sections, buttons, links, social icons | Screen reader descriptions |
| `aria-haspopup` / `aria-expanded` | Dropdown toggles | ARIA state management via JS |
| `role="menu"` / `role="menuitem"` | Dropdown menus | Correct ARIA semantics |
| `role="group"` + `aria-roledescription` | Testimonial slides | Carousel accessibility pattern |
| `rel="noopener"` | Gallery social links, footer social links | Security on external links |
| `<blockquote>` | Testimonial text | Semantic markup for quoted content |
| `<main>` | Page body wrapper | Landmark for skip-to-content navigation |
| Semantic HTML | Entire page | `<section>`, `<article>`, `<header>`, `<footer>`, `<nav>`, `<main>`, `<blockquote>` |

---

<br/>

# ✍️ How I Built This Project

Every section of this website was planned, structured, and coded manually. The workflow below is how I approached building each component from scratch.

### My Build Workflow

```
I plan the section  →  I write the HTML structure  →  I style it in CSS
       ↓                                                      ↓
I test it in browser  ←  I fix layout issues  ←  I add JS where needed
       ↓
I add accessibility (aria, roles, labels)  →  I test on mobile
```

---

### What I Built Section by Section

| Section | How I Approached It |
|---|---|
| **CSS Token System** | Designed the full `:root` variable architecture myself — named tokens for color, spacing, radius, shadow, and motion |
| **Navbar** | Wrote the fixed header, dropdown CSS, `backdrop-filter` glass effect, and JS aria-toggle logic manually |
| **Hero** | Built the full-viewport image + overlay + anchored text layout with logical CSS properties |
| **About Cards** | Built the 3-column card grid, image zoom on hover, and scroll fade-in logic from scratch |
| **Sale Banner** | Chose the light overlay approach (`rgba(255,255,255,0.85)`), `clamp()` heading, and `scale(1.03)` hover CTA |
| **Features** | Structured the 2-column layout with icon boxes, `<h3>` headings, and `aria-hidden` on decorative icons |
| **Products** | Built the frosted-glass overlay system with `backdrop-filter`, `scale(0.9→1)` pop, and `cubic-bezier` timing |
| **Newsletter** | Wrote the form container, `focus-within` ring, `fa-envelope` icon layout, and accessible hidden label |
| **Shop Banners** | Built the 2×2 grid with bottom-right aligned overlay + BUY NOW with unique `aria-label` per banner |
| **News Cards** | Wrote the `will-change` optimization, `shadow-hover` token, and `translateY(-8px)` lift system |
| **Gallery** | Structured the `aspect-ratio: 1/1` grid, 3-layer hover system, and `rel="noopener"` social links |
| **Testimonials** | Implemented the full ARIA carousel pattern — `role="group"`, `aria-roledescription`, `blockquote` |
| **Location** | Built the contact split header with `aria-labelledby`, iframe `title`, and logical-property grid |
| **Footer** | Designed the `2fr 1fr 1fr` grid, `<h2>` column headings, social button hover, and updated copyright |
| **Responsive System** | Wrote all three breakpoints with modern range query syntax (`width <= 900px`) |
| **JavaScript** | All JS written manually — sticky nav, hamburger + ARIA, dropdown click-outside, slider, observer |

---

<br/>

# 🔀 What I Built Myself

```
┌─────────────────────────────────────────────────────────────┐
│                   PROJECT CONTRIBUTION                      │
│                   100% Built Manually                       │
├─────────────────────────────────────────────────────────────┤
│  CSS token design system   │  Page structure & section plan │
│  Intersection Observer JS  │  Design decisions & color theme│
│  Hover overlay components  │  Content, copy & product data  │
│  Focus-within form ring    │  Image selection & alt text    │
│  Mobile nav + ARIA JS      │  Typography pairing            │
│  Dropdown ARIA toggle JS   │  Layout proportions & spacing  │
│  Range media query system  │  All aria-* attributes         │
│  Grid & Flexbox patterns   │  Semantic HTML document outline│
│  Logical property CSS      │  Debugging & browser testing   │
│  will-change optimizations │  Responsive breakpoint testing │
└─────────────────────────────────────────────────────────────┘
```

> 💡 **Building manually means learning deeply.** Every component — from the `clamp()` heading to the `aria-roledescription` on testimonial slides — was researched, written, and tested by hand. The decisions behind the code are entirely mine.

---

<br/>

# 📚 Key Learnings

### 01 — CSS Logical Properties Change Everything
Replacing `margin-top` with `margin-block-start` and `left` with `inset-inline-start` makes styles writing-mode aware and future-proof. It took discipline to use them consistently, but the code is cleaner for it.

### 02 — A CSS Token System Scales Beautifully
Building a full `:root` design system with named tokens like `--shadow-hover`, `--transition-premium`, and `--clr-primary-hover` meant every component stayed visually consistent. Changing one variable updated the entire site.

### 03 — ARIA Is Not Optional
Adding `aria-haspopup`, `aria-expanded`, `role="menu"`, `role="group"`, `aria-roledescription`, and `aria-labelledby` throughout made the site usable with a keyboard and screen reader. Accessibility is not a separate task — it's part of writing correct HTML.

### 04 — `clamp()` Replaces Multiple Media Query Rules
Using `font-size: clamp(28px, 5vw, 44px)` on the sale banner heading handled fluid scaling across all viewports in one line, without a single breakpoint.

### 05 — `will-change` Is a Precision Tool
Adding `will-change: transform, box-shadow` on news cards gave the browser an early compositing hint for the hover lift effect — making it visibly smoother without adding unnecessary repaint cost.

### 06 — `focus-visible` vs `focus` Matters
Using `a:focus-visible { outline: 2px dashed var(--clr-primary); }` shows the focus ring only for keyboard users, not mouse clicks — exactly the right UX behavior.

### 07 — Range Media Queries Are the Modern Standard
Writing `@media (width <= 900px)` instead of `@media (max-width: 900px)` is the current CSS specification. It reads more naturally and avoids the ambiguity of `min-width`/`max-width` pairs.

### 08 — `loading="eager"` vs `loading="lazy"` Has Real Impact
Setting `loading="eager"` on the hero image (above fold) and `loading="lazy"` on everything else is a simple optimization that meaningfully improves first-contentful-paint without extra tooling.

---

<br/>
<div align="center">

**✦ Author ✦**

**Your Name**
🐙 GitHub: [@your-username](https://github.com/AyeshaAbid892)
💼 LinkedIn: [your-profile](https://www.linkedin.com/in/ayesha-abid33/)
📧 Email: ayeshaa.abid33@gmail.com

---

**Built with curiosity, styled with intention — and understood every step of the way.**

<br/>

![Made with HTML](https://img.shields.io/badge/Made%20with-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Styled with CSS](https://img.shields.io/badge/Styled%20with-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Powered by JS](https://img.shields.io/badge/Powered%20by-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Built Manually](https://img.shields.io/badge/Built-Manually-3d9cd2?style=for-the-badge&logo=checkmarx&logoColor=white)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:a855f7,25:ff6ec7,50:ff9a3c,75:f7df1e,100:3d9cd2&height=150&section=footer&text=Shopamp!%20—%20Fashion%20Meets%20Clean%20Code&fontSize=22&fontColor=ffffff&fontAlignY=65&animation=twinkling" width="100%" />

</div>
