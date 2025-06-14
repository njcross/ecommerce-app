# 🛍️ Ecommerce App with FakeStoreAPI

A fully functional React + Redux Toolkit + React Query e-commerce app that simulates a real online store using the [FakeStoreAPI](https://fakestoreapi.com/). This project demonstrates advanced concepts such as API integration, Redux-based state management, and session persistence.

## 📦 Features

- **Product Catalog**: Browse all products from the FakeStoreAPI with images, ratings, price, and descriptions.
- **Category Filtering**: Dynamically filter products by category using a dropdown populated from the API.
- **Cart Management**: Add, remove, and update product quantities in the cart with Redux Toolkit.
- **Session Persistence**: Shopping cart state is saved in `sessionStorage` for persistence between sessions.
- **Checkout Simulation**: Clears cart and session on checkout with a success message.
- **Responsive UI**: Clean, responsive design using CSS modules and Bootstrap.

## 🧰 Technologies Used

- React
- Redux Toolkit
- React Query
- TypeScript
- React Router DOM
- Bootstrap
- FakeStoreAPI

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or later)
- npm

### Installation

```bash
git clone https://github.com/njcross/ecommerce-app.git
cd ecommerce-app
npm install
```

### Running the App

```bash
npm run dev
```

The application will be available at [http://localhost:5173](http://localhost:5173).

## 📁 Project Structure

```
src/
├── api/                # API utility functions
├── components/         # Reusable UI components
├── pages/              # Page components (Home, Cart, etc.)
├── store/              # Redux slices and store config
├── App.tsx             # Main app routes
└── main.tsx            # App entry point
```

## 🛠️ Functionality Overview

### Product Listing

- Loads all products via React Query.
- Shows title, price, category, rating, image, and description.
- Products can be added to cart from the home screen.

### Category Navigation

- Dropdown built from `/products/categories` API.
- Filters product list on selection.

### Shopping Cart

- View products in cart with quantity and price.
- Modify quantity or remove items.
- Checkout button simulates purchase and resets cart.

## 📚 Learn More

- [React Query Docs](https://tanstack.com/query/latest)
- [Redux Toolkit Docs](https://redux-toolkit.js.org/)
- [FakeStoreAPI Docs](https://fakestoreapi.com/docs)

---

© 2025 Nicholas Cross – Educational project built for learning purposes.