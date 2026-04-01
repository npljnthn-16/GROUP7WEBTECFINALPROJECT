# Kapee Coffee Shop 

> A multi-page, responsive website for **Kapee**, a fictional local coffee shop brand based in Metro Manila. Built as a group project for the Modern Web Interface Development course.

---

## Project Goals

This project demonstrates the design and development of a complete, production-quality local business website. The goals were to:

- Apply semantic HTML5 structure for accessibility and SEO
- Build a responsive, mobile-first layout using CSS3 Flexbox and Grid
- Implement interactive features including navigation toggles, tabbed content, an image slider, and form validation
- Follow WCAG accessibility guidelines throughout
- Deliver a polished, real-world-ready web interface with a consistent brand identity

---

## Pages & Features

| Page | Description |
|---|---|
| **Home** | Static hero section, scrolling marquee, featured drinks grid, brand story split, and a reviews preview |
| **Menu** | Tabbed menu with 4 categories: Espresso, Cold Drinks, Non-Coffee, and Food — each item displays a photo |
| **Order Now** | Full add-to-cart ordering system with a cart sidebar, quantity controls, and a 3-step checkout flow (delivery/pickup, payment method, confirmation) |
| **Reviews** | Full page with 15+ customer reviews and a link to submit your own |
| **About** | Brand origin story, stats bar, and core values section |
| **Locations** | 8 branch cards across Metro Manila, each with address, hours, and a Google Maps button |
| **Contact** | Split layout with store info and a validated contact form |

---

## Technologies Used

- **HTML5** — Semantic tags (`<header>`, `<main>`, `<section>`, `<footer>`, `<article>`, `<aside>`, `<nav>`) for structure, SEO, and accessibility
- **CSS3** — Custom properties (variables), Flexbox, CSS Grid, Media Queries, CSS animations and transitions. No external CSS framework — all styles written from scratch.
- **Vanilla JavaScript** — Multi-page switcher, mobile hamburger drawer, tabbed content, add-to-cart logic, 3-step checkout flow, and contact form validation
- **Google Fonts** — Cormorant Garamond (display) + DM Sans (body)
- **SVG Icons** — Inline SVGs for all social media links (no icon library dependency)

---

## Accessibility

- Minimum 4.5:1 color contrast ratio maintained across all text elements
- Descriptive `alt` text provided for all informative images
- ARIA roles and labels applied to navigation, tabs, dialogs, and interactive controls
- Keyboard navigable — Escape key closes mobile drawer and checkout overlay
- `aria-live` regions for dynamic content such as form success states

---

## Responsive Design

The site is built **mobile-first** and scales up through two breakpoints:

- **≤ 600px** — Single column layout, stacked forms, centered text throughout
- **≤ 900px** — Hamburger navigation drawer, adjusted grids, stacked split sections
- **> 900px** — Full desktop layout with multi-column grids and sticky cart sidebar

---

## Project Structure

```
kapee/
│
├── index.html          # Complete file website (HTML & CSS + JS)
│
└── img/                # Folder for all menu item photos
    ├── americano.jpg
    ├── avocadotoast.jpg
    ├── brownbutterbananaloaf.jpg
    ├── buttercroissant.jpg
    ├── cappuccino.jpg
    ├── chamomilehoneytea.jpg
    ├── coldbrew.jpg
    ├── cortado.jpg
    ├── darkchocolatechipcookie.jpg
    ├── darkcocoalatte.jpg
    ├── flatwhite.jpg
    ├── grilledchickenpanini.jpg
    ├── hojichalatte.jpg
    ├── icedamericano.jpg
    ├── icedbrownsugarlatte.jpg
    ├── icedlatte.jpg
    ├── kapeeclassic.jpg
    ├── kyotomatcha.jpg
    ├── leadbg.jpg
    ├── mainbg.jpg
    ├── milkandhoneylatte.jpg
    └── nitrocoldbrew.jpg
    ├── quinoagrainbowl.jpg
    ├── saltedcaramelcoldbrew.jpg
    └── storybg.jfif
```

---

## How to Run Locally

No build tools, package managers, or dependencies are required.

**Option 1 — Open directly in browser:**
1. Download or clone this repository
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari)

**Option 2 — Live Server in VS Code (recommended):**
1. Install [VS Code](https://code.visualstudio.com/) and the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
2. Open the project folder in VS Code
3. Right-click `index.html` → **Open with Live Server**
4. The site opens at `http://127.0.0.1:5500`

> **Note:** Option 2 is recommended so that local images in the `img/` folder load correctly in all browsers.



## Deployment

The site is deployed via **GitHub Pages** 

**Live URL:** `[https://npljnthn-16.github.io/GROUP7WEBTECFINALPROJECT]`

## Group Members

| Name | Role |
|---|---|
| *Napili, Jonathan* | Coding and Deployment |
| *Baluncio, Kris Princess* | Menu/Order Page Images |
| *Verdera, Pearl Loriane Joyce* | Wireframes |
| *Dawas, Janz Tricia*| Locations Page |
| *Eliang Rhialine* | Reviews Page|


## Brand Identity

| Property | Value |
|---|---|
| **Brand Name** | Kapee |
| **Tagline** | *Coffee, Crafted.* |
| **Founded** | 2019 (fictional) |
| **Location** | Metro Manila, Philippines |
| **Primary Font** | Cormorant Garamond |
| **Body Font** | DM Sans |
| **Cream** | `#FEFCF7` |
| **Beige** | `#F4EBDA` |
| **Sand** | `#E5CFA8` |
| **Coffee** | `#A87850` |
| **Espresso** | `#6B3F1E` |
