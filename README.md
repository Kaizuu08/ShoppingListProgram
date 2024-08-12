Shopping List Program
This Shopping List Program is a Python-based application that allows users to manage a virtual shopping experience by reading inventory data, purchasing items, and generating a receipt. The program features both a command-line interface and a simple GUI using Tkinter for easy interaction.

Features:
Inventory Management: The program reads inventory from a text file and displays the available items, including their price, aisle, and stock quantity.

Purchasing Items: Users can purchase items from the inventory by specifying the item name, aisle, and quantity. The program checks the availability and deducts the purchased amount from the inventory.

Checkout and Receipt Generation: After selecting items, users can checkout to finalize their purchase. The program generates a receipt, listing all purchased items, their prices, and the total cost, which is saved to a receipt.txt file.

GUI Interface: The program includes a graphical user interface (GUI) built with Tkinter, offering buttons for viewing inventory, making purchases, checking out, and quitting the application.

How It Works:
Inventory File: The inventory data is stored in a inventory.txt file in CSV format, with each line containing the item name, price, aisle, and stock quantity.

Main Program Flow:

Inventory: Displays the current inventory.
Buy: Allows the user to purchase items, checking availability and updating stock.
Checkout: Generates and writes the purchase receipt to a file.
Quit: Exits the program.
Graphical User Interface:

The GUI presents buttons for each action (Inventory, Buy, Checkout, Quit) and displays the output in the terminal.
Getting Started:
Ensure you have Python installed.
Place the inventory.txt file in the same directory as the script.
Run the script to start the program.
