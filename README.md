# Coffee-Machine

This code models a coffee machine and its functionality. The CoffeeMaker class has the following methods:

__init__(): Initializes the resources (water, milk, and coffee) of the coffee machine.
report(): Prints a report of all resources.
is_resource_sufficient(drink): Returns true when order can be made, false if ingredients are insufficient.
make_coffee(order): Deducts the required ingredients from the resources.
The MenuItem class has the following methods:

__init__(name, water, milk, coffee, cost): Initializes a menu item with the given name, cost and ingredients(water, milk and coffee).
The Menu class has the following methods:

__init__(): Initializes the menu with drinks.
get_items(): Returns all the names of the available menu items.
find_drink(order_name): Searches the menu for a particular drink by name. Returns that item if it exists, otherwise returns None.
The MoneyMachine class has the following methods:

__init__(): Initializes the profit and money received by the machine.
report(): Prints the current profit.
process_coins(): Returns the total calculated from coins inserted.
make_payment(cost): Returns true when payment is accepted, or false if insufficient.
This code also imports the Menu, MenuItem and CoffeeMaker classes from the menu, coffee_maker and MoneyMachine classes from the money_machine module.

Usage
You can use this code by creating an instance of the CoffeeMaker class, Menu class and MoneyMachine class and calling their methods as required.
