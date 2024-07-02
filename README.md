# Food-Ordering-System
This repository contains the source code for the FoodOrderingSystem, a Java-based GUI application that allows users to order food, drinks, and desserts from a menu. The application provides a user-friendly interface for selecting items, viewing the order summary, and placing the order.

# Features
User Interface: The application has a graphical user interface (GUI) built using JFrame and JPanel components from the Swing library.
Menu Categories: Users can select items from three categories: Foods, Drinks, and Desserts.
Order Summary: Displays the current order with the quantity and total price for each item.
Order Form: Allows users to enter their name, contact number, and address to place the order.
Dynamic Content: Menu items, prices, and images are dynamically loaded into the GUI.
Clear Order: Users can clear their current order and start over.
Order Validation: Ensures that all fields are filled out and that at least one item is added to the order before placing it.

# Requirements
Java Development Kit (JDK) 8 or higher.
An Integrated Development Environment (IDE) such as IntelliJ IDEA or Eclipse.
Required assets (images) should be placed in the assets directory.

# Installation
1. Clone the Repository:
git clone https://github.com/nxrymm/FoodOrderingSystem.git
cd FoodOrderingSystem

2. Open the Project in Your IDE:
Open your IDE and import the project from the cloned repository directory.
Ensure that the src directory is set as the source root.

3. Run the Application:
Run the FoodOrderingSystem class to start the application.

# Usage
1. Launch the Application:
Execute the FoodOrderingSystem class from your IDE.

2. Navigate the Interface:
Front Page: Click on the "ORDER NOW" button to start ordering.
Ordering Panel: Select items from the Foods, Drinks, or Desserts categories by clicking the respective buttons.
Add Items: Use the spinners to select the quantity for each item and the selected items will be added to the order summary.
View Order Summary: The right panel shows the current order summary with total price.
Clear Order: Click "CLEAR ALL" to reset your order.
Place Order: Click "PLACE ORDER" to proceed to the order form.

3. Complete the Order Form:
Fill in your name, contact number, and address.
Click "SUBMIT ORDER" to place your order.

# Code Overview
Main Class: FoodOrderingSystem
  Methods:
    main(String[] args): Entry point of the application.
    initialize(): Sets up the main frame and panels.
    createFrontPagePanel(): Creates the front page with the logo and order button.
    createOrderingPanel(): Sets up the ordering panel with category buttons and item panels.
    createOrderFormPanel(): Sets up the order form for user details.
    createItemPanel(String[] items, double[] prices, String[] images, String type): Creates panels for each menu category.
    switchToPanel(JPanel panel): Switches the current visible panel.
    switchToCategoryPanel(JPanel panel): Switches the visible category panel.
    updateOrderSummary(): Updates the order summary area with selected items.
    clearAllOrders(): Clears all selected items from the order.
    placeOrder(): Validates and submits the order.
