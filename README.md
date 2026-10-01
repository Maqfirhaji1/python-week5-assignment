PLP Python Week 5 — Modules

This repository contains my Week 5 Python assignment for the PLP Python Programming course.

The assignment focuses on using Python modules, built-in libraries, creating custom modules, defining functions, and importing functions from another Python file.

Project Files
plp-python-week5/
│
├── password_generator.py
├── helpers.py
├── main.py
└── README.md

Question 1 — Password Generator

The password_generator.py program uses Python's built-in random and string modules to generate random passwords.

Features

Uses random.choice() to select random characters.

Uses string.ascii_letters for uppercase and lowercase letters.

Uses string.digits for numbers.

Provides a default password length of 8 characters.

Allows a custom password length.

Generates both an 8-character and a 12-character password.

Run the program
python password_generator.py

Example output
Password: zAi1lJ0z
Length: 8
Password: d04fiFjnrbEK
Length: 12


The passwords will be different each time the program runs because they are randomly generated.

Question 2 — Creating and Using a Custom Module

The second part demonstrates how to create a custom Python module and import it into another program.

helpers.py

The helpers.py module contains two functions:

tables_needed(people, seats)


Calculates the number of tables required using math.ceil().

welcome(name)


Creates a personalized PLP welcome message.

The file also demonstrates the use of:

if __name__ == "__main__":


This ensures that the test code in helpers.py runs only when the file is executed directly, not when it is imported.

main.py

The main.py file imports the custom helpers module:

import helpers


It then uses the functions provided by the module.

Run main.py
python main.py


Expected output:

Welcome to PLP, Amina!
8
4

Run helpers.py
python helpers.py


Expected output:

3


The 3 does not appear when running main.py because of the if __name__ == "__main__": condition.

Concepts Demonstrated

This assignment demonstrates:

Python modules and imports

The random module

The string module

The math module

random.choice()

math.ceil()

Functions

Default function parameters

Custom Python modules

The if __name__ == "__main__": pattern

Code organization across multiple files

Requirements

Python 3 is required to run these programs.

Check your Python version with:

python --version


or:

python3 --version

Important Note

The files must not be named:

math.py
random.py
string.py


These names would conflict with Python's built-in modules and could prevent the programs from working correctly.

Author

PLP Python Programming — Week 5 Assignment