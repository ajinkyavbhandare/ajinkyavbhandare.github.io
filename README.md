# Portfolio Site

Simple personal portfolio built with plain HTML and CSS. No frameworks, no build tools, no dependencies.

# Table of Contents
- [Overview](#overview)
- [Pages](#pages)
- [Structure](#structure)
- [Running Locally](#running-locally)

# Overview

A minimal personal site that serves as a central reference for work, writing, and projects. The design is intentionally simple — fast to load, easy to read, nothing unnecessary.

# Pages

### Home
Introduction and brief description of the kind of work I do — machine learning systems, inference, data pipelines, and backend infrastructure.

### Projects
Detailed writeups of individual projects — what problem was being solved, how it was approached, what was built, and what was learned. Each project page goes beyond the GitHub README to explain the decisions made along the way.

### Blog
Technical writing on topics I find worth thinking about — system design, ML infrastructure, research papers, and the gap between what AI promises and what it actually delivers in production.

### About
Background, how I work, what I find interesting, and what I am currently exploring.

# Structure

```
index.html          — home
projects/           — individual project pages
blog/               — writing
about/              — background
assets/
  css/
    style.css       — single stylesheet
```

# Running Locally

No build step required. Open `index.html` directly in a browser or serve with any static file server.

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.
