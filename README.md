# POSITIVUS — Agency Landing Page

A modern marketing-agency landing page built with a **SCSS (BEM) architecture** — no CSS framework, no JavaScript framework. The layout includes hero, services, use cases, process, team, reviews, pricing, contact and footer sections.

## Features

- 🎨 Clean agency design with consistent design tokens (variables + mixins)
- 🧩 BEM-style component structure (`blocks/`)
- 📱 Fully responsive, including a mobile overlay navigation
- ♿ Accessible basics: `visually-hidden`, semantic sections
- 🔁 Sass watch mode for live CSS compilation

## Tech Stack

- HTML5
- SCSS / Sass (compiled to CSS)
- BEM naming methodology
- Vanilla JS (minimal, for the mobile menu)

## Getting Started

### Requirements

- Node.js + npm (only for the Sass compiler)

### Installation

```bash
git clone https://github.com/Mykola-Zhmurko/SCSS_POSITIVUS.git
cd SCSS_POSITIVUS
npm install
```

### Development

```bash
npm start
# compiles styles/index.scss → styles/index.css and watches for changes
```

Then serve the folder, e.g.:

```bash
python3 -m http.server 8080
# → http://localhost:8080
```

## Project Structure

```
├── index.html            # Page layout
├── styles/
│   ├── index.scss        # Entry point
│   ├── _variables.scss   # Design tokens (colors, spacing, fonts)
│   ├── _mixins.scss      # Reusable mixins
│   ├── _media.scss       # Responsive breakpoints
│   ├── _globals.scss     # Base styles
│   └── blocks/           # BEM components (header, hero, team, footer, ...)
└── images/               # Logos, icons, team images
```