# Enterprise Employee Dashboard - Task 03

A semantic, accessible employee operations dashboard built as part of the Rabtech Web Development Internship.

## Project Overview
This repository contains the structural baseline and component architecture for an internal enterprise dashboard. The markup strictly complies with HTML5 semantic standards and WCAG 2.1 accessibility guidelines to ensure usability across screen readers and keyboard navigation.

## Key Architectural Features
- **Semantic HTML5 Elements:** Utilizes `<header>`, `<nav>`, `<aside>`, `<main>`, `<section>`, `<article>`, and `<footer>` to create a structured document hierarchy.
- **Accessibility (A11y):**
  - Skip-to-content mechanism (`.skip-btn`) for keyboard-only users.
  - Native `<dialog>` modal with proper ARIA attributes (`aria-modal`, `aria-labelledby`).
  - Accessible data tables with scope-defined headers (`th scope="col"` and `th scope="row"`).
- **Form Controls & Validation:**
  - Explicit `<label for="...">` associations for all form fields.
  - Logical section grouping using `<fieldset>` and `<legend>`.
  - Native HTML5 validation constraints (`required`, `type="email"`).
- **W3C Validated:** Zero syntax or nesting errors.

## Project Structure
```text
├── index.html        # Main semantic markup and accessible modal dialog
└── README.md         # Architecture overview and documentation
