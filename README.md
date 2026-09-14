# Elnah's Wigs — Business Landing Page

A responsive single-page website built for Elnah's Wigs, a South African business selling synthetic and human hair wigs. The site showcases products, company info, and provides direct ordering channels via WhatsApp, email, and social media.

## Features

- **Responsive navbar** with scroll-based styling (navbar appearance changes once the user scrolls past the hero section)
- **Mobile hamburger menu** with open/close toggle, and auto-close on link click
- **Scroll-triggered fade-in animations** using the Intersection Observer API — product, about, and contact cards animate into view as the user scrolls, rather than all loading statically
- **Product showcase** — two-tier product section (Synthetic Wigs vs. Human Hair Wigs) with a "Most Popular" badge highlight
- **About section** with company stats and a "why choose us" feature list
- **Direct contact integration** — WhatsApp click-to-chat link, email link, and social media (TikTok, Facebook) links

## Tech Stack

- **HTML5** — semantic section-based structure
- **CSS3** — custom styling (`style.css`)
- **Vanilla JavaScript** — no frameworks; DOM manipulation and browser APIs used directly
- **Font Awesome** — icons (via CDN)
- **Google Fonts** — Poppins typeface (via CDN)

## Key JavaScript Techniques

- `IntersectionObserver` API for performant scroll-triggered animations (rather than listening to scroll events directly for visibility checks)
- Event delegation and class toggling for the mobile navigation menu
- Scroll position detection for dynamic navbar styling

## How to Run

1. Clone the repository:
   ```
   git clone https://github.com/RifumoMathebula/Hair-website.git
   ```
2. Open `index.html` directly in a browser — no build step or server required

## What I Learned

Building this project helped me practice:
- Structuring a multi-section responsive landing page
- Implementing mobile-friendly navigation patterns
- Using the Intersection Observer API for scroll-based animation
- Building real-world business features like click-to-WhatsApp ordering links
