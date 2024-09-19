# **Shopping List Program**

A simple Python command-line application that allows users to create a shopping list by adding items with their corresponding prices. The program displays the total cost of all items added to the list.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)

## Project Overview

This Shopping List Program is designed to help users easily keep track of their shopping items and their prices. It allows users to:

* Add items and their prices.
* View the entire shopping list.
* Calculate the total cost of all items.

The program continues to prompt users to enter items and prices until they choose to quit by typing 

  'q'.

## Features

* **Add Items**: Users can add items and specify their prices.
* **Display List**: After the user finishes adding items, the program prints the entire shopping list.
* **Calculate Total**: The program calculates and displays the total cost of all items in the list.
* **Input Validation**: Handles incorrect price inputs and prompts users to enter a valid price.


## Installation

1. Clone the repository:

        git clone https://github.com/your-username/shopping-list.git
    
        cd shopping-list

2. Ensure you have Python 3.x installed on your machine.

## Usage

To run the program, execute the following command in your terminal:

    python shopping_list.py

Example:

    What item would you like to add to your shopping list? (Enter 'q' to quit): Apple
    Enter the price of Apple: £0.99
    What item would you like to add to your shopping list? (Enter 'q' to quit): Bread
    Enter the price of Bread: £1.50
    What item would you like to add to your shopping list? (Enter 'q' to quit): q
    
    ----- YOUR SHOPPING LIST -----
    Apple: £0.99
    Bread: £1.50
    
    Your total is: £2.49

Error Handling Example:

    What item would you like to add to your shopping list? (Enter 'q' to quit): Milk
    Enter the price of Milk: £abc
    Invalid input. Please enter a valid price.
    Enter the price of Milk: £1.75

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-name).
3. Make your changes and commit them (git commit -m "Add feature").
4. Push to the branch (git push origin feature-name).
5. Open a pull request describing the changes.
