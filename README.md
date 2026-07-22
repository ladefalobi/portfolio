# Lade Falobi — Product Marketing Portfolio

Live site: [portfolio.ladefalobi.com](https://portfolio.ladefalobi.com/)

---

## What this is

My personal portfolio website, built to showcase my work as a Product Marketing Manager with 7+ years across B2B SaaS companies in Africa and globally.

The site covers:
- Six product marketing case studies with metrics, story structure, and embedded work samples
- A career timeline spanning 2022 to present
- Testimonials from founders and direct reports I've worked with
- Personal projects (Marketing For Geeks newsletter, Jumpwag)
- Press features and published writing
- Recognition and awards

---

## Built with

- **Pure HTML and CSS** — no frameworks, no build tools, no dependencies
- **Vanilla JavaScript** — carousel, lightbox, accordion case studies, back-to-top button, all hand-written
- **Google Fonts** — Caveat (handwritten personality) + Inter (body copy)
- **SVG** — hand-drawn dashed dividers between sections, all inline
- **CSS animations** — infinite logo slider, carousel transitions
- **YouTube embeds** — deferred loading for rivva launch and demo videos
- **Netlify** — static hosting with automatic deploys from this repo
- **JSON-LD schema** — structured data for AI and Google search visibility
- **Open Graph + Twitter Card meta tags** — rich previews when shared on LinkedIn, WhatsApp, X

---

## Why I built it this way

I wanted to own the output completely. A single HTML file also means:

- Zero loading overhead from frameworks
- Easy to version control and update directly in GitHub
- Fully portable
- Demonstrates that a marketer can build production-ready web work without being a developer

Most of this site was built collaboratively with Claude through iterative prompting, feedback rounds, and copy refinement. The process is documented implicitly in the commit history. I made all the product and design decisions; Claude handled the implementation.

---

## Structure

```
/
├── index.html          # The entire site — all HTML, CSS, and JS in one file
├── sitemap.xml         # For Google Search Console indexing
├── lade-photo.png      # Hero headshot
├── fig-*.png           # Stick figure illustrations (generated via AI prompt)
├── logo-*.png          # Company logos for the slider
├── mb-*.png/jpg        # Motherboard case study images
├── disha-*.png/jpg     # Disha case study images
├── rivva-*.png/jpg     # rivva case study images
├── crowdr-*.jpg        # Crowdr case study images
├── sk-*.png/gif        # SocialKit case study images
└── README.md           # This file
```

---

---

## Contact

[ladefalobi.netlify.app](https://ladefalobi.netlify.app) · [LinkedIn](https://www.linkedin.com/in/ladefalobi) · [Marketing For Geeks](https://www.marketingforgeeks.com)
