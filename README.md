# OM Group of Companies - Smart City & Technology Solutions Web App

A premium, responsive, single-page web landing page designed for the **OM Group of Companies** to showcase their smart city infrastructure, security networks, clean energy solar initiatives, and engineering capabilities.

---

## 🚀 Deployed Link
* **Production Deployment**: [om-industries-two.vercel.app](https://om-industries-two.vercel.app)
* **Local Preview**: `http://localhost:8080/`

---

## 🎨 Design Philosophy & Aesthetics

The web page is styled around a high-end, futuristic tech aesthetic:
* **Obsidian Slate Palette**: Backgrounds feature a deep charcoal-blue (`#080C14` to `#0F1626`) mimicking nocturnal smart city screens.
* **Teal & Cyan Glows**: Accent elements and highlights use glowing cyan (`#00F0FF`) and emerald (`#10B981`) colors to reflect clean technology, traffic automation, and intelligence.
* **Glassmorphic Cards**: Content cards feature `backdrop-filter: blur(16px)` and translucent border borders (`rgba(255, 255, 255, 0.08)`) giving the interface a floating, premium depth.
* **Scroll Animation Reveals**: Elements fade and translate upward dynamically as they enter the screen viewport.
* **Optimized Hero Section**: A high-resolution modern skyscraper background photo aligned to `center top/cover` with a customized overlay opacity (`0.25 / 0.65`) and glassmorphic card boundaries to ensure maximum visibility and text contrast.

---

## 💻 Technology Stack

* **Structure**: Semantic **HTML5** (Headings, sections, tags) optimized for SEO and readability.
* **Interactivity**: Vanilla **ES6+ JavaScript** (No heavy framework overhead):
  * **IntersectionObserver API** for scroll-reveal animations.
  * **Dynamic Active Link Tracker** for smooth-scrolling sticky navbar.
  * **Mobile Menu Toggler** (hamburger/cross) for touch devices.
  * **Tab Content Switcher** for the Business Verticals Explorer.
  * **Contact Inquiry Validator** with instant feedback states.
* **Styling**: Vanilla **CSS3** with CSS Variable tokens, custom scrollbar tracks, responsive flexboxes/grids, and fluid media queries.

---

## 📂 Project Structure

```bash
├── assets/
│   ├── logo.png               # Processed golden transparent PNG logo
│   ├── mukesh_jha.png         # Refined white-background portrait
│   ├── hero_background.jpg    # Glass skyscraper background
│   └── extracted_img_...      # Slide illustrations (ITMS, solar, clients, parking)
├── index.html                 # Main website template
├── index.css                  # Custom variables and layout rules
├── index.js                   # Visual and form interaction script
├── .gitignore                 # Excludes system configs, python tools, and logs
├── README.md                  # Project overview (this file)
└── OM.pdf                     # Source presentation document
```

---

## 🛠️ Local Development & Running

To run and preview the website locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/bkj1979/OM_Industries.git
   ```
2. Start a local server (e.g. using Python's built-in HTTP server module):
   ```bash
   python -m http.server 8080
   ```
3. Open your browser and navigate to:
   ```bash
   http://localhost:8080
   ```
