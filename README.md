# Odin Recipes

A simple recipe web app built with HTML, CSS, and JavaScript. Intended as a practice project to learn DOM manipulation, responsive layout, and client-side state management.

## Features
- List recipes with images, ingredients, and steps
- Add, edit, and delete recipes (in-memory / localStorage)
- Search and filter recipes by name or ingredient
- Responsive layout for desktop and mobile

## Tech stack
- HTML for structure
- CSS (Flexbox / Grid) for layout and responsive design
- Vanilla JavaScript for interactivity and local persistence

## Getting started
1. Clone the repository.
2. Open `index.html` in your browser, or run a live server:
   - VS Code Live Server extension

## Project structure
- index.html — main page
- styles.css — styling
- app.js — application logic
- assets/ — images and icons

## Development notes
- Use `localStorage` to persist recipes between sessions.
- Keep UI updates and data logic separated (e.g., render functions vs. storage functions).
- Add unit tests for critical functions if desired.

## Contribution
1. Create a feature branch.
2. Open a pull request with a clear description.
3. Follow the existing code style and add comments where needed.
