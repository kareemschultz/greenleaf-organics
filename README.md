<div align="center">

# 🌿 GreenLeaf Organics

### Farm-fresh organic produce, delivered to your door in Georgetown, Guyana.

A fully responsive, hand-authored marketing website for a certified organic food shop — built with HTML5, Tailwind CSS and vanilla JavaScript, deployed on GitHub Pages.

<br>

[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_Site-2D7D46?style=for-the-badge&logo=googlechrome&logoColor=white)](https://kareemschultz.github.io/greenleaf-organics/)
[![Deployment](https://img.shields.io/github/deployments/kareemschultz/greenleaf-organics/github-pages?style=for-the-badge&label=GitHub%20Pages&logo=github)](https://github.com/kareemschultz/greenleaf-organics/deployments)
[![Last Commit](https://img.shields.io/github/last-commit/kareemschultz/greenleaf-organics?style=for-the-badge&color=16a34a)](https://github.com/kareemschultz/greenleaf-organics/commits/main)

<br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=githubpages&logoColor=white)
![Responsive](https://img.shields.io/badge/Mobile-Responsive-2D7D46?style=flat-square&logo=googlechrome&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

</div>

---

## 📸 Preview

<div align="center">

[![GreenLeaf Organics — home page](docs/preview-home.png)](https://kareemschultz.github.io/greenleaf-organics/)

<sub><b>🔗 Live site:</b> <a href="https://kareemschultz.github.io/greenleaf-organics/">kareemschultz.github.io/greenleaf-organics</a></sub>

</div>

---

## ✨ Features

- 🎨 **Modern, hand-drawn aesthetic** — glassmorphism, rounded corners, soft-blob backgrounds and a cohesive green brand palette
- 📱 **Fully responsive** — mobile-first layout with zero horizontal overflow from 390px phones up to widescreen
- 🖼️ **Real photography** — open-licence Unsplash imagery across products, gallery and team
- 🛒 **Interactive product catalogue** — JavaScript filter tabs (Vegetables · Fruits · Dairy & Eggs · Grains & Pulses)
- 🧱 **CSS masonry gallery** with hover overlays
- ✅ **Client-side form validation** on the contact enquiry form
- 🎬 **Scroll-reveal animations** via the `IntersectionObserver` API
- 🔒 **HTTPS** — automatic SSL via GitHub Pages / Let's Encrypt
- ⚡ **No build step** — pure static files, instant load

---

## 🧰 Tech Stack

| Layer | Technology |
|-------|-----------|
| **Markup** | HTML5 — 5 semantic static pages |
| **Styling** | [Tailwind CSS](https://tailwindcss.com) v3 (Play CDN) + custom `css/style.css` |
| **Typography** | [Google Fonts](https://fonts.google.com) — Inter |
| **Interactivity** | Vanilla JavaScript (no framework) |
| **Imagery** | [Unsplash](https://unsplash.com) — open licence |
| **Layout** | CSS Grid · Flexbox · CSS multi-column masonry |
| **Hosting** | [GitHub Pages](https://pages.github.com) (free static hosting + HTTPS) |
| **Version control** | Git |

---

## 📂 Project Structure

```
greenleaf-organics/
├── index.html          # Home — hero, highlights, testimonials
├── products.html       # Catalogue with JS category filter
├── about.html          # Story, journey timeline, team, values
├── gallery.html        # Masonry photo gallery
├── contact.html        # Contact info + validated enquiry form
├── css/
│   └── style.css       # Animations, glassmorphism, components
├── docs/               # README assets
├── .nojekyll           # Serve files as-is (skip Jekyll)
└── README.md
```

---

## 📄 Pages

| Page | Description |
|------|-------------|
| **Home** | Hero banner, "Why GreenLeaf" value cards, weekly highlights, customer testimonials |
| **Products** | Filterable catalogue of 18 organic products across 4 categories with live pricing |
| **About** | Brand story, milestone timeline, team profiles and core values |
| **Gallery** | Masonry image grid of produce, farms and deliveries |
| **Contact** | Address, hours, delivery info and a validated enquiry form |

---

## 🚀 Run Locally

No dependencies or build tooling required:

```bash
git clone https://github.com/kareemschultz/greenleaf-organics.git
cd greenleaf-organics
# Open index.html in your browser, or serve it:
python -m http.server 8000   # then visit http://localhost:8000
```

---

## 🌐 Deployment

Hosted on **GitHub Pages** from the `main` branch (root). Every push to `main` triggers an automatic rebuild; the live site updates within 1–2 minutes at:

> **https://kareemschultz.github.io/greenleaf-organics/**

---

## 📱 Responsive Design

<div align="center">
<img src="docs/preview-mobile.png" alt="GreenLeaf Organics on mobile" width="260">
<br>
<sub>Verified at a 390 px mobile viewport — hamburger nav, stacked grids, full-width form, no horizontal scroll.</sub>
</div>

---

## 🎓 Academic Context

Created for **F3T2 12 — Computing: Authoring a Website**, SCQF Level 6 Foundation Diploma in Business & IT.

- **Student:** Kareem Nurw Jason Schultz
- **Student ID:** 252IFCBR0596

The project demonstrates hand-authored HTML/CSS/JavaScript, responsive design, accessibility-minded markup, and a real-world Git → GitHub Pages deployment workflow.

---

## 📜 License

Released under the [MIT License](LICENSE). Photography courtesy of [Unsplash](https://unsplash.com) under the Unsplash licence.

<div align="center">
<sub>Built with 🌱 in Georgetown, Guyana</sub>
</div>
