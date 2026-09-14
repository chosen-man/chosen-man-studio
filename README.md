# Chosen Man Studio

The standalone website for Chosen Man Studio, an independent web design and development practice.

## Brand assets

The live site uses the compact gold rose in the header, footer, browser icons, and structured metadata. The full emblem, light and dark horizontal lockups, one-color marks, and social-sharing card are published in `assets/brand` and mirrored in the sibling `Chosen-Man-Studio-Logo` working folder.

## Local preview

Open `index.html` in a browser. The page has no build step and uses only Google Fonts and Lucide icons as external assets.

## Publishing

The repository is structured for static hosting, including GitHub Pages.

## Interactive features

- The project selector introduces websites, apps, and IT/security consulting. Its contact link carries the selected service into the project brief.
- The brief opens a `mailto:` draft addressed to `hello@chosenman.studio`. The visitor must review and send it in their email app. Copy brief and a direct email link are also available. There is no submission backend, and the site does not store brief contents.
- Project notes and common questions use native disclosure elements. Core content and the direct email link remain usable without JavaScript.
- English, Spanish, and Yorkshire copy live in the inline `translations` object. Only the language preference is stored locally.
- Mobile navigation supports Escape and closes after choosing a section. Focus indicators and reduced-motion preferences are respected.
- The hidden field-note video loads only after activation and unloads when closed.

Before publishing, check all three languages at desktop and narrow phone widths, the project-to-brief handoff, email draft and copy fallback, disclosures, keyboard navigation, and the no-JavaScript contact fallback. Keep the sitemap modification date aligned with meaningful page changes.
