## 🚀 30-Day Coding Challenge: Day 16

This project is the sixteenth entry in my 30-day coding challenge. Today's goal was to build a foundational e-commerce component—a shopping cart—using React. This project focuses on managing a more complex state structure (an array of objects) and is a critical step towards building real-world applications.

### 📖 Project Overview

This is a clean and functional e-commerce interface that displays a list of products and a shopping cart. Users can add products to the cart, remove them, and see the total cost update in real-time. The application is built as a single-page app using React and styled with Tailwind CSS, demonstrating how to manage and derive state effectively.

### ✨ Live Demo & Screenshot

Below is a screenshot of the application's interface.
![Jun-24-2025 22-23-10](https://github.com/user-attachments/assets/85476fb1-f21f-4b1f-9fa4-2e13a7a1518d)


### 🌟 Key Features

* **Add to Cart:** Users can add products from the main list to their shopping cart.
* **Remove from Cart:** Items in the cart can be removed with a single click.
* **Real-time Total Calculation:** The cart total is calculated and displayed instantly whenever the cart's contents change. This is handled as "derived state" for efficiency.
* **Component-Based Architecture:** The UI is broken down into logical components (`ProductItem`, `CartItem`) for maintainability and reusability.
* **State Management with Arrays:** The core of the app is the management of an array of objects in React state.
* **Immutable State Updates:** Follows React best practices by treating state as immutable, creating new arrays for updates rather than modifying the original.
* **Modern & Responsive UI:** Styled with Tailwind CSS for a clean and responsive layout that works on all devices.

### 💻 Technologies Used

This project was built using a modern, lightweight React setup.

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Babel](https://img.shields.io/badge/Babel-%23F9DC3e.svg?style=for-the-badge&logo=babel&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

* **React:** The core library for building the user interface.
* **ReactDOM:** Used to render the React component into the browser's DOM.
* **Babel:** Used as a transpiler to convert JSX into standard JavaScript.
* **Tailwind CSS:** For all styling and layout.
* **Font Awesome:** For icons.

### 🛠️ How to Run Locally

This project is set up to be extremely simple to run, with no build process required:

1.  **Clone the repository (or download the code):**
    ```bash
    git clone https://github.com/timothy-agboada/shopping-cart.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd shopping-cart
    ```
3.  **Open the `index.html` file in your web browser.** The CDN links will handle loading all necessary libraries automatically.

### 🎯 Learning Objectives

This project was a crucial exercise in managing data collections in React:

* **Managing Arrays in State:** Learning the standard patterns for initializing and updating an array in React state using `useState`.
* **Immutable Update Patterns:** Mastering the use of the spread syntax (`...`) for adding items and `.filter()` for removing items, ensuring state is never mutated directly.
* **Derived State:** Understanding the concept of calculating values (like the cart total) from existing state on each render, rather than storing them in a separate state variable.
* **Component Communication:** Practicing passing callback functions (`onAddToCart`, `onRemoveFromCart`) as props from a parent component to child components to manage state changes.
* **Handling Unique Keys in Lists:** Using a combination of `id` and `index` to generate unique keys for items that may appear multiple times in a list.
