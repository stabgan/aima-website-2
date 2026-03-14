# AIMA Exercises — Website v2

Minimalistic, responsive website for exercises from *Artificial Intelligence: A Modern Approach* by Stuart Russell and Peter Norvig.

## What It Does

Presents all 27 chapters of AIMA exercises in a clean, book-like interface with full MathJax support for rendering mathematical notation. Each exercise page features a fixed navigation bar with a dropdown listing all chapters, highlighting the current one.

## Architecture

Pure HTML/CSS static site — no build tools or site generators. Each exercise page is a standalone HTML file with Bootstrap 4 for layout, MathJax for math rendering, and a shared navbar structure. The landing page (`index.html`) uses a custom responsive CSS grid with media queries for 7 breakpoints.

## 🛠 Tech Stack

| | Technology | Purpose |
|---|---|---|
| 🎨 | HTML / CSS | Structure and responsive styling |
| 📐 | Bootstrap 4 | Navbar and grid layout |
| 🔢 | MathJax 2.7 | LaTeX math rendering |
| 🔤 | Font Awesome 4.7 | Icons |
| 📝 | Google Fonts | Lora + Open Sans typography |

## Getting Started

No build step required. Just open `index.html` in a browser, or serve with any static file server:

```bash
python3 -m http.server 8000
# Then open http://localhost:8000
```

## Project Structure

```
├── index.html                  # Landing page / table of contents
├── *_exercise.html             # Individual chapter exercises (27 files)
├── css/clean-blog.min.css      # Custom blog-style CSS
└── figures/                    # SVG diagrams for exercises
```

## ⚠️ Known Issues

- Uses non-standard `<text>` HTML elements in `index.html` (works but not semantic).
- Some exercises still contain raw LaTeX references (`@Author:Year` citation format).
- The `vendor/` directory referenced in some pages does not exist in the repo (CDN fallbacks handle this).

## License

MIT — © Peter Norvig and Kaustabh Ganguly.
