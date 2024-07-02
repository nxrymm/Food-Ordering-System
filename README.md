# Food-Ordering-System
This repository contains the source code for the FoodOrderingSystem, a Java-based GUI application that allows users to order food, drinks, and desserts from a menu. The application provides a user-friendly interface for selecting items, viewing the order summary, and placing the order.

# Features
•	User Interface: The application has a graphical user interface (GUI) built using JFrame and JPanel components from the Swing library.
•	Menu Categories: Users can select items from three categories: Foods, Drinks, and Desserts.
•	Order Summary: Displays the current order with the quantity and total price for each item.
•	Order Form: Allows users to enter their name, contact number, and address to place the order.
•	Dynamic Content: Menu items, prices, and images are dynamically loaded into the GUI.
•	Clear Order: Users can clear their current order and start over.
•	Order Validation: Ensures that all fields are filled out and that at least one item is added to the order before placing it.

# Requirements
• Java Development Kit (JDK) 8 or higher.
• An Integrated Development Environment (IDE) such as IntelliJ IDEA or Eclipse.
• Required assets (images) should be placed in the assets directory.

# Installation
1. Clone the Repository:
git clone https://github.com/nxrymm/FoodOrderingSystem.git
cd FoodOrderingSystem

2. Open the Project in Your IDE:
• Open your IDE and import the project from the cloned repository directory.
• Ensure that the src directory is set as the source root.

3. Run the Application:
• Run the FoodOrderingSystem class to start the application.

# Usage
1. Launch the Application:
• Execute the FoodOrderingSystem class from your IDE.

2. Navigate the Interface:
• Front Page: Click on the "ORDER NOW" button to start ordering.
![Screenshot (61)](https://github.com/nxrymm/Food-Ordering-System/assets/164466808/87bffbf4-c4e9-47df-a679-12d08dd430b6)

• Ordering Panel: Select items from the Foods, Drinks, or Desserts categories by clicking the respective buttons.
• Add Items: Use the spinners to select the quantity for each item and the selected items will be added to the order summary.
• View Order Summary: The right panel shows the current order summary with total price.
• Clear Order: Click "CLEAR ALL" to reset your order.
• Place Order: Click "PLACE ORDER" to proceed to the order form.
![Screenshot (62)](https://github.com/nxrymm/Food-Ordering-System/assets/164466808/5239dafe-8b6a-4a7b-a001-90dec591552f)
![Screenshot (63)](https://github.com/nxrymm/Food-Ordering-System/assets/164466808/e3add00b-d1db-4b81-9266-62504a98344f)
![Screenshot (64)](https://github.com/nxrymm/Food-Ordering-System/assets/164466808/7d644781-a4ee-4919-95ea-344862bb43a2)
![Screenshot (65)](https://github.com/nxrymm/Food-Ordering-System/assets/164466808/adce732d-dbf3-4716-90ac-7303e28a93de)

3. Complete the Order Form:
• Fill in your name, contact number, and address.
![Screenshot (66)](https://github.com/nxrymm/Food-Ordering-System/assets/164466808/b6bc036c-c916-4122-a689-95f4b47e8f96)
![Screenshot (67)](https://github.com/nxrymm/Food-Ordering-System/assets/164466808/39f3bdcf-6289-4b49-99fc-c29f50972dba)

• Click "SUBMIT ORDER" to place your order.
![Screenshot (68)](https://github.com/nxrymm/Food-Ordering-System/assets/164466808/8b12a470-5774-4855-b9fc-5c0eddc1c5d6)
![Screenshot (69)](https://github.com/nxrymm/Food-Ordering-System/assets/164466808/66466306-e76b-45d0-b934-566d5f0e2801)
![Screenshot (70)](https://github.com/nxrymm/Food-Ordering-System/assets/164466808/79852312-c00f-4ff8-926a-2a48c71e2d91)


# Code Overview
• Main Class: FoodOrderingSystem
  • Methods:
  
    • main(String[] args): Entry point of the application.
    • initialize(): Sets up the main frame and panels.
    • createFrontPagePanel(): Creates the front page with the logo and order button.
    • createOrderingPanel(): Sets up the ordering panel with category buttons and item panels.
    • createOrderFormPanel(): Sets up the order form for user details.
    • createItemPanel(String[] items, double[] prices, String[] images, String type): Creates panels for each menu category.
    • switchToPanel(JPanel panel): Switches the current visible panel.
    • switchToCategoryPanel(JPanel panel): Switches the visible category panel.
    • updateOrderSummary(): Updates the order summary area with selected items.
    • clearAllOrders(): Clears all selected items from the order.
    • placeOrder(): Validates and submits the order.
    
# Group 1
MEMBERS:
Fulgencio, Hercie M.
Gloria, Nicole Rhyme V.
Mendola, Jana Dee N.
Omison, Jamel D.
Tamio, Riza Mae G.

# Group Documentation
![Screenshot_2024-07-02-22-51-14-548_com discord](https://github.com/nxrymm/Food-Ordering-System/assets/164466808/97d63ce3-a558-417d-a87c-30127c72a927)

# GDRIVE LINK FOR OVERALL DOCUMENTATION AND SOURCE CODE
https://drive.google.com/drive/folders/1Uv7k20v6Tk1UZsh8Xryy8LPUWB6nrVj9
