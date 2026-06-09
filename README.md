# Axon Agency — Webflow-Style 5-Page Website

A beautifully crafted, single-page application (SPA) style agency website built with **Tailwind CSS** and vanilla **JavaScript**. Designed to emulate the smooth, animation-rich feel of a **Webflow + CMS** project.

## ✨ Features

- **5 Complete Pages:** Home, Work, Services, Studio, Contact — all with seamless client-side routing.
- **Webflow-Inspired Animations:** Fade-up on scroll, hover lift effects, smooth page transitions.
- **Fully Responsive:** Mobile-first design with a collapsible navigation menu.
- **Dynamic Active State:** Highlights the current page in the navigation bar.
- **Contact Form Simulation:** Interactive form with success feedback (no backend required).
- **Smooth Scrolling & Polish:** Custom scrollbar, glassmorphism header, and subtle gradient backgrounds.

## 🛠️ Tech Stack

- **HTML5 / Tailwind CSS** – Utility-first styling and responsive grid/flex layouts.
- **Vanilla JavaScript** – Client-side routing, intersection observer for scroll animations, DOM manipulation.
- **Font Awesome** – Icon library for social and feature icons.
- **Google Fonts (Inter)** – Modern, clean typography.

## 🚀 How to Run

1. Copy the entire HTML code into a new file named `index.html`.
2. Open the file directly in any modern web browser (Chrome, Firefox, Safari, Edge).
3. No build step, server, or installation required — it runs purely client-side.

> 💡 For the best experience, serve it via a local development server (e.g., VS Code Live Server) to ensure all external assets load correctly.

## 📁 Project Structure

```
index.html        # Single file containing all styles, markup, and logic
```

All pages and interactions are contained within one document — the script handles dynamic page swapping without reloading the browser.

## 📄 Page Overview

| Page      | Description                                 |
|-----------|---------------------------------------------|
| **Home**  | Hero section, brand trust indicators, CTA.  |
| **Work**  | Portfolio grid with project cards.          |
| **Services** | Feature list and development offerings.   |
| **Studio**| Team story, stats, and testimonial.         |
| **Contact** | Contact form with email/studio details.   |

## 🎨 Customization

- **Colors:** Modify Tailwind’s theme classes or replace gradient stops in the `section-bg` class.
- **Content:** Update images (Unsplash URLs), text, and project details directly in the HTML.
- **Animations:** Adjust transition durations in the `.fade-up`, `.hover-lift` CSS rules.
- **Form Behavior:** Edit the `contactForm` submit event inside the `<script>` block.

## 📦 Dependencies (CDN)

- Tailwind CSS
- Font Awesome 6
- Google Fonts (Inter)

All dependencies are loaded via Cloudflare CDN — no local installation required.

## 🧠 Key Script Logic

- **Client-side Routing:** Listens to hash changes and custom data-page clicks; toggles visibility of page containers.
- **Scroll Reveal:** Uses `IntersectionObserver` to add a `.show` class to elements with `.fade-up`.
- **Mobile Menu:** Toggles visibility of the responsive navigation drawer.
- **Active Link Highlight:** Dynamically applies `.active-nav` styling to the current page link.

---

*Built as a demonstration of modern front-end techniques — blending Tailwind utility classes with smooth, Webflow-like interactions.*