# Ableton Web Clone – Project Houston

Welcome to **Project Houston**, a collaborative front-end clone of the Ableton website. This project showcases our HTML & CSS skills as part of our web development bootcamp. The goal was to replicate key sections of the Ableton homepage, focusing on visual layout, responsive design, and semantic HTML5 structure.

---

## Project Overview

This website presents a visually engaging user interface inspired by [Ableton](https://www.ableton.com/), a leading brand in music production software and hardware. The project demonstrates modern HTML and CSS capabilities including:

- Fully responsive layouts
- Section-based design architecture (Hero, Header, Cards, Footer, etc.)
- Consistent styling using modular CSS files
- Use of animations and hover interactions without JavaScript

---

## Git Workflow Strategy

To ensure a clean and conflict-free collaboration, our team followed a structured **Git Branching Strategy**:

### Branching Structure:

- `main` – Production-ready branch (final version)
- `development` – Staging branch for merged features
- `feature/your-name` – Individual branches for isolated development

## To maintain clean organization and modularity, our project follows a well-structured folder layout:

├── index.html # Main HTML file
├── styles/ # All modular CSS files (e.g., hero.css, footer.css)
│ └── styles.css # Main stylesheet importing all section CSS files
├── assets/ # Contains static assets
│ ├── images/ # Hero and content images
│ ├── icons/ # Footer and navigation icons
│ └── fonts/ # Custom web fonts (e.g., Futura PT)

### Workflow:

1. Each developer works on a personal `feature/` branch.
2. Changes are committed using the convention:
   - `feature: added hero section`
   - `bug: fixed layout shift in card section`
3. Developers regularly push to their remote feature branch to stay backed up and in sync.
4. When ready, a **Pull Request (PR)** is created into `development` and assigned to a teammate for review.
5. After approval, the PR is merged into `development`.
6. All developers pull the latest changes from `development` into their own branches before continuing.
7. Once the team agrees on a release candidate, `development` is merged into `main`.

---

## Team Git Conventions

- **Branch Naming:** `feature/hero-section`, `bug/fix-footer`, etc.
- **Commit Message Format:**
  - `feature: added responsive layout to text section`
  - `bug: resolved navbar overflow issue`
- **Pull Requests:** Must include a short summary and assign at least one reviewer.
- **Review Practice:** Code is reviewed for readability, consistency, and adherence to naming/styling conventions before merging.

---

## Technologies Used

- HTML5
- CSS3 (Modular, with separate files for sections)
- Git & GitHub (branching, pull requests, code reviews)
- VS Code

---

## Authors

- Paramveer Marwah
- Ciro
- Hisham

Bootcamp Project – WBS Coding School  
Berlin, Germany – 2025
