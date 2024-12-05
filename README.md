# Python Menu Ordering System

This Python script, `menu.py`, allows users to place an order from a variety of menu items, stores their order, and generates a receipt with the total price. It's designed to be simple and interactive, making it easy for customers to select items and quantities.

---

## Features

- Displays categorized menus (Snacks, Meals, Drinks, Dessert).
- Allows customers to select items and specify quantities.
- Continues taking orders until the customer decides to stop.
- Generates a detailed receipt summarizing items ordered and the total price.

---

## How to Run

1. Ensure you have **Python 3.9 or later** installed on your system.
2. Clone or download this repository to your computer.
3. Open a terminal, navigate to the folder containing `menu.py`, and run:

   ```bash
   python menu.py
   ```

---

## Example Output

```plaintext
Welcome to the variety food truck.
From which menu would you like to order?
1: Snacks
2: Meals
3: Drinks
4: Dessert
Type menu number: 1
You selected Snacks
What Snacks item would you like to order?
Item # | Item name                | Price
-------|--------------------------|-------
1      | Cookie                   | $0.99
2      | Banana                   | $0.69
3      | Apple                    | $0.49
4      | Granola bar              | $1.99
Which item would you like to order? 1
How many of the item 'Cookie' would you like?
(Enter whole number. Default will be 1 if invalid or missing.): 3
Would you like to keep ordering? (Y)es or (N)o y
From which menu would you like to order?
1: Snacks
2: Meals
3: Drinks
4: Dessert
Type menu number: 4
You selected Dessert
What Dessert item would you like to order?
Item # | Item name                | Price
-------|--------------------------|-------
1      | Chocolate lava cake      | $10.99
2      | Cheesecake - New York    | $4.99
3      | Cheesecake - Strawberry  | $6.49
4      | Australian Pavlova       | $9.99
5      | Rice pudding             | $4.99
6      | Fried banana             | $4.49
Which item would you like to order? 1
How many of the item 'Chocolate lava cake' would you like?
(Enter whole number. Default will be 1 if invalid or missing.): 3
Would you like to keep ordering? (Y)es or (N)o n

Thank you for your order
This is what we are preparing for you.

Item name                 | Price  | Quantity
--------------------------|--------|----------
Cookie                    | $0.99  | 3
Chocolate lava cake       | $10.99 | 3
----------------------------------------------
                           TOTAL PRICE: $35.94
----------------------------------------------
```

---

## Prerequisites

- Python **3.9 or later**.

---

## Tests

- Test manually

---

## Notes

An additional feature was added to detect if an item had already been ordered and, if it had, subsequent orders would increase the quantity rather than adding the item to the order again with a new quantity.


