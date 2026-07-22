# Kitka Weddings — website v2

A redesign of the Kitka destination-wedding planning site: bilingual (Bulgarian/English), interactive, and built as a static site with no build step.

## Structure

- `index.html` — Home
- `services.html` — Planning packages & pricing
- `portfolio.html` — Filterable celebration gallery
- `blog.html` — Stories & guides
- `contact.html` — Contact details + inquiry form
- `css/style.css` — Design system (colors, type, components, animation)
- `js/i18n.js` — Bulgarian/English content dictionary + language switching
- `js/main.js` — Header scroll state, mobile menu, scroll-reveal animations, portfolio filters, contact form

## Running locally

No build step — serve the folder with any static file server, e.g.:

```
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Content

All copy is real content carried over from the original Kitka site (services, pricing, contact details), reorganized and restyled. Photography and blog articles are placeholders, as in the original — swap the `.tile` gradient blocks for real images when photography is available.
