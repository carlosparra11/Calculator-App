Calculator App

A simple command-line calculator written in Python. It asks you to pick an operation, enter two numbers, and prints the result.

Features
Addition, subtraction, multiplication, and division
Input validation: re-prompts if you enter something that isn't a number or pick an option outside 1–4
Prevents division by zero by asking for a new second number
Requirements
Python 3.10 or newer (uses the match statement)
Project Structure
Calculator-App/
├── app.py                        # Entry point and user interaction
└── calculator/
    └── calculator_methods.py     # add, subtract, multiply, divide
Usage
bash
git clone https://github.com/carlosparra11/Calculator-App.git
cd Calculator-App
python app.py

Example session:

Pick a number to select an operation:
1. Addition
2. Subtraction
3. Division
4. Multiplication

What operation do you want to do?: 1
What is the first number?: 5
What is the second number?: 3
The result of the Addition is 8.0
