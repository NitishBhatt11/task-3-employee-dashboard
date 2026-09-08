# Enterprise Employee Dashboard

A responsive, accessible employee operations dashboard built as part of the Rabtech Web Development Internship (Tasks 03 & 04).

## Project Overview
This repository contains the semantic markup baseline, accessible component structure, and modern mobile-first styling for an internal operations dashboard. The layout strictly follows WCAG 2.1 standards, supports light/dark color schemes via CSS variables, and adapts seamlessly across mobile, tablet, and desktop viewports.

## Key Features
- **Semantic Structure & Accessibility (Task 03):**
  - Full landmark hierarchy (`header`, `nav`, `aside`, `main`, `footer`).
  - Native `<dialog>` modal with proper ARIA attributes.
  - Keyboard accessible skip-to-content mechanism (`.skip-btn`).
  - Accessible tables with defined `scope` attributes for row/column headers.
- **Design Tokens & Responsive Styling (Task 04):**
  - CSS Custom Properties (`:root`) for color palette, spacing, and typography scales.
  - Native dark mode support (`prefers-color-scheme: dark`).
  - Mobile-first architecture using CSS Grid and Flexbox.
  - Fluid breakpoints (mobile, tablet at 768px, desktop) with zero horizontal overflow.
  - Clean UI transitions, subtle elevation, and status indicators.

## Project Structure
```text
├── index.html        # Semantic HTML5 markup and dialog modal
├── style.css         # Design tokens, mobile-first layouts, and themes
└── README.md         # Architecture overview and documentation
