# 🧮 Simple Calculator in C

## 📌 Project Overview

This is a beginner-friendly **Simple Calculator** program written in **C**. It performs basic arithmetic operations using the **`switch` statement** and user input.

The calculator accepts two integer numbers and an arithmetic operator from the user, then displays the calculated result. It also handles common errors such as division by zero and invalid operators.

---

## 🚀 Features

* ➕ Addition
* ➖ Subtraction
* ✖️ Multiplication
* ➗ Division
* ✅ Division by zero validation
* ✅ Invalid operator handling
* ✅ Easy-to-read and beginner-friendly code

---

## 🛠️ Technologies Used

* Programming Language: **C**
* Header File: `stdio.h`
* Concepts Covered:

  * Variables
  * User Input (`scanf`)
  * Output (`printf`)
  * `switch` Statement
  * `if-else` Conditions
  * Arithmetic Operators

---

## 📂 Program Flow

1. Ask the user to enter the first number.
2. Ask the user to enter an operator (`+`, `-`, `*`, `/`).
3. Ask the user to enter the second number.
4. Use a `switch` statement to determine which operation to perform.
5. Display the result.
6. If the user enters `/` and the second number is `0`, display an error message.
7. If the operator is invalid, display an appropriate error message.

---

## 💻 Example Output

### Addition

```
Enter first number:
10

Enter operator (+, -, *, /):
+

Enter second number:
5

Result = 15
```

### Division by Zero

```
Enter first number:
20

Enter operator (+, -, *, /):
/

Enter second number:
0

Division cannot be performed by zero.
```

### Invalid Operator

```
Enter first number:
10

Enter operator (+, -, *, /):
%

Enter second number:
5

Invalid operator.
```

---

## 📚 Concepts Practiced

* C Programming Basics
* Switch Case
* Conditional Statements
* Input and Output
* Error Handling
* Arithmetic Operations

---

## 🎯 Learning Objective

This project is designed for beginners who are learning C programming and want to understand how a `switch` statement can be used to build a menu-driven calculator. It also demonstrates the importance of validating user input to prevent runtime errors.

---

## 🔮 Future Improvements

* Support decimal numbers using `float` or `double`
* Add modulus (`%`) operation
* Perform multiple calculations without restarting the program
* Create a menu-driven calculator
* Improve user interface with better formatting

---

## 👨‍💻 Author

Created as a C programming practice project to strengthen understanding of **switch statements**, **conditional logic**, and **basic arithmetic operations**.
