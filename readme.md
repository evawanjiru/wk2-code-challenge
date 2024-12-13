# Interactive Shopping List

## Overview
This project is a simple web-based shopping list application that allows users to add, mark items as purchased, and clear the entire list. The application is built with HTML, CSS, and JavaScript, and features an interactive user interface with real-time updates to the shopping list.

## Features
- Add Item: Users can type an item into the input field and click "Add" to add it to the list.
- Mark as Purchased: Each item has a "Mark Purchased" button to toggle its purchased status. Purchased items are visually struck through and highlighted with a background color.
- Clear List: Users can clear all items from the shopping list with the "Clear List" button.
- Responsive Design: The application is fully responsive and works across various screen sizes.

## Tech Stack
- HTML: Structure and content of the application.
- CSS: Styling and layout to make the app visually appealing.
- JavaScript: Functionality for managing the shopping list, adding items, marking items as purchased, and clearing the list.

## Code Explanation
## HTML 
Contains the basic structure of the shopping list, including the input field, buttons, and the shopping list container.

## CSS
Provides styles for the application, including layout, button styles, and list item appearance. It also includes hover effects and a strikethrough style for purchased items.

## JavaScript
- Array (shoppingList): Holds the list of shopping items.
- renderList(): Renders the current list of items to the HTML. This function updates the list each time an item is added or marked as purchased.
- addItem(): Adds a new item to the shopping list when the user clicks the "Add" button.
- togglePurchased(): Toggles the purchased state of an item when the "Mark Purchased" button is clicked.
- clearList(): Clears all items from the shopping list when the "Clear List" button is clicked.

