# AI Coding Agent Instructions for Portfolio Project

Welcome to the portfolio project for Gangadhara B (Full-Stack Developer). This file provides essential instructions and conventions to help AI coding agents be immediately productive in this codebase.

## Project Overview
- **Type:** Personal portfolio (single-page application)
- **Tech:** HTML, CSS (inlined), JavaScript (potentially for interactivity)
- **Purpose:** Showcase skills, projects, experience, and contact information

## Key Conventions
- **Single file:** All content is currently in `index.html` (HTML, CSS, and possibly JS inlined)
- **Styling:** Uses custom CSS with modern gradients, responsive design, and utility classes
- **No build tools:** No package.json, build scripts, or external dependencies (except CDN fonts/icons)
- **No framework:** Pure HTML/CSS/JS, not React/Vue/Angular

## Editing Guidelines
- **Preserve structure:** Maintain semantic HTML and section order (nav, hero, skills, projects, etc.)
- **Accessibility:** Use proper tags and ARIA attributes if adding new interactive elements
- **Responsiveness:** Ensure any changes remain mobile-friendly (see media queries in CSS)
- **Performance:** Minimize inline JS/CSS bloat; prefer CSS for animations and effects
- **External links:** Use `target="_blank"` for external project/demo links

## Common Tasks
- **Add new project:** Duplicate a `.proj-card` in the Projects section, update content and links
- **Add new skill:** Duplicate a `.sb` or `.chip` in the Skills section
- **Update contact info:** Edit the Contact section at the bottom of the file
- **Change theme:** Update CSS variables in the `:root` selector

## Potential Pitfalls
- **Large file:** As all content is in one file, edits can be error-prone—double-check closing tags
- **No JS framework:** Avoid JSX, imports, or module syntax
- **No backend:** All data is static; forms do not submit anywhere unless JS is added

## Useful Links
- [Font Awesome Icons](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css)
- [Google Fonts: Rubik](https://fonts.googleapis.com/css2?family=Rubik:wght@400;700&display=swap)

---

This file helps AI coding agents understand the structure and conventions of this portfolio project. For major changes, consider splitting content into multiple files for maintainability.
