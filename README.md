Velvet Patisserie Restaurant Management System 
Overview
This is a Python GUI application built with Tkinter for managing orders at Velvet Patisserie, a bakery. It allows customers to view the menu, add items to their order interactively, and keeps track of the total bill with a visually appealing interface.

Features
Displays bakery menu items with prices in an easy-to-read format.

Users can add items to their order by clicking "Add to Order" buttons.

Dynamically updates the list of ordered items along with their prices.

Shows the running total amount to pay, with a subtle animated color effect on the total for enhanced user experience.

Simple and intuitive interface suitable for a small bakery or café.

Menu
Item	                                Price (Rs.)
Classic Vanilla Bean Cake	            750
Chocolate Molten Cake with Ice Cream	1000
Pain au Chocolat	                    650
Cinnamon Rolls	                      700
Lemon Blueberry cupcake	              350
Gourmet Macarons	                    900
How to Run
Make sure Python 3.x is installed on your system.

Tkinter comes pre-installed with most Python distributions.

Save the provided script in a file named, for example, velvet_patisserie.py.

Run the script via command line or an IDE:

text
python velvet_patisserie.py
The application window will open, displaying the menu and order interface.

How It Works
The menu dictionary stores items with their prices.

The BakeryApp class manages the application window, menu display, order list, and total price.

Buttons beside each menu item add that item to the order list on click.

The total price label updates every time an item is added, with a brief color animation to highlight the change.

The order list shows each selected item alongside its price.

Possible Enhancements
Adding item quantity selection.

Ability to remove items from the order.

Saving and printing bills.

Integration with payment gateways or databases.
