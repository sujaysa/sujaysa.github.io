# Copilot Instructions for sujaysa.github.io

This repository is a static portfolio website based on the iPortfolio template from BootstrapMade. It is primarily HTML, CSS, and JavaScript, with some PHP for contact form handling. The project structure and conventions are inherited from the template, but customizations may exist.

## Architecture Overview
- **Entry Point:** `index.html` is the main file. All navigation and content sections are defined here.
- **Assets:**
  - `assets/css/main.css`: Custom styles.
  - `assets/js/main.js`: Main JavaScript logic for UI interactions, animations, and third-party integrations.
  - `assets/vendor/`: Contains third-party libraries (Bootstrap, AOS, Typed.js, PureCounter, GLightbox, Isotope, Swiper, etc.).
  - `assets/img/`: Images used in the site.
- **Forms:**
  - `forms/contact.php`: Placeholder for contact form backend. The actual working script is only available in the pro version of the template.

## Key Patterns & Conventions
- **Template Customization:** Most code is adapted from the iPortfolio template. Custom logic should be added in `main.js` and `main.css` rather than modifying vendor files.
- **Section Navigation:** Navigation is handled via anchor links (`#section-id`). JavaScript manages active states and smooth scrolling.
- **Animations:** AOS (Animate On Scroll) is used for section and element animations. Initialization is in `main.js`.
- **Skills Animation:** Progress bars in the Skills section animate on scroll using Waypoints.
- **Typed.js:** Used for dynamic text in the hero section. Strings are set via the `data-typed-items` attribute in HTML.
- **Preloader:** A preloader is shown until the page is fully loaded, then removed by JS.
- **Scroll-to-Top:** Button appears after scrolling down, handled in `main.js`.
- **Vendor Libraries:** All third-party JS/CSS should be placed in `assets/vendor/` and referenced in `index.html`.

## Developer Workflows
- **No Build Step:** This is a static site. Changes to HTML, CSS, or JS are reflected immediately. No build or test commands are required.
- **Debugging:** Use browser dev tools for debugging. No automated test suite is present.
- **Adding Libraries:** Place new libraries in `assets/vendor/` and update references in `index.html`.
- **Contact Form:** The PHP backend is a placeholder. For a working form, upgrade to the pro template or implement your own backend.

## External Integrations
- **BootstrapMade Template:** See [iPortfolio](https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/) for documentation and updates.
- **LinkedIn:** Social link in the header points to the user's LinkedIn profile.

## Examples
- To add a new section, define it in `index.html` and style it in `main.css`.
- To add a new animation, use AOS attributes in HTML and initialize in `main.js`.
- To update navigation, modify the `<nav>` in `index.html` and ensure anchor links match section IDs.

## Important Files & Directories
- `index.html`: Main site structure and content.
- `assets/css/main.css`: Custom styles.
- `assets/js/main.js`: Custom JS logic.
- `assets/vendor/`: Third-party libraries.
- `forms/contact.php`: Contact form backend (placeholder).

---

If any conventions or workflows are unclear, please provide feedback so this guide can be improved.