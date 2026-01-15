# Food Product Explorer

## Overview
This project is a **Food Product Explorer** web application built using **ReactJS** and **TailwindCSS**. It allows users to:

- Search for food products by name.
- Search products by barcode.
- Filter products by category.
- Sort products by product name or nutrition grade.
- View detailed information about each product, including ingredients, nutrition values, labels, and images.

The application fetches data from the **[OpenFoodFacts API](https://world.openfoodfacts.org/)**.

---

## Features Implemented
1. **Homepage**
   - Displays a list of products with name, image, category, ingredients, and nutrition grade.
   - Supports pagination via "Load More" button.

2. **Search Functionality**
   - Users can search products by name.
   - Users can search products by barcode.

3. **Category Filter**
   - Dropdown filter for different product categories fetched from the API.

4. **Sort Functionality**
   - Sort products alphabetically (A-Z / Z-A).
   - Sort products by nutrition grade (Best First / Worst First).

5. **Product Detail Page**
   - Shows product image, ingredients, nutrition values, labels (vegan, gluten-free, etc.).

6. **Responsive Design**
   - Fully responsive on mobile and desktop screens.

---

## Technology Stack
- **Frontend:** ReactJS
- **Styling:** TailwindCSS
- **API:** OpenFoodFacts API
- **Bundler/Dev Server:** Vite

---

## Methodology
1. **Setup**
   - Initialized a React project using Vite.
   - Configured TailwindCSS for styling.
   - Created components for Header, Product Card, Product Modal, Loading Spinner, Empty State, and Error Messages for modularity.

2. **API Integration**
   - Used fetch API to retrieve product data from OpenFoodFacts.
   - Implemented search, category filter, barcode lookup, and pagination features.

3. **State Management**
   - Managed state using React `useState` and `useEffect`.
   - Sorting, filtering, and product selection handled at component level.

4. **Responsive UI**
   - Used TailwindCSS utility classes to ensure mobile-first, responsive design.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-link>
