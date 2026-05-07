# Atish Tupe — Portfolio

A modern, responsive, single-page portfolio for **Atish Tupe**, Java Full-Stack Developer.

Built with **pure HTML, CSS, and JavaScript** — zero build tools, zero dependencies. Just open `index.html` in your browser.

## Features

- **Responsive design** — looks great on mobile, tablet, and desktop
- **Dark / Light theme toggle** with persisted preference
- **Animated hero** with typing effect & floating tech-stack icons
- **Glassmorphism + gradient blobs** modern aesthetic
- **Scroll-triggered reveal animations** (Intersection Observer)
- **Animated stat counters**
- **Interactive timeline** for work experience
- **Project showcase** with hover effects
- **Working contact form** (opens user's email client via `mailto:`)
- **Smooth scroll** + active section highlighting in nav
- **Cursor glow** effect on desktop
- **Back-to-top button**

## File Structure

```
Portfolio/
├── index.html              # Main HTML structure
├── styles.css              # All styles, responsive rules, animations
├── script.js               # Theme, animations, typing, form handling
├── ATISH TUPE CV-2025.pdf  # CV (downloadable from the hero)
└── README.md
```

## Run Locally

Just double-click `index.html` — that's it.

Or, for the best dev experience, serve it with a local static server:

```bash
# Python 3
python -m http.server 8000

# Node (npx)
npx serve .
```

Then visit `http://localhost:8000`.

## Deploy

You can deploy this anywhere that serves static files:

- **GitHub Pages** — push to a repo, enable Pages on the `main` branch
- **Netlify** — drag-and-drop the folder onto [app.netlify.com/drop](https://app.netlify.com/drop)
- **Vercel** — `vercel deploy`
- **Cloudflare Pages**, **Surge.sh**, or any static host

## Customizing

| What | Where |
|---|---|
| Personal info / sections | `index.html` |
| Colors / spacing / theme | CSS variables at the top of `styles.css` |
| Typing roles | `roles` array in `script.js` |
| Stat counter values | `data-count` attributes in `index.html` |
| Skills, projects, experience | Their respective sections in `index.html` |

### Theme colors

Edit the `:root` block in `styles.css`:

```css
:root {
  --primary: #6366f1;
  --accent:  #f59e0b;
  --accent-2: #ec4899;
  /* ... */
}
```

## Contact

- **Email:** atishtupe1612@gmail.com
- **Phone:** +91-7028161259
- **LinkedIn:** [atish-tupe-java-developer](https://www.linkedin.com/in/atish-tupe-~-java-developer-85287620a/)
- **Location:** Mumbai, India

---

Crafted with care.
