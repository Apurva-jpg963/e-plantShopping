# Paradise Nursery Shopping Application

Paradise Nursery is an online houseplant shopping web application built with React and Redux Toolkit. It allows plant enthusiasts to explore a diverse catalog of indoor plants, learn about their characteristics, and seamlessly manage a dynamic shopping cart.

## Features

- **Landing Page**: An inviting entrance featuring the company name, background scenery, company mission statement, and a "Get Started" button to transition into the plant catalog.
- **Product Listing**:
  - Organized categorization of plants: *Air Purifying Plants*, *Aromatic Fragrant Plants*, *Insect Repellent Plants*, *Medicinal Plants*, *Low Light Plants*, and *Easy Care Plants*.
  - Detailed product cards showcasing thumbnail images, names, descriptions, and prices.
  - Interactive "Add to Cart" buttons that dynamically update cart counts and disable upon selection.
- **Dynamic Navigation Bar**:
  - Direct navigation between the Landing Page, Product Catalog, and Shopping Cart.
  - Live shopping cart icon displaying the dynamic total quantity of selected plants.
- **Shopping Cart Management**:
  - Detailed cart overview displaying plant thumbnails, unit prices, individual item totals, and grand total cart cost.
  - Increase (`+`) and decrease (`-`) quantity controls that update the cart in real time.
  - Delete buttons to easily remove items from the cart.
  - "Continue Shopping" button to return to the catalog and an interactive "Checkout" button.

## Tech Stack

- **React** (Vite)
- **Redux Toolkit** & **React-Redux** (Global state management)
- **CSS3** (Responsive design and micro-interactions)

## Installation & Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Apurva-jpg963/e-plantShopping.git
   cd e-plantShopping
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`.