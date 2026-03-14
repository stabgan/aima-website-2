# AIMA Exercises Website

A responsive, minimalistic website for Artificial Intelligence: A Modern Approach (AIMA) exercises with complete MathJax integration.

## 📖 Overview

This website provides an interactive platform for AIMA textbook exercises, featuring a clean, paper-like design that adapts seamlessly across devices. Built from scratch with pure HTML, CSS, and JavaScript - no frameworks or site generators.

## ✨ Features

- **📱 Fully Responsive Design** - Optimized for phones, tablets, and desktops with adaptive fonts and layouts
- **📄 Paper-like Reading Experience** - Clean, academic styling for comfortable reading
- **🧮 Complete MathJax Support** - Modern MathJax 3.x integration for mathematical notation rendering
- **🧭 Smart Navigation** - Fixed navbar with exercise highlighting and easy page switching
- **📚 Comprehensive Coverage** - All AIMA exercise categories included

## 🛠 Tech Stack

| Technology | Purpose | Version |
|------------|---------|---------|
| ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) | Structure & Content | HTML5 |
| ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) | Responsive Styling | CSS3 |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | Interactive Features | ES6+ |
| ![Bootstrap](https://img.shields.io/badge/-Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white) | UI Components | 5.3.0 |
| ![MathJax](https://img.shields.io/badge/-MathJax-FF6600?style=flat&logo=mathjax&logoColor=white) | Math Rendering | 3.x |
| ![Font Awesome](https://img.shields.io/badge/-Font%20Awesome-528DD7?style=flat&logo=fontawesome&logoColor=white) | Icons | 6.4.0 |

## 📋 Exercise Categories

The website covers all major AIMA topics:

- **Foundations**: Introduction, Agents, Search
- **Problem Solving**: Advanced Search, Game Playing, CSP
- **Knowledge & Reasoning**: Logic, FOL, Inference, Planning
- **Uncertainty**: Probability, Bayes Nets, Decision Theory
- **Learning**: Concept Learning, Bayesian Learning, Reinforcement Learning
- **Communication**: NLP, Robotics, Perception
- **Philosophy**: AI Ethics and Future Considerations

## 🚀 Getting Started

### Prerequisites
- Modern web browser with JavaScript enabled
- Internet connection (for CDN resources)

### Local Development
```bash
# Clone the repository
git clone https://github.com/stabgan/aima-website-2.git
cd aima-website-2

# Serve locally (Python 3)
python -m http.server 8000

# Or with Node.js
npx serve .

# Open in browser
open http://localhost:8000
```

### Deployment
Simply upload all files to any web server. The site is static and requires no server-side processing.

## 🎨 Design Philosophy

- **Minimalistic**: Clean, distraction-free interface focused on content
- **Academic**: Paper-like styling appropriate for educational material
- **Accessible**: High contrast, readable fonts, and semantic HTML
- **Performance**: Lightweight with optimized loading and CDN resources

## 🔧 Recent Improvements

- ✅ **Modernized Dependencies**: Updated to Bootstrap 5.3.0 and MathJax 3.x
- ✅ **Fixed Broken Links**: Replaced missing vendor files with reliable CDN links
- ✅ **Enhanced Performance**: Removed duplicate scripts and optimized loading
- ✅ **Improved Compatibility**: Better cross-browser support and mobile experience

## 📱 Responsive Breakpoints

- **Desktop**: 960px+ (Full layout with side navigation)
- **Tablet**: 569px-959px (Adapted layout)
- **Mobile**: 320px-568px (Simplified mobile-first design)
- **Small Mobile**: <320px (Optimized for small screens)

## 🤝 Contributing

This project is maintained under the supervision of Peter Norvig. The exercises are from the AIMA textbook - this repository only provides the web interface.

### Development Guidelines
- Maintain responsive design principles
- Test across multiple devices and browsers
- Ensure MathJax renders correctly for all mathematical content
- Follow semantic HTML practices

## 📄 License

See [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Peter Norvig** - Project supervision and exercise content
- **AIMA Authors** - Original textbook and exercise material
- **MathJax Team** - Mathematical notation rendering
- **Bootstrap Team** - Responsive framework

---

**Live Demo**: [View Website](https://kaustabhganguly.github.io/aima-website-2)

*Experience the responsive design by viewing on both desktop and mobile devices.*