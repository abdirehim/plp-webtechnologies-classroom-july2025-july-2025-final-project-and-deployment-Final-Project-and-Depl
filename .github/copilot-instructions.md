
# Copilot Instructions for AI Coding Agents


## Chosen Project Idea: Local Community Event Finder

This project is a practical website designed to help users discover local community events, workshops, and meetups. The site will include pages such as Home, Events, Submit Event, About, and Contact. Users can browse upcoming events, search by category or date, and submit their own events for listing. The goal is to solve the problem of community members missing out on local happenings by providing a centralized, easy-to-use platform for event discovery and sharing.

## Project Overview
This project is a multipage website built with HTML5, CSS, and JavaScript. The goal is to demonstrate planning, responsive design, interactivity, and production-ready organization. The site is intended for deployment on static hosting platforms (GitHub Pages, Netlify, or Vercel).

## Key Architectural Patterns
- **Pages:** 3–5 HTML pages (e.g., Home, About, Services, Contact, Gallery) with consistent header/footer and internal navigation.
- **Folder Structure:**
  - `/css` for stylesheets
  - `/js` for JavaScript files
  - `/images` for assets
  - HTML files at the root or in a `/pages` directory
- **Shared Layout:** All pages should use the same header and footer for consistency. Use includes/partials if templating is introduced.
- **Responsiveness:** Use CSS media queries and flexible layouts. Test on mobile and desktop.
- **Interactivity:** Each page must have at least one interactive JavaScript feature (e.g., menu toggle, form validation, animation).

## Developer Workflows
- **Development:** Edit HTML, CSS, and JS files directly. Use relative paths for all internal links and assets.
- **Testing:**
  - Validate HTML and CSS using online validators (e.g., https://validator.w3.org/)
  - Manually test navigation, responsiveness, and interactivity in multiple browsers/devices
- **Build/Deploy:**
  - No build step required for static sites
  - Deploy via GitHub Pages, Netlify, or Vercel
  - Ensure all links/scripts work after deployment

## Project-Specific Conventions
- Use semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<footer>`, etc.)
- Organize code for readability: comment sections, use meaningful names
- Keep code modular: separate JS/CSS by feature if possible
- README must include project purpose, structure, and live URL

## Integration Points
- No backend or API integration; all logic is client-side
- External libraries (if used) should be included via CDN and documented in the README

## Examples
- See the `README.md` for project requirements and deliverables
- Example folder structure:
  ```
  /css/style.css
  /js/main.js
  /images/logo.png
  index.html
  about.html
  contact.html
  ```

## Do/Don't
- **Do:**
  - Follow the folder structure and naming conventions
  - Ensure all pages are accessible and linked
  - Test on different devices
- **Don't:**
  - Add server-side code or frameworks
  - Use absolute paths for internal links

---
For any unclear conventions, refer to the `README.md` or ask for clarification.
