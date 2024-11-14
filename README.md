# E-Commerce Flutter App

This Flutter project is a fully functional e-commerce application using the Fake Store API. It includes essential features such as infinite scrolling, product details, search, user authentication, sorting, and a shopping cart, with state management handled by Riverpod and a clean architecture for modularity and maintainability.

## Features

### 1. Homepage
- Displays a list of featured products, including images, names, prices, and ratings.
- Initially loads 10 products, with infinite scrolling to fetch additional products as the user scrolls down.

### 2. Product Detail Page
- Provides detailed information about each product, including images, name, price, description, ratings, and reviews when a user selects a product.

### 3. Product Search
- Allows users to search for products by name.
- Displays search results with product image, name, price, and rating.

### 4. User Authentication
- Implements login and logout functionality.
- Validates user registration details, including name, email, phone number, and password.

### 5. Product Sort & Filter
- Enables sorting of products by price, popularity, and rating.
- Provides filtering options for categories, price ranges, and ratings.

### 6. Shopping Cart
- Allows users to add and remove products from their cart.
- Displays the cart with a list of added products, quantities, and total price.
- Includes a checkout button that navigates the user to a checkout page.

### 7. State Management
- Utilizes Riverpod to efficiently manage the application state.

### 8. Clean Architecture
- Separates business logic from UI code, ensuring modularity, testability, and maintainability.

### 9. Responsive UI
- Ensures the UI adapts to various device sizes and orientations.

### 10. Documentation
- Provides meaningful variable names and comments to enhance code readability and maintainability.
- Includes this README file with comprehensive setup and run instructions.

## Getting Started

Follow these steps to set up and run the application:

### Prerequisites
- Install [Flutter SDK](https://flutter.dev/docs/get-started/install)
- Clone the repository and navigate to the project directory.

### Clone the Repository
```bash
git clone https://github.com/nikeshsharma192002/ecommerce-flutter-app.git
cd ecommerce-flutter-app
```
### Install Dependencies
Run the following command to install required packages:
```bash
flutter pub get
```
### Run the Application
```bash
flutter run
```
### Run Tests
```bash
flutter test
```

## Dependencies
- Flutter SDK: Main framework for developing the app.
- Riverpod: For efficient state management.
- HTTP package: To handle network requests.
