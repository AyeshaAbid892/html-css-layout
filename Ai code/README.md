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
| 🖼️ **Full-Viewport Hero** | 100vh background image with `rgba(240,240,235,0.45)` overlay and brand headline |
| 🃏 **About Us Cards** | 3-column grid cards with image zoom on hover (`scale(1.05)`) |
| 💥 **Sale Banner** | Full-width 800px promotional section with `rgba(50,50,80,0.5)` overlay and CTA |
| ⚙️ **Features Section** | 2-column layout with icon-bordered feature highlights (Sale, Delivery, Clients, Warranty) |
| 👕 **Product Grid** | 2×2 product cards with frosted-glass hover text overlay |
| 📧 **Newsletter Form** | Inline email subscription with `focus-within` ring and SUBSCRIBE button |
| 🗂️ **Shop Banners** | 2×2 image banner grid with hover overlay + Buy Now |
| 📰 **Latest News** | 3-column cards with `translateY(-8px)` lift-on-hover + deep shadow |
| 📷 **Last Collection Gallery** | 3×2 square Instagram-style grid with social icon overlay (Facebook, Twitter, Instagram) |
| 💬 **Testimonial Slider** | JS-powered carousel with `fadeIn` animated slide transitions (Markus Grecho, Sara Mills) |
| 📍 **Store Location** | Split layout — store photo + contact info (email/phone) + embedded Google Map (Manhattan, NY) |
| 🔗 **Footer** | 3-column grid (`2fr 1fr 1fr`) with brand description, News links, Shop links, and social buttons |
| 🎞️ **Scroll Animations** | Intersection Observer (`threshold: 0.15`) fades elements in as they enter the viewport |

---

<br/>

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic structure — `<header>`, `<section>`, `<article>`, `<footer>`, `<nav>` |
| **CSS3** | Custom properties, Flexbox, Grid, transitions, keyframe animations |
| **Vanilla JavaScript** | Sticky navbar (`.scrolled`), hamburger toggle (`.open`), testimonial slider, scroll animations |
| **Google Fonts** | `Montserrat` (headings, weight 400/600/700) + `Open Sans` (body text, weight 400/600) |
| **Font Awesome 6** | Icons for features, social media links, navigation caret, and UI elements |
| **Google Maps Embed** | Embedded store location iframe — Manhattan, New York (`z=13`) |
| **Unsplash CDN** | External stock images for About Us, News, Banners, and Testimonials |
| **Claude AI** | Component design assistance, CSS architecture, animation logic |

---

<br/>

# 🎨 UI/UX Breakdown

### 🧭 Navbar

```
Position: fixed  |  Height: 64px (--nav-height)  |  Z-index: 1000
──────────────────────────────────────────────────────────────────────
│ shopamp!   HOME   LIVE DEMO ▾   LIVE DEMO BLOCKS ▾  [Buy Now] │
──────────────────────────────────────────────────────────────────────
```

- Background transitions from transparent → `box-shadow: 0 2px 12px rgba(0,0,0,0.12)` via `.scrolled` class toggled at `scrollY > 60`
- Dropdown menus use CSS-only hover: `opacity 0→1` + `translateY(6px)→0` with `border-top: 2px solid var(--primary)`
- On mobile (`≤640px`): hamburger toggles `.open`, sliding the nav panel from `translateY(-110%) → translateY(0)`
- Hamburger `.active` state animates spans: rotate ±45° for X icon

## `Visual Reference`

<img width="1253" height="49" alt="Screenshot 2026-06-04 at 5 12 46 PM" src="https://github.com/user-attachments/assets/e968ed54-7c9d-4539-820a-b776c7b5631d" />

---

### 🖼️ Hero Section

```
Height: 100vh  |  min-height: 560px  |  margin-top: var(--nav-height)
Background: Image.jpg  |  Overlay: rgba(240,240,235,0.45)
┌────────────────────────────────────────────────┐
│                                                │
│                                                │
│  Clothing                                      │
│  Store                   ← bottom-left anchor  │
│  Clothing Website Template                     │
└────────────────────────────────────────────────┘
```

- `object-fit: cover` + `object-position: center top` keeps image sharp at every viewport
- Text anchored with `position: absolute; bottom: 80px; left: 48px`
- Hero title: `Montserrat`, `3.8rem`, `font-weight: 700`, `color: var(--dark) #222`
- Hero subtitle: `font-size: 0.95rem`, `color: var(--primary) #3d9cd2`, `font-weight: 600`

## `Visual Reference`

<img width="1322" height="671" alt="Screenshot 2026-06-04 at 5 13 44 PM" src="https://github.com/user-attachments/assets/c7e4dd27-bc3d-4629-aea7-e54e7160a0b3" />

---

## 🃏 About Us Section

```
Background: #ffffff  |  Layout: 3-column CSS Grid  |  Gap: 32px
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
| Image container | `height: 200px` · `overflow: hidden` · `border-radius: var(--radius) 4px` |
| Image zoom on hover | `transform: scale(1.05)` · `transition: 0.5s ease` |
| Card label | `font-size: 0.78rem` · `text-transform: uppercase` · `color: var(--light-text) #888` · `letter-spacing: 1px` |
| Card heading | `font-family: Montserrat` · `color: var(--primary) #3d9cd2` · `font-weight: 600` |
| Body text | `font-size: 0.88rem` · `color: var(--gray-text) #555` · `line-height: 1.65` |
| "Learn more >" link | `color: #555` → hover `color: var(--primary)` transition |
| Scroll animation | Starts `opacity: 0` + `translateY(24px)` → `.visible` fades in via Intersection Observer |

**Card content breakdown:**

```
Card 1 — Prices
  Label:   "Prices"
  Heading: "Best prices"
  Text:    Monthly discounts and sales on certain categories.
  Image:   Unsplash — photo-1441986300917-64674bd600d8 (store interior)

Card 2 — Trends
  Label:   "Trends"
  Heading: "Newest trends"
  Text:    Latest fashionable clothes + style magazines.
  Image:   Unsplash — photo-1558769132-cb1aea458c5e (clothing display)

Card 3 — Collections
  Label:   "Collections"
  Heading: "Previous collections"
  Text:    Best pieces from past collections at huge discounts every Saturday.
  Image:   Unsplash — photo-1567401893414-76b7b1e5a7a5 (clothing rack)
```

**Responsive behaviour:**
- `≤900px` → `grid-template-columns: 1fr` — all 3 cards stack vertically

## `Visual Reference`

<img width="1122" height="506" alt="Screenshot 2026-06-04 at 5 22 48 PM" src="https://github.com/user-attachments/assets/85959a4e-333b-4684-b8ea-b1e731222ae4" />


---

## 💥 Sale Banner (70% OFF Section)

```
Height: 800px  |  Background: Image 1.jpg  |  Overlay: rgba(50,50,80,0.5)
┌──────────────────────────────────────────────────────┐
│                                                      │
│            WE ARE GLAD TO SEE YOU                    │
│                                                      │
│         SALE TO -70% LAST 2 DAYS                     │  ← color: var(--primary) #3d9cd2
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
| Pre-text "WE ARE GLAD TO SEE YOU" | `font-size: 0.8rem` · `letter-spacing: 3px` · `opacity: 0.85` · `text-transform: uppercase` |
| Main heading "SALE TO -70% LAST 2 DAYS" | `font-family: Montserrat` · `font-size: 2.6rem` · `color: var(--primary)` · `font-weight: 700` |
| "Watch Now" button | `padding: 12px 36px` · `background: var(--primary)` · `border-radius: 30px` · hover lifts `translateY(-2px)` |

> The heading color is intentionally `var(--primary)` blue — not white — to create contrast against the dark overlay and make the sale amount the visual focal point.

## `Visual Reference`

<img width="1220" height="399" alt="image" src="https://github.com/user-attachments/assets/c0db1b53-1ffd-4b2c-af70-b6e92f49dafa" />

---

### ⚙️ Features Section

```
Background: var(--bg-light) #f0f2f7  |  Layout: 2-column CSS Grid  |  Gap: 60px
┌───────────────────────┬────────────────────────────────────┐
│  FEATURES             │  [tag] Sale      [truck] Delivery  │
│  Features Our         │                                    │
│  Store                │  [heart] Clients [thumb] Warranty  │
└───────────────────────┴────────────────────────────────────┘
```

- Left column: label `FEATURES` (`0.75rem`, `letter-spacing: 2.5px`) + heading `Features Our Store` (`2.2rem`, `font-weight: 700`, `color: var(--dark)`)
- Right column: `grid-template-columns: 1fr 1fr`, 4 feature items
- Each `.feature-item`: `display: flex`, icon box (`44px × 44px`, `border: 1.5px solid var(--primary)`, `border-radius: 4px`) + heading + description
- Icons used: `fas fa-tag`, `fas fa-truck`, `fas fa-heart`, `fas fa-thumbs-up`
- Scroll animation: `opacity: 0` + `translateY(20px)` → `.visible`

## `Visual Reference`

<img width="1219" height="196" alt="image" src="https://github.com/user-attachments/assets/32fc36e0-e32f-474a-8b28-d91cd1d92102" />


---

### 👕 Product Section

```
Grid: 2 columns × 2 rows  |  Card height: 320px
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

| Image | Name | Price |
|---|---|---|
| Image 2.jpg | SHIRT | $69.99 |
| Image 3.jpg | LIGHT SHIRT | $89.99 |
| Image 4.jpg | JACKET | $129.99 |
| Image 5.jpg | DENIM SHIRT | $179.99 |

- Product name: `font-size: 0.8rem` · `font-weight: 600` · `color: var(--primary)` · `letter-spacing: 1.5px` · uppercase
- Product price: `font-size: 0.95rem` · `color: var(--gray-text) #64748b`

## `Visual Reference`

<img width="1211" height="672" alt="Screenshot 2026-06-04 at 5 14 53 PM" src="https://github.com/user-attachments/assets/8a7ba973-9b3e-4ca7-8d1d-26a5e2b6063a" />

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

- Wrapper: `display: flex; flex-direction: column; align-items: center; gap: 20px`
- Title: `font-family: Montserrat`, `font-size: clamp(1.8rem, 4vw, 2.4rem)`, `color: var(--app-primary)`, `font-weight: 500`
- Meta row: `justify-content: space-between` — "Subscribe Now" (bold, dark) + "* Invite a friend and get a discount - 10%" (muted)
- Form: `display: flex`, `border: 1px solid var(--app-border)`, `border-radius: 4px`, `overflow: hidden`
- `focus-within` applies `border-color: var(--app-primary)` + `box-shadow: 0 0 0 3px rgba(59,130,246,0.15)` ring around the whole form
- Icon: `fas fa-search` in `color: #94a3b8`
- Submit button: `padding: 0 24px`, white bg, `color: var(--app-primary)`, `border-left: 1px solid #f1f5f9`, `font-weight: 700`, uppercase

## `Visual Reference`

<img width="1057" height="187" alt="image" src="https://github.com/user-attachments/assets/bc11edc8-0a11-4205-a932-352b5d48a88f" />


---

## 🗂️ Shop Banners Section

```
Layout: 2×2 CSS Grid  |  No gap  |  Banner height: 280px
┌──────────────────────┬──────────────────────┐
│  [Women Banner]      │  [Collection Banner] │
│  item!  [BUY NOW]    │  item!  [BUY NOW]    │
├──────────────────────┼──────────────────────┤
│  [Style Banner]      │  [Fashion Banner]    │
│  2em!   [BUY NOW]    │  2em!   [BUY NOW]    │
└──────────────────────┴──────────────────────┘
```

- Each `.banner-card`: `position: relative`, `overflow: hidden`, `height: 280px`
- On hover: image zooms `scale(1.05)` + overlay fades in (`rgba(0,0,0,0.35)`)
- Overlay aligns to `flex-end / flex-end` (bottom-right) with `padding: 20px 24px`
- "BUY NOW" button: `background: var(--primary)`, `border-radius: var(--radius)`, `font-size: 0.78rem`, `letter-spacing: 1px`
- Scroll animation applied: `opacity: 0` + `translateY(20px)` → `.visible`

**Unsplash image sources:**

| Position | Unsplash Photo ID |
|---|---|
| Banner 1 | photo-1525507119028-ed4c629a60a3 |
| Banner 2 | photo-1567401893414-76b7b1e5a7a5 |
| Banner 3 | photo-1512436991641-6745cdb1723f |
| Banner 4 | photo-1490481651871-ab68de25d43d |


## `Visual Reference`

<img width="1057" height="486" alt="image" src="https://github.com/user-attachments/assets/36a14154-ce7e-4804-91f4-8ddbd99f86ec" />

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
  └── .news-img-wrap  (height: 190px · overflow: hidden · bg: #000)
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
  will-change: transform, box-shadow;
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
| 1 | Work Mode | Unsplash `photo-1441986300917-64674bd600d8` |
| 2 | New Collections | Unsplash `photo-1558769132-cb1aea458c5e` |
| 3 | Our Stores | Unsplash `photo-1567401893414-76b7b1e5a7a5` |

**Responsive:** Collapses to single column at `≤900px`

## `Visual Reference`

<img width="1261" height="394" alt="Screenshot 2026-06-04 at 5 25 34 PM" src="https://github.com/user-attachments/assets/f93a7629-e9b3-4584-a280-d818a1ecabed" />


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
.collection-label { font-size: 1.8rem; font-weight: 700; color: var(--primary-accent) #3b82f6; }
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
              transition: all 0.4s cubic-bezier(0.25, 1, 0.5, 1)
```

**Social icons on each image:**

Each `.insta-item` overlay contains 3 circular white buttons with `gap: 12px`:
- `fab fa-facebook-f` → Facebook (aria-label: "Share on Facebook")
- `fab fa-twitter` → Twitter (aria-label: "Share on Twitter")
- `fab fa-instagram` → Instagram (aria-label: "Follow us on Instagram")

```css
.social-icon {
  width: 42px; height: 42px;
  border-radius: 50%;
  background: #fff;
  color: var(--primary-accent) #3b82f6;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}
/* On icon hover → fills blue, lifts up */
.social-icon:hover {
  background: var(--primary-accent);
  color: #fff;
  transform: translateY(-4px);
  box-shadow: 0 6px 16px rgba(59,130,246,0.35);
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

<img width="1156" height="669" alt="Screenshot 2026-06-04 at 5 26 34 PM" src="https://github.com/user-attachments/assets/eae4ffdf-7f46-444f-97a7-5d22d27d34cc" />

---

### 💬 Testimonials Slider

```
Max-width: 700px  |  Centered  |  JS-controlled  |  min-height: 300px
◉  ←  [Avatar]  Markus Grecho / Sara Mills  →  ◉
          "Review text..."
```

- `display: none / block` toggle on `.active` class
- `@keyframes fadeIn` animates each incoming slide (`opacity 0→1`, `translateY(10px)→0`, `0.5s ease`)
- Arrow buttons: `position: absolute`, `top: 50%`, `font-size: 1.3rem`, `color: #ccc` → hover `color: var(--primary)`
- `.testi-prev { left: -48px }` · `.testi-next { right: -48px }`

**Two testimonial slides:**

| Slide | Name | Role | Image Source |
|---|---|---|---|
| 1 | Markus Grecho | Clients | Unsplash `photo-1544005313-94ddf0286df2` |
| 2 | Sara Mills | Clients | Unsplash `photo-1534528741775-53994a69daeb` |

- Avatar: `width: 72px`, `height: 72px`, `border-radius: 50%`, `border: 3px solid #eee`
- Name: `Montserrat`, `1rem`, `font-weight: 700`, `color: var(--dark)`
- Role: `0.82rem`, `color: var(--light-text) #888`, `margin-bottom: 18px`
- Text: `0.9rem`, `color: var(--gray-text) #555`, `line-height: 1.75`

## `Visual Reference`

<img width="1010" height="424" alt="Screenshot 2026-06-04 at 5 16 40 PM" src="https://github.com/user-attachments/assets/8fc60004-4b0e-43e4-baff-544194c7e1df" />

---

### 📍 Location Section

```
Background: #ffffff  |  Padding: 60px 0
┌──────────────────────────┬──────────────────────────┐
│  Email                   │  Phone                   │
│  company@mobirise.com    │  +573 1235 5324          │
└──────────────────────────┴──────────────────────────┘
┌──────────────────┬──────────────────────────────────┐
│   Store Photo    │   Embedded Google Map iframe      │
│  (object-fit)    │      Manhattan, New York z=13     │
│  height: 400px   │      height: 400px               │
└──────────────────┴──────────────────────────────────┘
```

- Contact header: `grid-template-columns: repeat(2, 1fr)` split for email (left) and phone (right)
- Contact label: `Montserrat`, `1.1rem`, `font-weight: 700`, `color: var(--text-dark) #1e293b`
- Contact link: `color: var(--brand-primary) #3b82f6`, hover → `#1d4ed8`
- Location grid: `grid-template-columns: repeat(2, 1fr)`, `box-shadow: 0 4px 20px rgba(0,0,0,0.05)`, `border-radius: 4px`, `overflow: hidden`
- Store photo: Unsplash `photo-1441986300917-64674bd600d8` · `object-fit: cover`
- Map: Google Maps embed, `loading="lazy"`, `referrerpolicy="no-referrer-when-downgrade"`


## `Visual Reference`

<img width="1070" height="532" alt="Screenshot 2026-06-04 at 5 17 14 PM" src="https://github.com/user-attachments/assets/98290df3-94d7-4788-97e1-257a0f4bd35c" />


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
   © Copyright 2019 Mobirise – Clothing Website Template – All Rights Reserved
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
| Logo `.footer-logo` | `font-family: Montserrat` · `font-size: 1.6rem` · `color: var(--primary) #3d9cd2` · `font-weight: 700` |
| Description `.footer-desc` | `font-size: 0.85rem` · `color: var(--gray-text) #555` · `line-height: 1.75` · brand copy about the store |
| Social buttons | 3 circular bordered buttons — Facebook (`fab fa-facebook-f`), Twitter (`fab fa-twitter`), Instagram (`fab fa-instagram`) |

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

**Link hover:** `color: var(--gray-text) #555` → `color: var(--primary)` with `0.3s ease` transition

**Footer bottom bar:**

```css
.footer-bottom {
  border-top: 1px solid #dce0e8;
  padding: 20px 24px;
  text-align: center;
}
/* © Copyright 2019 Mobirise – font-size: 0.82rem · color: var(--light-text) #888 */
```

**Responsive behaviour:**
- `≤900px` → `grid-template-columns: 1fr 1fr` · brand column spans full width (`grid-column: 1 / -1`)
- `≤640px` → `grid-template-columns: 1fr` · all columns stack vertically


## `Visual Reference`

<img width="1233" height="337" alt="Screenshot 2026-06-04 at 5 27 53 PM" src="https://github.com/user-attachments/assets/e3f47f19-dec0-4ca7-9539-c425cd82f97d" />


---


## `YouTube URL :` https://youtu.be/Tcv4vhj-2dI


<br/>

# 🎞️ Animations & Styling

### CSS Custom Properties (Design Tokens)

```css
:root {
  --primary:    #3d9cd2;   /* Main blue — headings, links, accents */
  --accent:     #00b5e2;   /* Lighter blue for highlights          */
  --dark:       #222;      /* Body text                            */
  --gray-text:  #555;      /* Secondary text                       */
  --light-text: #888;      /* Muted/tertiary text                  */
  --bg-light:   #f0f2f7;   /* Alternating section backgrounds      */
  --white:      #fff;
  --nav-height: 64px;
  --radius:     4px;
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
| About Cards | Image zoom `scale(1.05)` · `transition: 0.5s ease` |
| Product Cards | Frosted overlay (`backdrop-filter: blur(2px)`) + `rgba(255,255,255,0.25)` + text `scale(0.9→1)` |
| News Cards | `translateY(-8px)` lift + `box-shadow: 0 20px 38px rgba(0,0,0,0.22)` |
| Instagram Items | Image zoom `scale(1.06)` + `opacity 0.85` + dark overlay + social icon bounce from `translateY(12px) scale(0.92) → 0` |
| Shop Banners | Zoom `scale(1.05)` + overlay `rgba(0,0,0,0.35)` fade + Buy Now button reveal |
| Nav Dropdowns | `opacity 0→1` + `translateY(6px)→0` |
| Footer Social Buttons | Background fill + `border-color: var(--primary)` transition |

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

### Sticky Navbar Scroll Logic

```javascript
window.addEventListener('scroll', () => {
  const nav = document.getElementById('navbar');
  nav.classList.toggle('scrolled', window.scrollY > 60);
});
```

---

<br/>

# 🧠 HTML & CSS Concepts Used

| Concept | Used In | How It Was Applied |
|---------|---------|-------------------|
| `CSS Grid` | Products, About, News, Banners, Footer, Location | Multi-column responsive layouts |
| `Flexbox` | Navbar, Features, Newsletter, Footer socials | Alignment and spacing |
| `position: fixed` | Navbar | Keeps nav visible during scroll with `z-index: 1000` |
| `position: absolute` | Hero text, product overlay, banner overlay, sale content | Layered content over images |
| `object-fit: cover` | Hero, sale banner, all card images, location photo | Fills containers without distortion |
| `CSS custom properties` | Entire stylesheet — `--primary`, `--bg-light`, `--transition`, etc. | Global theming and consistency |
| `@keyframes` | Testimonials `fadeIn` | Entrance animation for slides |
| `backdrop-filter: blur()` | Product hover overlay (`blur(2px)`) | Frosted glass premium effect |
| `IntersectionObserver` | Scroll animations (`threshold: 0.15`) | Triggers `.visible` class on entry |
| `transition` | All interactive elements | Smooth hover state changes |
| `aspect-ratio: 1/1` | Instagram gallery | Perfect square image cards |
| `transform: scale()` | Image zooms, text pop, social icon bounce | Smooth zoom without layout shift |
| `rgba() overlays` | Hero, Sale Banner, Instagram, Shop Banners | Darkening layers over images |
| `clamp()` | Newsletter title font-size | Fluid responsive typography |
| `focus-within` | Newsletter form | Blue focus ring on whole container |
| `inset: 0` | Overlay layers throughout | Full-cover positioning shorthand |
| Semantic HTML | Entire page | `<section>`, `<article>`, `<header>`, `<footer>`, `<nav>` |
| `aria-*` attributes | Navbar, gallery social icons, newsletter form, location map | Accessibility for screen readers |
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
| **Product card hover overlay** | Asked AI to build the frosted-glass overlay system with `backdrop-filter: blur(2px)` and centered text pop animation (`scale(0.9→1)`) |
| **Intersection Observer setup** | Described the scroll fade-in effect I wanted; AI wrote the observer logic and `.visible` class pattern with `threshold: 0.15` |
| **Newsletter form layout** | Asked for an inline form with icon + input + button sharing one container and a `focus-within` ring |
| **Instagram gallery overlay** | Requested the social icon bounce-in effect — AI implemented the `translateY(12px) scale(0.92) → 0` combo |
| **News card hover lift** | Described the "premium lift" effect; AI generated the `translateY(-8px)` + `box-shadow: 0 20px 38px` combination with `will-change` optimization |
| **CSS variable architecture** | Asked AI to organize all colors, shadows, and transitions into a single `:root` block |
| **Mobile hamburger menu** | AI wrote the JS toggle logic and the `transform: translateY(-110%)` slide-in for the mobile nav panel |
| **Responsive media queries** | Asked AI to write breakpoints at `900px` and `640px` based on the existing grid structure |
| **Location section layout** | AI built the two-column contact header split + location grid with `grid-template-columns: repeat(2, 1fr)` |

---

### Prompts I Actually Used

> *"Create a product card component where hovering shows a frosted-glass overlay in the center of the image with the product name. The text should scale from 0.9 to 1 on hover. The image should zoom slightly."*

> *"Write an Intersection Observer in vanilla JS that adds a `.visible` class to any element with `.card`, `.product-card`, or `.news-card` when 15% of it enters the viewport."*

> *"Build a newsletter form where the search icon, email input, and submit button all sit inside one bordered container. Add a blue focus ring around the whole form when the input is active."*

---

### What I Decided Myself

- The overall page structure and section order
- Which sections to include and what content to put in each
- Color palette (`#3d9cd2` blue as the brand primary, `#f0f2f7` for alternate backgrounds)
- Product names, prices, and copy (Shirt $69.99, Light Shirt $89.99, Jacket $129.99, Denim Shirt $179.99)
- Typography pairing (`Montserrat` headings + `Open Sans` body)
- Layout proportions and spacing decisions (`gap: 32px` cards, `gap: 48px` footer)
- Which hover effects made sense for which sections
- Image selection (local files for hero/sale/products, Unsplash CDN for about/news/banners/testimonials)
- All `aria-label` attributes and semantic HTML structure
- Contact details, footer copy, and link text

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
│ Location section split   │ Aria labels & accessibility   │
└──────────────────────────┴──────────────────────────────┘
```

> 💡 **Using AI doesn't mean not learning.** Every snippet generated was reviewed, tested, modified, and understood before being added to the project. AI accelerated the process — the thinking behind the project was entirely mine.

---

<br/>

# 📚 Key Learnings

### 01 — CSS Grid + Flexbox Together
Using Grid for page-level sections (`grid-template-columns: 2fr 1fr 1fr` in footer, `repeat(3, 1fr)` in news) and Flexbox inside components (navbar, newsletter form) gave me clarity on when to use each. Grid = two-dimensional layout. Flexbox = one-dimensional alignment.

### 02 — CSS Custom Properties are Game Changers
Defining `--primary: #3d9cd2`, `--transition: 0.3s ease`, and `--shadow: 0 4px 18px rgba(0,0,0,0.10)` as variables meant changing the brand color in one place updated the entire site instantly.

### 03 — Intersection Observer is More Efficient Than Scroll Events
The `IntersectionObserver` API fires only when elements cross a `threshold: 0.15` — far more performant than attaching listeners to the scroll event which fires constantly.

### 04 — `position: absolute` + `inset: 0` is the Overlay Pattern
Building product overlays, hero text, sale content, and banner CTAs made me deeply comfortable with stacking contexts. `inset: 0` shorthand became my go-to for full-cover layers like `.sale-overlay`, `.insta-overlay`, and `.product-hover-overlay`.

### 05 — `object-fit: cover` is Non-Negotiable for Images
Without it, images stretch or squish inside containers. With it, every photo — from the 100vh hero (`object-position: center top`) to the 190px news card images — looks intentional and well-composed.

### 06 — Semantic HTML Costs Nothing and Gains Everything
Using `<section>`, `<article>`, `<header>`, `<nav>`, and `<footer>` with `aria-label` and `aria-labelledby` attributes makes the page meaningful to screen readers and search engines — at zero extra effort.

### 07 — How to Use AI Without Losing the Learning
Describing exactly what I wanted (e.g. frosted-glass overlay with `backdrop-filter`, cubic-bezier bounce animation), then reading and understanding the output before using it, meant AI made me faster — not dependent. The key is using it as a tool, not a shortcut around understanding.

---

<br/>
<div align="center">

**✦ Author ✦**

**Your Name**
🐙 GitHub: [@your-username](https://github.com/AyeshaAbid892)
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
