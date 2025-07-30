## 🎯 AIM
To learn how to use **for**, **while**, and **do while** loops in C++ for automating repetitive tasks, implementing algorithms, and improving program control flow.
## 📚 THEORY
Loops allow a block of code to execute repeatedly, making them essential for:

* Automating repetitive operations
* Processing collections of data
* Implementing algorithms efficiently
  
* Initialize Variables
    Set a fixed password (e.g., "BCD9QTTU").

    Create a variable to store user input.

    Set attempts to 0.

    Define a maximum number of attempts (e.g., 3).

Loop While Attempts Are Less Than Maximum

    Prompt the user to enter the password.

    Hide the input characters (optional, depending on system).

    Capture each character typed until the Enter key is pressed.

        If the character is Backspace, remove the last character from the input.

        Otherwise, add the character to the input and show * on the screen.

Validate the Password

    If the entered password matches the stored password:

        Display "System is Unlocked".

        Exit the program.

    If not:

        Increment the attempt counter.

        Display "Incorrect Password" and show remaining attempts.

Lock the System if Attempts Exceed Limit

    After maximum attempts, display "System is locked".

    Exit the program.
  
## 🔄 Types of Loops in C++
* **For Loop:** Best when the number of iterations is known. It combines initialization, condition, and increment in one line. Commonly used for counting or traversing arrays.
* **While Loop:** Ideal when the number of iterations depends on a condition that is evaluated before each cycle. Useful for waiting on input or dynamic conditions.
* **Do While Loop:** Executes the loop body at least once before checking the condition. Perfect for scenarios like menus or input validation where the code must run at least once.
* 
## 🧭 Loop Control Statements
* **break:** Immediately stops the loop when a specific condition is met.
* **continue:** Skips the current iteration and proceeds to the next one, helping simplify logic inside loops.
* 
## 🔁 Nested Loops
Loops placed inside other loops, used for generating patterns, working with multi-dimensional arrays, or creating complex output structures

## 🧠 Common Loop Algorithms

* **Factorial Calculation:** Multiplying numbers from 1 to *n*.
* **Fibonacci Sequence:** Each term is the sum of the two preceding ones.
* **Prime Number Check:** Verifies if a number has no divisors other than 1 and itself.
* **Sum of Natural Numbers:** Adds numbers sequentially from 1 to *n*.
* **Pattern Generation:** Prints shapes or tables using nested loops.
* 
## ⚙️ Loop Optimization Tips

* Keep loop bodies simple and avoid unnecessary calculations.
* Use efficient and easy-to-evaluate conditions.
* Minimize memory access inside loops by caching values.
* Avoid deep nesting to reduce complexity.
* Use `break` to exit loops early when possible.

## ✅ CONCLUSION
Loops are fundamental in C++ programming for managing repetition and control flow. Understanding when and how to use `for`, `while`, and `do while` loops, along with control statements and optimization, is key to writing clear, efficient, and maintainable code.
Would you like sample C++ code snippets demonstrating these loops?
