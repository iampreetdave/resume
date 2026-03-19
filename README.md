# Resume — Preet Dave

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

> A sleek, animated personal portfolio and resume website with a neural network background.

## About

A modern, single-page portfolio website built with pure HTML, CSS, and JavaScript. Features a dark-themed design with an animated neural network canvas background, smooth scroll animations, and a fully responsive layout. Showcases skills, experience, projects, and contact information for an AI-ML Engineer profile.

## Tech Stack

- **HTML5** — semantic markup and structure
- **CSS3** — custom properties, grid/flexbox layouts, animations, and responsive design
- **JavaScript** — Canvas API for neural network animation, Intersection Observer for scroll effects

## Features

- **Animated neural network background** using HTML5 Canvas
- **Dark theme** with subtle grid overlay and glassmorphism effects
- **Responsive design** — works on mobile, tablet, and desktop
- **Smooth scroll animations** with Intersection Observer API
- **Sections:** Hero, About, Skills, Experience, Projects, Certifications, Contact
- **Interactive elements** — hover effects, animated skill bars, project cards
- **No external frameworks** — pure vanilla HTML/CSS/JS

## Getting Started

### Prerequisites

- A modern web browser

### Installation

```bash
git clone https://github.com/iampreetdave/resume.git
cd resume
```

### Run

Open `index.html` in your browser, or serve locally:

```bash
npx serve .
```

**Live:** [https://iampreetdave.github.io/resume/](https://iampreetdave.github.io/resume/)

## How It Works

The page is a single `index.html` file with embedded CSS and JavaScript. On load, a Canvas element renders an animated neural network (nodes connected by lines that respond to proximity). The Intersection Observer API triggers fade-in animations as sections scroll into view. All styling uses CSS custom properties for consistent theming.

## Project Structure

```
resume/
├── index.html    # Complete portfolio (HTML + CSS + JS)
└── README.md
```

## License

This project is licensed under the [MIT License](LICENSE).
