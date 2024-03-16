Coffee Machine (OOP Implementation)

This is a simple Python program that simulates a coffee machine using Object-Oriented Programming (OOP) principles. Users can interact with the machine by selecting drinks from a menu, checking the available resources, and placing orders. The program utilizes classes and objects to encapsulate related functionality and maintain code modularity.
How to Use

  Run the program.
  Follow the instructions prompted in the console.
  Select a drink from the available menu.
  If you want to turn off the machine, type "off".
  To get a report of the available resources, type "report".

Files

  menu.py: Defines the Menu and MenuItem classes to manage the drink menu.
  coffee_maker.py: Defines the CoffeeMaker class to manage the coffee-making process and check resources.
  money_machine.py: Defines the MoneyMachine class to handle payments and keep track of profits.
  main.py: Contains the main program logic.

Classes

  Menu: Manages the menu of available drinks and provides methods to access it.
  MenuItem: Represents an item in the menu with its name, ingredients, and cost.
  CoffeeMaker: Models the coffee-making machine, checks resource sufficiency, and prepares drinks.
  MoneyMachine: Handles payments, calculates change, and keeps track of profits.

Object-Oriented Design

This program follows an object-oriented design approach, where different aspects of the coffee machine functionality are encapsulated within separate classes. This design promotes code reusability, modularity, and maintainability.
Dependencies

  No external dependencies are required. This program runs using only Python's built-in modules.
