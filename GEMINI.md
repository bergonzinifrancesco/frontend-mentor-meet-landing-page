# Meet Landing Page - Project Context

## Project Overview
This project is a static landing page for "Meet", a group chat application. It is likely a solution to a Frontend Mentor challenge. The project uses HTML5 and CSS3, leveraging Bootstrap 5 for the layout system and responsiveness.

## Tech Stack
*   **HTML5:** Semantic markup.
*   **CSS3:** Custom styling with CSS Variables (Custom Properties) for theme colors.
*   **Bootstrap 5.3.8:** Used via CDN for the grid system (`container`, `row`, `col`) and utility classes.
*   **Fonts:** "Red Hat Display" from Google Fonts.

## Directory Structure
*   `index.html`: The main entry point. Contains the HTML structure and CDN links for Bootstrap.
*   `styles.css`: Contains project-specific styles, including:
    *   **Color Palette:** `--color-cyan-300`, `--color-purple-600`, `--color-slate-900`, etc.
    *   **Typography:** Utility classes like `.text-preset-1` through `.text-preset-5` defining font weights, sizes, and line heights.
*   `assets/`: Contains images (SVGs, JPGs, PNGs) for different viewports (desktop, tablet, mobile).

## Development Conventions
*   **Styling:** 
    *   The project uses a mix of Bootstrap utility classes (e.g., `text-center`, `mt-xl-5`, `d-flex`) and custom CSS classes.
    *   Typography styles are abstracted into `.text-preset-*` classes rather than targeting HTML tags directly.
    *   Colors are managed via CSS variables on the `body` selector.
*   **Responsive Design:** Uses Bootstrap's grid system to handle responsiveness across mobile, tablet, and desktop viewports.

## Building and Running
Since this is a static site, no build step is required.
1.  Open `index.html` in a web browser to view the page.
2.  Use a local development server (e.g., Live Server, `python -m http.server`) for a better development experience.
