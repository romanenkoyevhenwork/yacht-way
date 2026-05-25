# YachtWay Design Test Task

Static implementation of the YachtWay General Info screen for the vessel listing creation flow.

## Live Demo

The deployed version is available via GitHub Pages:

[Open GitHub Pages demo](https://romanenkoyevhenwork.github.io/yacht-way/)

## What Was Done

- Matched the General Info screen to the provided Figma design and UI Kit.
- Updated the HTML structure in `index.html` where it was needed for proper component markup, semantics, and class structure.
- Updated `styles.css` to align layout, spacing, typography, colors, buttons, inputs, sidebar steps, section icons, form groups, and responsive behavior with the design.
- Preserved the existing component interactivity without changing application logic.
- Left `app.js` unchanged, according to the task requirements.
- Added the bonus Listing Heat animation: the indicator smoothly changes from the freezing state to the warm state and visually grows as the form becomes more complete.
- Added the required visual assets for the Listing Heat states.

## Changed Files

- `index.html` — markup and component structure updates.
- `styles.css` — all visual styling and layout updates.
- `assets/` — added Listing Heat image assets.
- `app.js` — unchanged.

## How To Run Locally

Open `index.html` directly in a browser.

You can also serve the folder with any static server, for example:

```bash
npx serve .
```
