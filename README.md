# Food Delivery App — Multi-restaurant ordering (prototype)

Overview
- Multi-restaurant ordering prototype with cart and order status tracking.
- Tech: Figma (design), HTML, CSS, Tailwind CSS, Bootstrap, JavaScript.
- This repo is a frontend prototype (no backend). Cart persists in localStorage. Order status is simulated.

Quick start (prototype / demo using CDN)
1. Open `index.html` in a browser.
2. Use the restaurant cards to open a menu, add items to cart.
3. Open the cart (top-right) to adjust quantities and place an order.
4. After placing an order, the Order Tracking screen simulates status changes.

Development (Tailwind build)
- To build an optimized Tailwind CSS for production:
  1. Node.js installed (v16+ recommended)
  2. npm install
  3. npm run build
  4. Open `index.html` (adjust link to the built CSS in `dist/`)

Files
- index.html — main prototype
- scripts.js — cart & order logic
- styles.css — small custom styles
- src/input.css — Tailwind entry (for build)
- tailwind.config.js, postcss.config.js — build config
- package.json — dev scripts

Design
- Use the `figma/` directory or your Figma space for wireframes and component library. Key screens: Home, Restaurants, Menu, Cart, Order Tracking, Profile.

License
- MIT
