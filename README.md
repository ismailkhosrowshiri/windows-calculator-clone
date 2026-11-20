# Windows Calculator UI Clone

A browser-based recreation of the Windows 10 calculator interface, created as a frontend practice project.

## Original Project

The original implementation is kept in the repository root:

- `index.html`
- `css/style.css`

This version is part of the project's learning history. Its original code is intentionally preserved and has not been refactored.

## Improved HTML & CSS Version

The `improved-versions/` directory contains a separate refactored version focused on code quality:

- `improved-versions/index.html` — semantic page structure and clearly grouped interface sections.
- `improved-versions/style.css` — organized styles, reusable CSS custom properties, consistent naming, and responsive layouts.

### What Was Improved

- Replaced presentation-only structure with more meaningful HTML elements such as `main`, `header`, `section`, `aside`, and `output`.
- Grouped related interface elements into clear, maintainable sections.
- Introduced consistent class naming with a component-oriented structure.
- Centralized repeated colors and layout values in CSS custom properties.
- Applied a consistent box-sizing rule and removed unnecessary global styling.
- Organized responsive breakpoints and simplified the layout rules.
- Added accessible labels and visible keyboard-focus styling.
- Kept HTML and CSS in separate files to make the project easier to read and maintain.

### Important Scope Note

This is a **static UI mockup**, not a working calculator. The keys are visual interface elements only; no JavaScript or calculation behavior has been added. The goal of this version is to demonstrate a cleaner HTML and CSS implementation while keeping the original learning project intact.

### Run the Improved Version

Open `improved-versions/index.html` directly in a browser. No build tools or package installation are required.

## Run the Original Version

Open the root `index.html` file in a browser.

## Tech Stack

- HTML
- CSS

## Project Status

Both implementations are retained for comparison: the original shows the earlier learning stage, while the improved version demonstrates a more structured approach to the same visual interface.

## Author

[Ismail Khosrowshiri](https://github.com/ismailkhosrowshiri)
