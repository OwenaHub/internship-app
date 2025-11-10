# Todo App — Intern Guide

A small, intentionally simple HTML & CSS todo app to learn front-end basics and the project workflow.

## What this repo contains
- index.html — app markup
- styles.css — styling
- assets/ — images or icons (if present)
- README.md — this file

## Prerequisites
- Git installed
- A modern browser
- (Optional) A simple static server (python, node, or VS Code Live Server)

## Clone the repo
Choose SSH or HTTPS and replace with the real repository path:

SSH:
git clone git@github.com:ORG/REPO.git

HTTPS:
git clone https://github.com/OwenaHub/internship-app.git

cd internship-guide

## Run locally
- Open index.html in your browser
OR
- Start a simple server:
    - Python 3: python3 -m http.server 8000
    - Node (http-server): npx http-server
- Visit http://localhost:8000

## Branching & workflow
- Create a branch per task:
    - feature/short-description or fix/short-description
- Commit messages: type(scope): short summary
    - Example: feat(ui): improve todo item spacing
- Push branch and open a Pull Request to main
- Add a short description and link to related issue (if any)

## Code style & accessibility
- Use semantic HTML elements (header, main, form, button, ul/li)
- Class names: kebab-case (e.g., .todo-list)
- Keep CSS simple and modular (variables for colors)
- Avoid inline styles
- Ensure keyboard accessibility and use labels for inputs

## Tasks / Suggestions for interns
- Implement add / remove / complete functionality (JavaScript, if not present)
- Persist todos using localStorage
- Make layout responsive
- Improve visual design (hover/focus states, transitions)
- Add keyboard shortcuts and accessibility improvements

## Submitting work
- Push your branch and open a PR
- Add a summary of changes and testing steps
- Request a review and address feedback
- Link the PR to the relevant issue or task card

## Contact / Support
- Ask questions via the project’s issue tracker or your assigned mentor
- Include steps to reproduce and screenshots where helpful

Keep changes small and focused. Welcome — learn by doing and ask for reviews early.