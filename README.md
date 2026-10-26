# Manglan Labs — Open AI for People

Official website for **Manglan Labs**, an open-weights AI research lab based in India dedicated to building accessible machine learning models, training tools, and high-performance open-source frameworks.

![Manglan Labs Design Style](https://github.com/old-droid.png)

## Overview

Manglan Labs builds open-weights AI models and tools designed for high performance on standard hardware. This repository contains the source code for the official Manglan Labs landing page, designed with a sleek, high-contrast monochrome editorial style, subtle micro-interactions, responsive typography, and scroll-triggered visual reveals.

### Key Features

- **Monochrome Editorial Visual System**: Pure high-contrast typography hierarchy, custom bar mark SVG/CSS logotype, and acid accent highlighting (`#d7ff42`).
- **XTRAIN Flagship Section**: Highlights the Numba-powered, CPU-first, pure Python machine learning training framework without C extension requirements.
- **Interactive Terminal Emulator**: Renders real-time installation commands and representative epoch-by-epoch model training output.
- **Responsive Layout**: Designed mobile-first for touch devices, tablets, laptops, and ultra-wide desktop monitors.
- **Restrained Motion Design**: Scroll progress bar, fluid scroll cue, cursor magnet effect on CTAs, and IntersectionObserver scroll reveals.
- **Accessibility & Performance**: Native HTML5 semantic structure, reduced-motion media query support, lightweight CSS/JS footprint, zero external heavy framework dependencies.

---

## Project Structure

```text
/home/ubuntu/manglan/
├── index.html              # Main single-page application and stylesheet
├── manus-routes.json       # Route manifest configuration for deployment
├── app.config.ts           # Metadata configuration including brand asset logo
├── public/
│   └── manus-routes.json   # Public route declarations for static file serving
├── TODO.md                 # Project implementation acceptance criteria
└── README.md               # Project documentation
```

---

## Technology Stack

- **HTML5**: Semantic tags (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`) with structured heading hierarchy.
- **CSS3**: Custom properties (CSS variables), CSS grid, flexbox, clamp fluid typography, balance text wrapping, and high-DPI media queries.
- **JavaScript (ES6+)**: IntersectionObserver for reveal animations, pointer event handlers for CTA magnetic physics, and scroll listener for top progress bar.
- **Python HTTP Server**: Lightweight local web server for development and static delivery.

---

## Quick Start

### Local Development

1. Clone or navigate to the project directory:

   ```bash
   cd /home/ubuntu/manglan
   ```

2. Start a local static HTTP server:

   ```bash
   python3 -m http.server 3000 --bind 0.0.0.0
   ```

3. Open your browser and navigate to:

   ```text
   http://localhost:3000
   ```

---

## Core Product Highlights

### XTRAIN Framework

[XTRAIN](https://github.com/old-droid/XTRAIN) is Manglan Labs' flagship high-performance ML training framework.

- **Numba-Powered**: Pure Python architecture compiled dynamically with JIT compilation.
- **CPU-First**: Native optimization for Intel and AMD processor architectures.
- **Open Source**: MIT licensed for commercial and research applications.

#### Installation & Quick Usage

```bash
pip install numpy scipy numba
python run_model.py --model llm
```

---

## Contact & Links

- **Flagship Repository**: [https://github.com/old-droid/XTRAIN](https://github.com/old-droid/XTRAIN)
- **Email Contact**: [mangalan.ai@proton.me](mailto:mangalan.ai@proton.me)
- **Organization**: Manglan Labs — India's Open-Weights AI Lab

---

*Models built with care by living humans.*
