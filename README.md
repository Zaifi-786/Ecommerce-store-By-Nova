# My Store — E-Commerce Frontend

A responsive e-commerce frontend application built with **React**, **TypeScript**, and **Vite**. This project provides a complete shopping interface including product browsing, detailed product views, wishlist management, a slide-out shopping cart, and a checkout flow[cite: 3].

---

## Features

- **Home & Product Catalog (`Home.tsx`):** Browse available products with clean, reusable product cards[cite: 3].
- **Product Details (`ProductionDetails.tsx`):** View detailed information for individual items[cite: 3].
- **Wishlist (`Wishlist.tsx`):** Save and manage favorite items for future purchase[cite: 3].
- **Interactive Cart (`CartDrawer.tsx`):** Slide-out cart drawer for reviewing selected items and quantities without leaving the current page[cite: 3].
- **Checkout Flow (`Checkout.tsx`):** Streamlined checkout page for completing orders[cite: 3].
- **Responsive Navigation (`Navbar.tsx`):** Easy access across store pages, wishlist, and cart[cite: 3].
- **404 Error Handling (`NotFound.tsx`):** Fallback page for invalid routes[cite: 3].

---

## Tech Stack

- **Framework:** React (with TypeScript)[cite: 3]
- **Build Tool:** Vite (`vite.config.js`)[cite: 3]
- **Styling:** CSS (`App.css`, `index.css`)[cite: 3]
- **Linting:** ESLint (`eslint.config.js`)[cite: 3]

---

## Project Structure

```text
my-store/
├── src/
│   ├── components/
│   │   ├── CartDrawer.tsx       # Slide-out shopping cart component
│   │   ├── Navbar.tsx           # Top navigation bar
│   │   └── ProductCard.tsx      # Individual product display card
│   ├── data/
│   │   └── products.ts          # Mock product catalog data
│   ├── pages/
│   │   ├── Checkout.tsx         # Order checkout view
│   │   ├── Home.tsx             # Main storefront landing page
│   │   ├── NotFound.tsx         # 404 fallback page
│   │   ├── ProductionDetails.tsx# Single product detail view
│   │   └── Wishlist.tsx         # Saved items page
│   ├── types/
│   │   └── index.ts             # TypeScript interfaces and type definitions
│   ├── App.css                  # Application-level styles
│   ├── App.tsx                  # Root component and routing setup
│   ├── index.css                # Global styles
│   └── main.tsx                 # Application entry point
├── eslint.config.js             # ESLint configuration
├── package.json                 # Project dependencies and scripts
├── tsconfig.json                # TypeScript configuration
└── vite.config.js               # Vite bundler configuration
