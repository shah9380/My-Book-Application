# My-Book_Application

## Table of Contents

- [Project Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [JavaScript Functions](#javascript-functions)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

### Description

The project seems to be a book-related web application where users can browse and interact with a collection of books. It includes features such as user authentication, book rendering based on categories, a shopping list, and navigation between different sections.

### Key Features

1. **User Authentication:**
   - Users can log in or register using the provided forms.
   - The authentication status is stored in local storage, controlling the user's access to certain features.

2. **Book Rendering:**
   - Books are fetched from an external API based on categories and displayed on the main page.
   - Bestseller books and category lists are rendered initially.
   - Users can select a category, triggering the display of books in that category.

3. **Popup for Individual Books:**
   - Clicking on a book in the list opens a popup with detailed information about the book.
   - Users can add books to their shopping list from this popup.

4. **Shopping List:**
   - Users can view and interact with a shopping list that dynamically updates as they add books.

5. **Navigation:**
   - The application includes navigation buttons to switch between the home page and the shopping list.
   - The navigation changes the visual styling to indicate the active section.

6. **User Logout:**
   - Users can log out, which updates the UI and the local storage to reflect the logout status.

### Technologies Used

- **HTML/CSS:** The project includes well-structured HTML and CSS for the user interface.
- **JavaScript:** JavaScript is used for dynamic functionality, including API interactions, user authentication, and DOM manipulation.

### Project Structure

The code is organized into functions responsible for specific tasks, promoting modularity and maintainability. Functions handle user authentication, book rendering, popups, navigation, and more.

### Recommendations

- Consider adding comments to the code for better readability and understanding.
- Test the application thoroughly, especially user authentication and book rendering functionalities.
- Enhance the UI/UX to provide a more visually appealing and user-friendly experience.

### Next Steps

Potential future enhancements might include adding search functionality, user reviews, or refining the overall user interface. Additionally, thorough testing and potential bug fixes are essential for a robust application.
## Features

List the main features of your project.

## Getting Started

### Prerequisites

Specify any prerequisites or system requirements needed to run your project.

### Installation

Provide step-by-step instructions on how to install and set up your project. Include any dependencies that need to be installed.

```bash
# Example command to install dependencies
npm install
```


## Usage Guide

### 1. Login or Register

- To access the full features of the application, start by logging in.
- If you don't have an account, click on the "Register" button to create a new account.

### 2. Explore Books

- Once logged in, you will land on the home page where you can explore books.
- The bestseller books and category lists are displayed by default.

### 3. Navigate Categories

- Click on a category in the list to see books specifically related to that category.
- The displayed books will dynamically update based on your selection.

### 4. View Book Details

- Click on a book to view detailed information in a popup.
- In the popup, you can find the book's title, author, description, and purchase links.

### 5. Add to Shopping List

- Inside the book popup, you have the option to add the book to your shopping list.
- Click the "Add to Shopping List" button to include the selected book.

### 6. Shopping List

- Navigate to the shopping list using the "Shopping List" button in the navigation bar.
- Here, you can view the books you've added, each with an option to remove it.

### 7. Logout

- If you want to log out, click on your user profile icon, and select the "Logout" option.

### Notes:

- **User Authentication:** Some features may require you to be logged in. If you're not logged in, you'll be prompted to do so.
  
- **Responsive Design:** The application is designed to work seamlessly on various devices, from desktops to mobile devices.

- **Adding Books:** Explore different categories, view book details, and build your shopping list.

### Enjoy exploring and discovering new books with your web application!

## Screenshots

![image](https://github.com/shah9380/My-Book-Application/assets/130676464/6251ae6d-605f-446a-b6db-9b76d9324d2e)

![image](https://github.com/shah9380/My-Book-Application/assets/130676464/96225fe3-e14e-4061-87ff-d6a78fc19219)

![image](https://github.com/shah9380/My-Book-Application/assets/130676464/f64a7aa9-19c1-4b2f-81af-c345d59a9f76)



## JavaScript Functions

### User Authentication

- **`showLogin`**: Toggles between the login and registration forms when the "Login" link is clicked.
- **`showRegister`**: Toggles between the login and registration forms when the "Register" link is clicked.
- **`signUpBtn`**: Handles the form submission for user registration, storing user data in local storage.

### User Session Management

- **`isLoggedIn`**: Checks the user's login status and updates the UI accordingly.

### Book Rendering and Interaction

- **`getMyBook`**: Fetches and renders books based on the selected category.
- **`data`**: Fetches and renders data from the API, including the best books and category lists.
- **`renderList`**: Renders the category list in the sidebar.
- **`renderBestBooks`**: Renders the best books on the main page.
- **`renderSelectedCategory`**: Renders books based on the selected category.
- **`scrollToTop`**: Scrolls the window to the top when called.

### Popup and Shopping List

- **`popSection`**: Handles the display and content of the popup for individual books.
- **`cardDelete`**: Deletes a book card from the shopping list.

### Navigation

- **`shop_Btn` and `Home_Btn` event listeners**: Toggle between shopping and home sections.
- **`BookBtn` event listener**: Handles the navigation when the "Book" button is clicked.

### User Logout

- **`logMeOut`**: Logs the user out, updating UI and local storage accordingly.
