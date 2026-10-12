# Week 2 Task: Implementation of Responsive Web Design

## Overview
A responsive internship landing page made with semantic HTML5, CSS3, CSS Grid, Flexbox, fluid typography, and media queries.

## Files
- `index.html` — page structure
- `style.css` — styling and responsive breakpoints
- `script.js` — accessible mobile navigation toggle

## Responsive methods
- Fluid typography using `clamp()`
- Flexible container widths and CSS Grid
- Tablet breakpoint at `900px` (cards change to two columns)
- Mobile breakpoint at `640px` (sections stack and navigation collapses)
- Extra-small breakpoint at `380px`
- Media elements use `max-width: 100%` and `height: auto`
- Keyboard focus styles and reduced-motion support

## Test plan
Use browser Developer Tools to test widths of 320px, 390px, 768px, and 1280px. Check navigation, text wrapping, card layout, spacing, and horizontal overflow. Record the actual results after testing in a browser.

## Challenges and solutions
- Crowded cards on mobile: switch to a single-column grid.
- Long headings: use fluid font sizes and `overflow-wrap`.
- Crowded mobile navigation: provide an accessible menu toggle.
- Oversized media: constrain media to its container.

## Run
Keep the three project files in one folder and open `index.html` in a browser. Compare with an official wireframe if one is supplied.
