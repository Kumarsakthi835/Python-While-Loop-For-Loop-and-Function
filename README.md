# 📊 Data Analytics – Module 4

## Python Assignment 3 – While Loop, For Loop, and Function

**Module:** Module 4
**Assignment:** Python Assignment 3
**Platform:** Google Colab

---

## 📌 Assignment Overview

This assignment focuses on implementing **loops, control statements, functions, input handling, and logical problem-solving using Python**.

The assignment consists of three practical programs:

1. **Number Guessing Game** using a `while` loop
2. **Multiplication Table Generator** using a `for` loop
3. **BMI Calculator** using a user-defined function

These programs provide practical experience with Python programming concepts and demonstrate how loops and functions can be used to solve simple logical problems.

---

# 🎯 Task 1 – Number Guessing Game

## Objective

The objective of this task is to create a number guessing game using a **while loop**.

The program generates a random number between **1 and 10**, and the user attempts to guess the number within a limited number of attempts.

## Concepts Used

* While loop
* Conditional statements
* `break`
* `continue`
* `else`
* Random number generation
* User input
* Input validation

## Program Features

* Generates a random number between 1 and 10.
* Allows the user to make a maximum of three valid guesses.
* Displays **"Too low"** when the guess is smaller than the secret number.
* Displays **"Too high"** when the guess is greater than the secret number.
* Displays a congratulations message when the correct number is guessed.
* Handles numbers outside the valid range using `continue`.
* Uses `break` when the correct number is guessed.
* Uses the `else` block when the user runs out of attempts.

## Sample Input

The user enters different numbers as guesses during the game.

## Sample Output

The program displays feedback such as:

* Too low. Try again.
* Too high. Try again.
* Congratulations! You guessed the correct number.
* Your guess is out of range.

## 📸 Screenshot

![Task 1 Number Guessing Game code]

<img width="494" height="261" alt="image" src="https://github.com/user-attachments/assets/4d15f27b-7f3f-4a94-b358-66dcd7529717" />
<img width="565" height="259" alt="image" src="https://github.com/user-attachments/assets/4e4bc12b-ee53-4a3a-99a3-837dad77b563" />

[Task 1 Number Guessing Game Output]

<img width="485" height="157" alt="image" src="https://github.com/user-attachments/assets/ed230106-a595-4bf6-9784-443e585e8795" />

---

# 🔢 Task 2 – Multiplication Table Generator

## Objective

The objective of this task is to create a multiplication table from **1 to 10** using a **for loop** and the `range()` function.

## Concepts Used

* For loop
* `range()` function
* User input
* Arithmetic operations
* Output formatting

## Program Features

* Accepts a number from the user.
* Uses a for loop to iterate from 1 to 10.
* Calculates the multiplication result for each iteration.
* Displays the multiplication table in a clear format.

## Input Used

For this assignment, the number entered was:

**2**

## Output

The multiplication table generated was:

| Multiplication | Result |
| -------------- | -----: |
| 2 × 1          |      2 |
| 2 × 2          |      4 |
| 2 × 3          |      6 |
| 2 × 4          |      8 |
| 2 × 5          |     10 |
| 2 × 6          |     12 |
| 2 × 7          |     14 |
| 2 × 8          |     16 |
| 2 × 9          |     18 |
| 2 × 10         |     20 |

**Screenshot:** `Task_2_Multiplication_Table_Code_Output

<img width="593" height="267" alt="image" src="https://github.com/user-attachments/assets/6423eb40-3203-4451-9465-b386965f20b8" />




---

# ⚖️ Task 3 – BMI Calculator

## Objective

The objective of this task is to create a **BMI calculator using a user-defined function**.

The program accepts weight in kilograms and height in meters and calculates the Body Mass Index.

## BMI Formula

**BMI = Weight (kg) / Height (m)²**

## Concepts Used

* Function definition
* Function parameters
* `return` statement
* User input
* Arithmetic calculation
* Output formatting

## Program Features

* Defines a reusable BMI calculation function.
* Accepts weight from the user in kilograms.
* Accepts height from the user in meters.
* Calculates BMI using the standard formula.
* Displays the calculated BMI rounded to two decimal places.

## Input Used

**Weight:** 70 kg
**Height:** 1.75 m

## Output

**Your BMI is: 22.86**

**Screenshot:** `Task_3_BMI_Calculator_Code_Output

<img width="382" height="269" alt="image" src="https://github.com/user-attachments/assets/ff57c2b5-f49a-4fd4-9e60-d08f929e50d5" />




---

# 🧠 Skills Demonstrated

| Skill / Concept       | Application                                   |
| --------------------- | --------------------------------------------- |
| While Loop            | Number Guessing Game                          |
| For Loop              | Multiplication Table                          |
| `range()`             | Iteration from 1 to 10                        |
| `break`               | Stops the guessing game after a correct guess |
| `continue`            | Handles out-of-range guesses                  |
| `else`                | Handles unsuccessful attempts                 |
| Functions             | BMI Calculator                                |
| Function Parameters   | Weight and height inputs                      |
| User Input            | All three tasks                               |
| Conditional Logic     | Number Guessing Game                          |
| Arithmetic Operations | Multiplication and BMI calculation            |
| Output Formatting     | Displaying results clearly                    |

---

# 🛠️ Tools Used

* **Python**
* **Google Colab**
* **Jupyter Notebook Environment**

---

# 📁 Project Structure

```text
Python_Assignment_3/
│
├── Python_Assignment_3.ipynb
│
├── README.md
│
└── Screenshots/
    ├── Task_1_Number_Guessing_Game_Final.png
    ├── Task_2_Multiplication_Table_Code_Output.png
    └── Task_3_BMI_Calculator_Code_Output.png
```

---

# 📚 Learning Outcomes

Through this assignment, the following Python concepts were practiced:

* Understanding and implementing `while` loops.
* Understanding and implementing `for` loops.
* Using the `range()` function for iteration.
* Applying `break`, `continue`, and `else` control statements.
* Creating and using functions.
* Passing arguments to functions.
* Handling user input.
* Applying conditional logic.
* Performing arithmetic calculations.
* Displaying formatted output.
* Developing basic logical problem-solving skills.

---

# 📊 Assignment Completion Summary

| Task   | Program              | Main Concept                    | Status      |
| ------ | -------------------- | ------------------------------- | ----------- |
| Task 1 | Number Guessing Game | While Loop & Control Statements | ✅ Completed |
| Task 2 | Multiplication Table | For Loop & Range                | ✅ Completed |
| Task 3 | BMI Calculator       | Function & Parameters           | ✅ Completed |

---

# 📝 Conclusion

This assignment provided practical experience with fundamental Python programming concepts required for Data Analytics.

The **Number Guessing Game** helped demonstrate while loops and control statements. The **Multiplication Table Generator** provided practice with for loops and the `range()` function. The **BMI Calculator** demonstrated the use of functions, parameters, and return values.

Overall, the assignment improved understanding of **iteration, control flow, functions, input handling, and logical problem-solving using Python**.

---

*Kumar S

*Data Analyst
