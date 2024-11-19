# Restaurant Ordering System

This is a simple Python program that simulates a restaurant menu where users can order items and the system calculates the total price.

## Features

- Displays a menu of available items with their prices.
- Allows customers to order multiple items.
- Keeps track of the total price of the order.
- Supports checking for invalid item selections and prompts the user to choose a valid item.

## Requirements

- Python 3.x
- A terminal or command prompt to run the Python script.

## Code Explanation

The code consists of two main functions: `manager()` and `main()`. 

### `manager()` function
This function greets the user and asks if they would like to place an order. If the customer responds with "yes", it displays the menu and continues to process the order. If they respond with "no", the program exits.

### `main()` function
This function manages the ordering process:
1. It prompts the user to select an item from the menu.
2. It checks if the item is available in the `menu` dictionary and adds its price to the total order.
3. It asks if the user wants to order another item.
4. If the user selects an invalid item, it asks them to choose again.
5. Finally, it displays the total price of the order and ends the session.

## Example

``bash git clone https://github.com/your-username/restaurant-ordering-system.git``


``bash cd restaurant-ordering-system``

