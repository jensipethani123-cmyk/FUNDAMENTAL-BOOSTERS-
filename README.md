# PR. 1 Fundamental Booster 

An interactive Python application designed to collect, process, and display personal user data while demonstrating foundational programming concepts like variables, input/output functions, type casting, built-in functions (`type()`, `id()`), and basic arithmetic operations.

## Author
* **Jensi Pethani**
* **Course/Project:** Python Practical Assignment

## 🎯 Project Objectives
* **User Input Handling:** Collect personal information dynamically using `input()`.
* **Data Type Inspection:** Display the data type and memory address of variables using `type()` and `id()`.
* **Basic Calculation:** Calculate the user's approximate birth year based on their age.

## ✨ Features & Functionality
1. **Data Collection:**
   * Name as a string (`str`)
   * Age as an integer (`int`)
   * Height in meters as a floating-point number (`float`)
   * Favorite number as an integer (`int`)

2. **Data Type & Memory Inspection:**
   * Displays each entered value along with its Python data type using `type()`.
   * Displays its unique object identity/memory address using `id()`.

3. **Age-to-Year Calculator:**
   * Automatically calculates the approximate birth year using the formula: `birth_year = 2026 - age`.

## 💻 Technologies Used
* Python 3
* Visual Studio Code
* Git & GitHub

## 📚 Concepts Covered
* `input()` function & output formatting
* Variables and assignment
* Data types (`str`, `int`, `float`) and type conversion
* Built-in functions: `type()`, `id()`
* Arithmetic operations
* Console input/output handling

## 📂 Project Structure
```text
Project-1/
│
├── Fundamental_Booster.py
├── README.md
└── output.png

🖥️ Sample Output

Welcome to the Interactive Personal Data Collector!

Please enter your name: Jensi
Please enter your age: 19
Please enter your height in meters: 1.69
Please enter your favourite number: 11

Thank you for providing your information!

Name: Jensi (Type: <class 'str'>, Memory Address: 3166906178016)
Age: 19 (Type: <class 'int'>, Memory Address: 140726799746744)
Height: 1.69 (Type: <class 'float'>, Memory Address: 3166903186320)
Favourite Number: 11 (Type: <class 'int'>, Memory Address: 140726799746488)

Your birth year is approximately: 2007 (based on your age of 19)

Thank you for using the Personal Data Collector. Goodbye!
