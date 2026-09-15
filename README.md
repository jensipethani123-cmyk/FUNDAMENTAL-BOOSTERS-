# PR. 1 Fundamental Booster - Personal Data Collector

An interactive Python application designed to collect, process, and display personal user data while demonstrating foundational programming concepts like variables, input/output functions, type casting, built-in functions (`type()`, `id()`), and basic arithmetic operations.

## Author
* **Jensi Pethani**

## Features
* **Interactive Data Input:** Gathers user name (string), age (integer), height in meters (float), and favourite number (integer).
* **Data Inspection:** Displays each collected variable's value along with its data type using `type()` and its memory location using `id()`.
* **Data Processing:** Calculates the approximate birth year based on the current year and the user's input age.
* **Formatted Output:** Uses clean prints and messages to guide the user from start to finish.

## Example Console Output
```text
Welcome to the Interactive Personal Data Collector!

Please enter your name: Alice
Please enter your age: 25
Please enter your height in meters: 1.68
Please enter your favourite number: 7

Thank you! Here is the information we collected:
Name: Alice (Type: <class 'str'>, Memory Address: 140703847239568)
Age: 25 (Type: <class 'int'>, Memory Address: 9793456)
Height: 1.68 (Type: <class 'float'>, Memory Address: 140703847253232)
Favourite Number: 7 (Type: <class 'int'>, Memory Address: 9793312)

Your birth year is approximately: 2001 (based on your age of 25)

Thank you for using the Personal Data Collector. Goodbye!