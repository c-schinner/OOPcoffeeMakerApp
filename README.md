# Object-Oriented Coffee Machine Program
The Object-Oriented Coffee Machine Program is a Python application that simulates the functionality of a coffee machine. It is designed using object-oriented programming principles to create a modular and maintainable system for preparing various drinks and managing resources and payments.

# Features
Choose from a menu of different drinks, each with its own recipe and cost.

Check the resources available in the coffee machine.

Make a payment for the selected drink and receive the drink if payment is successful.

Generate reports of the coffee machine's status, including resources and financial data.

# Components
The program consists of the following main components:

Menu: The Menu class is responsible for defining the available drinks, their ingredients, and their costs.

CoffeeMaker: The CoffeeMaker class handles the preparation of drinks by checking resource availability and making the drink if possible.

MoneyMachine: The MoneyMachine class manages the financial aspect of the coffee machine, including processing payments and keeping track of money.

# How to Use
1. Make sure you have Python installed on your system.

2. Download or copy the provided code into a Python file (e.g., coffee_machine.py).

3. Ensure that the menu.py, coffee_maker.py, and money_machine.py files are present in the same directory as the main file.

4. Open a terminal or command prompt and navigate to the directory where the Python files are located.

5. Run the program by executing the following command:

        python coffee_machine.py

6. The program will display the available drink options from the menu and prompt you to choose a drink. You can enter the name of the drink as shown in the menu.

7. If you enter 'off', the program will turn off the coffee machine.

8. If you enter 'report', the program will generate and display a report containing resource status and financial information.

9. For any other valid drink choice, the program will check resource availability, process the payment, and dispense the drink if payment is successful.

# Example

    What would you like to drink? (latte/espresso/cappuccino): latte
    Please insert coins.
    How many quarters?: 9
    How many dimes?: 10
    How many nickels?: 5
    How many pennies?: 0
    Payment successful. Enjoy your latte!

    What would you like to drink? (latte/espresso/cappuccino): report
    Water: 300ml
    Milk: 200ml
    Coffee: 100g
    Money: $2.5

    What would you like to drink? (latte/espresso/cappuccino): off

# Note
This program is designed for educational purposes and as a demonstration of object-oriented programming concepts. 

It does not handle real transactions or monetary systems.

You can extend and modify this program by adding more drinks, customizing recipes, or implementing additional features.

# Author
This Object-Oriented Coffee Machine Program was created by Chris Schinner.

Feel free to experiment with the program and adapt it to your needs. Enjoy your virtual coffee-making experience!





