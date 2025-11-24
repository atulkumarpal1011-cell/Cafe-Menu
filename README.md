 #Cafe Ordering System
##Overview of the Project

The Cafe Ordering System is a Python-based console application designed to simulate a restaurant ordering and billing experience. Customers can browse a categorized menu (Indian, Chinese, Italian), select multiple items with quantities, and receive a detailed final bill that includes discounts, service charges, and GST.

##Features

Display a categorized menu of dishes (Indian, Chinese, Italian) with prices.

Interactive ordering system with quantity selection.

Automatic calculation of:

Subtotal

Bulk discount (10% for orders above Rs. 3500)

Service charge (10%)

GST (18%)

Grand total

Prints a detailed final receipt.

User-friendly prompts with error handling for invalid inputs.

##Technologies/Tools Used

Programming Language: Python 3.x

Libraries: time (for simulating bill calculation delay)

Steps to Install & Run the Project

Ensure a version of Python 3 is installed on your system. You can download it from Python.org
.

Download or clone the repository containing the script.

Open a terminal or command prompt.

Navigate to the directory where the script is saved.

Run the script using the command:

python cafe_ordering_system.py

##Instructions for Testing

Run the script.

The menu will be displayed categorized by cuisine.

Choose a category to view items.

Enter the item number to add it to your order.

Input the quantity for the selected item.

Repeat steps 3–5 to add more items.

Type 'Done' when finished adding categories, or 'F' to finish ordering.

The system will calculate the final bill, apply discounts if applicable, and print a detailed receipt.

##Edge Cases to Test:

Ordering quantities of zero or negative numbers (should prompt again).

Entering invalid category or item numbers (should prompt again).

Ordering items totaling above Rs. 3500 to test bulk discount.

##Screenshots

Example of final receipt:

==================================================
               FINAL RECEIPT
==================================================
Qty Item                      Price     Amount
--------------------------------------------------
2   Butter Naan              100.00    200.00
1   Chicken Tikka Masala     450.00    450.00
--------------------------------------------------
SUBTOTAL (Items)                          Rs. 650.00
Service Charge (10%)                       +Rs. 65.00
Total Before GST                            Rs. 715.00
GST (18%)                                   +Rs. 128.70
==================================================
GRAND TOTAL TO PAY                          Rs. 843.70
==================================================
Thank you for dining with us! Please come again.
