# Python Challenge 1        
Repository: python_challenge_1

File: menu.py

## What it does

* Adapt menu to allow customers to place an order.
* This includes storing the customer order and printing
the receipt with the total prices of all items ordered.

## Overview
* Print menu - code already provided.
* Order system - new code.
* Order receipt - new code.

## Coding overview
* Dictionary: menu is a dict of dict.
* Dictionary: menu_items creates a dictionary to store the menu for
              later retrieval.
* Dictionary: selected_item
* List: customer_order is a  list of dict
* Variables: long list including place_order (bool), i (int), and
            menu_category (str)

## Coding notes
* Includes: while True, for loops, if else, and match: case
    
## Small sample program output

Welcome to the variety food truck.

From which menu would you like to order?

1: Snacks

2: Meals

3: Drinks

4: Dessert

Type menu number: 2

You selected Meals

What Meals item would you like to order?
Item # | Item name                | Price
-------|--------------------------|-------
1      | Burrito                  | $4.49
2      | Teriyaki Chicken         | $9.99
3      | Sushi                    | $7.49
4      | Pad Thai                 | $6.99
5      | Pizza - Cheese           | $8.99
6      | Pizza - Pepperoni        | $10.99
7      | Pizza - Vegetarian       | $9.99
8      | Burger - Chicken         | $7.49
9      | Burger - Beef            | $8.49

Type item number to order: 6

How many Pizza - Pepperoni would you like? 3

Would you like to order anything else? (Y)es or (N)o: n

Thank you for your order!

This is what we are preparing for you.

Item name                 | Price  | Quantity
--------------------------|--------|----------
Pizza - Pepperoni         |  $10.99 | 3

Total cost: $32.97

Have a great day!
