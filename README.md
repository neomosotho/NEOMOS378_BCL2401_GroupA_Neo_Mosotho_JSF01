## SwiftCraft
SwiftCraft is a responsive e-commerce web application built using HTML, Tailwind CSS, Alpine.js, and FontAwesome. The app fetches product data from the Fake Store API, displaying products in a grid format with features like sorting, filtering, searching, and favoriting.

## Features
Product Listing: Browse a wide range of products fetched from an external API.
Category Filtering: Filter products by category.
Sorting: Sort products by price (low to high, high to low).
Search: Search for products by title.
Product Details: View detailed information about a specific product in a modal.
Favorites: Mark products as favorites with a heart icon.
Technologies Used
HTML: Structure and content of the web pages.
Tailwind CSS: For styling the application with utility-first CSS classes.
Alpine.js: A lightweight JavaScript framework for managing UI state and interactions.
FontAwesome: For icons used in the application.
Fake Store API: A RESTful API used to fetch product data.

## Installation
To set up the project locally, follow these steps:

## Clone the Repository

git clone 
cd swiftcraft
npm run dev

## Install Dependencies

No additional dependencies are required as the project relies on CDN links for Tailwind CSS, Alpine.js, and FontAwesome.

## Usage
1. Product Listing
The main page displays a grid of products fetched from the Fake Store API. Each product card includes an image, title, price, category, rating, and a heart icon for marking as favorite.

2. Category Filtering
Use the category dropdown to filter products by category. The list updates dynamically based on the selected category.

3. Sorting
Use the sorting dropdown to sort products by price:

Default: No sorting.
Price: Low to High: Sort products by increasing price.
Price: High to Low: Sort products by decreasing price.

4. Search
Enter keywords in the search bar to find products by their title. The search is case-insensitive and updates the product list as you type.

5. Product Details
Click the "View Details" button on any product card to open a modal with detailed information, including a larger image, full description, and reviews.

6. Favorites
Click the heart icon on any product card to mark it as a favorite. The icon changes color to indicate the product's favorite status. This status is maintained during the session but will not persist across page reloads.

## Future Enhancements
Persistent Favorites: Implement local storage to persist favorite products across sessions.
Authentication: Add user authentication for personalized features like wishlists.
Pagination: Implement pagination for the product list to improve performance and user experience.
Styling: Use better styling 