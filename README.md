# Manglan Labs — Open AI for People
<img src="https://private-user-images.githubusercontent.com/196172713/584957763-fc9a68e6-3d9c-4336-96ff-76242e297b86.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3OTMwMzk5MTIsIm5iZiI6MTc5MzAzOTYxMiwicGF0aCI6Ii8xOTYxNzI3MTMvNTg0OTU3NzYzLWZjOWE2OGU2LTNkOWMtNDMzNi05NmZmLTc2MjQyZTI5N2I4Ni5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYxMDI2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MTAyNlQxODMzMzJaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jOTYzZWVhMjQ5NDFjNWI1MmJkNjc0YjYwNGVjNDliYTNhYzlhMzk0ZGYzM2E1YTllYWUwYWZjMDgwZGFkZDI5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.6pxjm3C9FItrTzma0G2EQHGT2mGoytDi58HD-dLMmvE" width="300" alt="Alt text"> 
Official website for Manglan Labs, an open-weights AI research lab based in India dedicated to building accessible machine learning models, training tools, and high-performance open-source frameworks.

-------.
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
