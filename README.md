# 🎨 CSS Codes

A collection of UI components and mini-projects built while learning CSS — covering Flexbox, Grid, transitions, animations, hover effects, and responsive layouts.

---

## 🗂️ Projects Overview

### 🖼️ Photo Gallery
A responsive 9-image photo gallery using **CSS Grid**.
- 3-column grid layout with `grid-template-columns: repeat(3, 1fr)`
- Hover effect: card lifts with `translateY` and box-shadow
- Image zoom on hover using `transform: scale(1.05)`
- `object-fit: cover` for uniform image sizing

---

### 💳 Pricing Card UI
A clean SaaS-style pricing card for a "Pro Plan".
- Centered layout using **Flexbox**
- Feature list with CSS `::before` checkmark (`✓`) pseudo-elements
- CTA button with hover color change + `translateY` lift effect
- Smooth transitions on button hover

---

### 👤 Profile Card
A personal profile card component with avatar, skills, and stats.
- Circular avatar with initials using **Flexbox centering** + `border-radius: 50%`
- Skills displayed as pill-shaped tags (`border-radius: 20px`)
- Stats section (Projects / Followers / Following) with border separators
- Follow button with hover color transition

---

### 🌐 Simple Landing Page
A portfolio-style landing page with navbar and hero section.
- **Navbar** built with Flexbox — logo on left, nav links on right
- Animated nav underline on hover using `::after` pseudo-element + `width` transition
- **Hero section** with centered content and a `fadeIn` CSS animation
- CTA button with background-color and `translateY` hover transitions

---

## 🧠 CSS Concepts Practiced

- **Flexbox** — Navbar layout, card centering, skills row, stats section
- **CSS Grid** — Photo gallery 3-column responsive layout
- **Transitions** — Smooth hover effects on buttons, images, and nav links
- **Animations** — `@keyframes fadeIn` on the landing page hero
- **Pseudo-elements** — `::after` for nav underline animation, `::before` for list checkmarks
- **Transform** — `translateY` for button/card lift, `scale` for image zoom
- **Box Model** — Padding, margin, border-radius, and border styling
- **`object-fit: cover`** — Uniform image display in gallery cards

---

## Tech Stack

- **HTML5**
- **CSS3**
- No frameworks — pure vanilla CSS only

---

## 📁 Folder Structure

```
CSS-codes/
├── Photo Gallery/
│   ├── index.html
│   ├── style.css
│   └── images/
│       ├── photo1.jpg
│       ├── photo2.jpg
│       ├── photo3.jpg
│       └── photo4.jpg
├── PricingCard UI/
│   ├── index.html
│   └── style.css
├── ProfileCard/
│   ├── styledProfileCard.html
│   └── ProfileCard.css
└── SimpleLanding Page/
    ├── index.html
    └── Style.css
```

---

## How to View

No setup needed — just open any `index.html` or `.html` file directly in your browser.

```bash
# Clone the repo
git clone https://github.com/RadhikaKapoor383/CSS-codes.git

# Open any project
open "CSS-codes/Photo Gallery/index.html"
```

---

## Author

**Radhika Kapoor** — [GitHub](https://github.com/RadhikaKapoor383)
