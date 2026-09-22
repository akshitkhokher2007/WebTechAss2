# Assignment #2 — Advanced CSS (Flexbox & Grid)

**Name:** _[Your Full Name]_
**Group:** _[Your Group Number]_

## About This Project

This repository contains my solutions for Assignment #2, covering Flexbox and
CSS Grid layout techniques. Each task lives in its own folder with its own
`index.html` and `style.css`, so every page can be opened independently.

```
project/
├── task0-navbar/
├── task1-cards/
├── task2-grid-layout/
├── task3-gallery/
└── task4-portfolio/
```

---

## Part 1. Flexbox

### Task 0 — Navigation Bar
A flex container header with a logo on the left and nav links on the right,
using `justify-content: space-between` and `align-items: center`.

📁 [`/task0-navbar`](./task0-navbar)

**Screenshot:**
`![Navbar screenshot](./screenshots/task0-navbar.png)`

---

### Task 1 — Card Row
Three cards in a flex row, equal height, consistent gaps, with a hover
"lift" effect.

📁 [`/task1-cards`](./task1-cards)

**Screenshot:**
`![Card row screenshot](./screenshots/task1-cards.png)`

---

## Part 2. Grid System

### Task 2 — Page Layout with Grid Areas
A full-page layout (header, sidebar, main, footer) built using
`grid-template-areas`.

📁 [`/task2-grid-layout`](./task2-grid-layout)

**Screenshot:**
`![Grid layout screenshot](./screenshots/task2-grid-layout.png)`

---

### Task 3 — Image Gallery
A 3x3 CSS Grid gallery with equal gaps and a caption overlay that fades in
on hover.

📁 [`/task3-gallery`](./task3-gallery)

**Screenshot:**
`![Gallery screenshot](./screenshots/task3-gallery.png)`

---

## Part 3. Combining Flexbox & Grid

### Task 4 — Portfolio Page
A full portfolio page: Flexbox for the navbar, CSS Grid for the two-column
main section (projects + sidebar), and Flexbox again inside each project
card.

📁 [`/task4-portfolio`](./task4-portfolio)

**Screenshot:**
`![Portfolio screenshot](./screenshots/task4-portfolio.png)`

---

## Summary of My Work Process


I started with the simpler Flexbox tasks (navbar and card row) to get
comfortable with `justify-content`, `align-items`, and `gap`. Then I moved
to CSS Grid, first learning `grid-template-columns`/`rows`, and later
`grid-template-areas` for the page layout task, which was the part I had
to re-read the documentation for the most. The hardest part was making the
image gallery captions appear smoothly on hover using `position: absolute`
and `opacity` transitions. For the final portfolio page, I combined both
techniques: Flexbox for one-dimensional rows (navbar, card content) and
Grid for the two-dimensional page structure.

---

## How to Run

Each task is a static HTML/CSS page — no build tools required.

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. Open any task's `index.html` file directly in your browser, or use the
   VS Code "Live Server" extension for auto-reload while editing.
