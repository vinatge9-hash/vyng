# Niyantri Cafe Website

This project includes a five-page coffee shop website built with Tailwind CSS (via CDN).

Pages:
- index.html: Home
- menu.html: Menu
- cart.html: Cart
- about.html: About
- contact.html: Contact

Key features:
- Coffee color theme with warm tones
- Responsive navigation with a mobile hamburger menu
- Page load fade-in animation and section reveal on scroll (Tailwind-based)
- LocalStorage-based cart with add, remove, render, and checkout flow
- Mock PayPal checkout flow (client-side) using a simulated API
- Placeholder images using the required placeholder syntax
- Footer with current year: 2025
- Placeholder location: Hyderabad, India (used on contact/footer)

Notes:
- All icons are inline SVG within the HTML where used (not external assets).
- The header and footer are identical across all pages as requested.
- All items in the menu are explicitly defined in the HTML (no dynamic loading).

To run:
- Open the HTML files in a browser. The cart uses localStorage to persist between pages.
- No server is required; this is a static front-end implementation with a mock API for PayPal.
