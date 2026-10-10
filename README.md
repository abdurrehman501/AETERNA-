# AETERNA — Botanical Haute Horlogerie

A responsive, animation-driven concept website for **AETERNA**, a fictional ultra-luxury watch brand. Built as a single static HTML file with a deep forest-green and champagne-gold palette, smooth scrolling and scroll-triggered motion.

> **Note:** This is a portfolio demonstration. The brand, products, address, email and all content are fictional, and the contact form does not send any data.

**Live Demo:** https://YOUR-SITE-NAME.netlify.app

![AETERNA homepage preview](screenshot.png)

## Features

- **Animated preloader** with a live percentage counter
- **Smooth scrolling** using Lenis, synced with GSAP ScrollTrigger
- **Scroll-triggered animations** on the hero, collection cards, heritage timeline and quotes
- **Custom cursor** with a hover-reactive follower (desktop with a mouse only)
- **Magnetic buttons** that follow the pointer
- **Collections section** with three watch illustrations drawn as inline SVG, so no external images are needed
- **Sections:** hero, key specifications, collections, craftsmanship, heritage timeline, philosophy, contact
- **Contact form** with client-side validation (demo only, no backend)
- **Fully responsive** with layouts for mobile, tablet and desktop

## Built With

- HTML5 and CSS3 (custom properties, grid, flexbox)
- Vanilla JavaScript (ES6+)
- [GSAP 3.12](https://gsap.com/) and ScrollTrigger
- [Lenis 1.0.19](https://github.com/darkroomengineering/lenis) for smooth scrolling
- Google Fonts: Cinzel Decorative, Playfair Display, Space Grotesk, Plus Jakarta Sans

## Getting Started

No build step or dependencies to install.

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
   ```
2. Open the folder and double-click `index.html`, or serve it locally:
   ```bash
   npx serve .
   ```

An internet connection is needed for the CDN scripts and Google Fonts.

## Project Structure

```
├── index.html     # Markup, styles and scripts in one file
├── README.md
├── screenshot.png # Homepage preview
└── .gitignore
```

## Colour Palette

| Role | Hex |
|---|---|
| Forest | `#082017` |
| Deep forest | `#020705` |
| Gold | `#D4AF37` |
| Champagne gold | `#E5C558` |

## Possible Improvements

- Connect the contact form to a real backend or a service such as Formspree
- Replace the SVG illustrations with product photography
- Add a reduced-motion mode for users who prefer less animation
- Improve accessibility labels and keyboard navigation

## Deployment

Deployed on Netlify directly from the `main` branch. Every push updates the live site.

## License

Released for portfolio and educational purposes.
