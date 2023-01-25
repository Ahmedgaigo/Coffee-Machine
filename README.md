# Coffee-Machine
Coffee Maker Application
This is a simple application that models a coffee maker machine. The application is built using Python classes, and includes the following features:

CoffeeMaker: This class models the coffee maker machine and contains methods to check resources, make coffee, and print a report of all resources.

MenuItem: This class models each menu item and contains information about the ingredients required to make the drink, as well as the cost of the drink.

Menu: This class models the menu of the coffee maker machine and contains methods to get all menu items, and find a particular drink by name.

MoneyMachine: This class models the money machine of the coffee maker machine and contains methods to process coins, make payment, and print the current profit.

Usage:
To use this application, you will need to create an instance of the CoffeeMaker class, Menu class and MoneyMachine class. You can then use the methods provided by these classes to make a coffee, check resources, make a payment and check the profit.

********************************************************************
For example, you can use the following code snippet to make a latte:
coffee_maker = cm()
menu = m()
money_machine = mm()

order = menu.find_drink("latte")
if coffee_maker.is_resource_sufficient(order) and money_machine.make_payment(order.cost):
    coffee_maker.make_coffee(order)
*****************************************************************************************
Resources
The resources of the coffee maker machine can be modified by changing the values in the resources dictionary in the __init__ method of the CoffeeMaker class.

Menu Items
The menu items can be modified by adding or removing items from the menu list in the __init__ method of the Menu class.

Coin values
The coin values can be modified by changing the values in the COIN_VALUES dictionary in the MoneyMachine class.

Reports
You can use the report() method of the CoffeeMaker and MoneyMachine classes to print a report of the resources and the current profit respectively.
