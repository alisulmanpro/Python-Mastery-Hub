# Programming Fundamentals | Python

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![License](https://img.shields.io/badge/license-Apache%205-green.svg)](LICENSE)
[![License](https://img.shields.io/badge/license-GPL%20v4-green.svg)](LICENSE)

This is a simple step-by-step Python learning hub for complete beginners. You start from zero and slowly become good at coding. We have 7 levels. Each level teaches one important topic with easy practice questions. Practice is the only way to learn coding well – do every question yourself. After the levels, try the 20 fun console projects to use everything you learned.

---

![Image](https://github.com/user-attachments/assets/78a742f8-9334-4f86-b25d-98d0ca2242d8)

---

## Table of Contents
- [Level 1: Python Basics - Variables & Input/Output](#level-1-python-basics---variables--inputoutput)
- [Level 2: Working with Text - Strings](#level-2-working-with-text---strings)
- [Level 3: Making Decisions - Conditionals](#level-3-making-decisions---conditionals)
- [Level 4: Repeating Tasks - Loops](#level-4-repeating-tasks---loops)
- [Level 5: Organizing Data - Lists & Tuples](#level-5-organizing-data---lists--tuples)
- [Level 6: Advanced Collections - Sets & Dictionaries](#level-6-advanced-collections---sets--dictionaries)
- [Level 7: Reusable Code - Functions](#level-7-reusable-code---functions)
- [20 Console Projects](#20-console-projects)

---

### Level 1: Python Basics - Variables & Input/Output

**Why this level?**  
Learn how to store data in variables, take input from user, and print results. This is the first step of every Python program.

1. **Swap Two Numbers**  
   Define two numbers in variable. Swap them without extra variable. Print both after swap.
   
   ```markdown
   Example: Input `First = 10` and `Second = 20` → Output: `First = 20`, `Second = 10`
   ```
   
2. **Swap Two Strings**  
   Take two strings from user. Swap them without extra variable. Print both after swap.
   
   ```markdown
   Example: Input `First = "Ali"` and `Second = "Alia"` → Output: `First = "Alia"`, `Second = "Ali"`
   ```

3. **Add Two Numbers**  
   Ask user for two numbers. Add them and print the sum.
   
   ```markdown
   Example: Input `5` and `8` → Output: `Sum = 13`
   ```

4. **Area of Rectangle**  
   Ask user for length and width. Calculate area and print it.
   
   ```markdown
   Example: Input `4` and `6` → Output: `Area = 24`
   ```

5. **Say Hello to User**  
   Ask user for name. Print `Hello [Name]!`
   
   ```markdown
   Example: Input `Ali` → Output: `Hello Ali!`
   ```

6. **Full Name Greeting**  
   Ask for first name and last name. Join them and print greeting.
   
   ```markdown
   Example: Input `Alia` and `Mirza` → Output: `Hello, Alia Mirza!`
   ```

7. **Welcome with Age**  
   Ask for name and age. Print welcome message using f-string.

   ```markdown
   Example: Input `Ali` and `20` → Output: `Welcome, Ali! You are 20 years old.`
   ```

---

### Level 2: Working with Text - Strings

**Why this level?**  
Learn how to work with words and sentences. Almost every program needs text.

1. **String Length Counter**  
   Ask user for a sentence. Print how many characters it has.
   
   ```markdown
   Example: Input `Hello Pakistan` → Output: `Length: 14`
   ```

2. **Upper and Lower Case**  
   Ask for a string. Print it in uppercase and lowercase.

   ```markdown
   Example: Input `Python` → Output: `UPPER: PYTHON`, `lower: python`
   ```

3. **Name Formatting**  
   Ask first and last name. Print normal, uppercase, and title case.

   ```markdown
   Example: Input `lilly`, `collins` → Output: `Normal: lilly collins`, `Title Case: Lilly Collins`
   ```

4. **Count Vowels**  
   Ask for a word. Count vowels (a,e,i,o,u – ignore case).

   ```markdown
   Example: Input `education` → Output: `Number of vowels: 5`
   ```

5. **Formatted Bill**  
   Ask item name, quantity, price. Print neat bill with total.

   ```markdown
   Example: Input `Apple`, `5`, `50` → Output:  
   `Item: Apple`  
   `Quantity: 5`  
   `Total: Rs.250`
   ```

---

### Level 3: Making Decisions - Conditionals

**Why this level?**  
Learn how to make your program choose different actions using if/elif/else.

1. **Even or Odd**  
   Ask a number. Print Even or Odd.
   
   ```markdown
   Example: Input `7` → Output: `Odd`
   ```

3. **Compare Two Numbers**  
   Ask two numbers. Print which is bigger or if equal.

   ```markdown
   Example: Input `10` `5` → Output: `10 is greater`
   ```

5. **Pass or Fail**  
   Ask marks. Print Pass (≥40) or Fail.

   ```markdown  
   Example: Input `35` → Output: `Fail`
   ```

7. **Positive, Negative, Zero**  
   Ask a number. Print what it is.

   ```markdown
   Example: Input `-4` → Output: `Negative`
   ```

9. **Grade System**  
   Ask percentage. Print A (≥80), B (60-79), C (40-59), Fail.

   ```markdown
   Example: Input `85` → Output: `A Grade`
   ```

11. **Simple Calculator**  
   Ask two numbers and operation (+ - * /). Print result. Show error for divide by zero.

      ```markdown
      Example: Input `10`, `5`, `/` → Output: `Result: 2.0`
      ```

---

### Level 4: Repeating Tasks - Loops

**Why this level?**  
Learn how to repeat work easily using while and for loops.

1. **Print 1 to 10**  
   Use for loop to print numbers 1 to 10.

2. **Multiplication Table**  
   Ask a number. Print its table (1 to 10).

   ```markdown 
   Example: Input `5` → `5 x 1 = 5` ... `5 x 10 = 50`
   ```

4. **Sum of Numbers**  
   Ask a number n. Print sum from 1 to n.

   ```markdown
   Example: Input `10` → Output: `Sum = 55`
   ```

6. **Even Numbers 1-20**  
   Print all even numbers from 1 to 20 using loop.

7. **Countdown**  
   Print numbers from 10 down to 1 using while loop.

8. **Simple Star Pattern**  
   Print this pattern using loops:
   
   ```markdown
   *                 1
   * *               1 2
   * * *             1 2 3
   * * * *           1 2 3 4
   * * * * *         1 2 3 4 5
   ```

---

### Level 5: Organizing Data - Lists & Tuples

**Why this level?**  
Learn how to store many items in lists (can change) and tuples (cannot change).

1. **Create Fruit List**  
   Ask user for 5 fruits. Store in list and print.

2. **Access List Items**  
   Make list [10,20,30,40,50]. Print first, middle, last.

3. **Add and Insert Items**  
   Start empty list. Append 3 items. Insert one at position 1. Print final list.

4. **List Slicing**  
   Make list 1 to 10. Print first 5, last 3, and items 3 to 8.

5. **Introduction to Tuples**  
   Make tuple of 5 days. Print it and try to change one item (will give error).

6. **Convert List to Tuple**  
   Ask 4 subjects → store in list → convert to tuple → print both.

---

### Level 6: Advanced Collections - Sets & Dictionaries

**Why this level?**  
Learn sets (unique items) and dictionaries (key-value pairs).

1. **Create and Add to Set**  
   Make empty set. Add 5 numbers. Print set (duplicates removed).

2. **Set Operations**  
   Make two sets. Print union and intersection.

3. **Remove from Set**  
   Make set with 6 items. Remove one and discard one (if not exist). Print after each.

4. **Student Marks Dictionary**  
   Make dict with 3 student names and marks. Print all.

5. **Add and Update Dict**  
   Start empty dict. Add 3 key-value pairs. Update one value.

6. **Word Frequency**  
   Ask a sentence. Make dict to count how many times each word appears.

---

## 07 – Practice Questions Set (Functions)

Q1. Write a function named `greet()` that prints:  
`Welcome to Python Programming`

Q2. Write a function named `show_name(name)` that takes a **name as a parameter** and prints:  
`Hello <name>`

Q3. Write a function named `add_numbers(a, b)` that takes **two numbers** and prints their **sum**.

Q4. Write a function named `student_info(name, age)` that prints the student’s **name and age** in one sentence.

Q5. Write a function named `calculate_bill(price, quantity)` that takes **price and quantity** and prints the total bill.

Q6. Write a function named `is_even(number)` that returns whether the number is **even or odd**.

Q7. Write a function named `get_full_name(first_name, last_name)` that returns the **full name** using string concatenation.

Q8. Write a function named `find_max(a, b)` that returns the **greater number**.

Q9. Write a function named `count_items(items)` that takes a **list** and returns the **total number of items**.

Q10. Write a function named `show_menu()` that prints a simple **food menu** and calls the function when the program runs.

Q11. Write a function named `calculate_discount(price)` that:
- Takes the product price as a parameter
- Applies a **10% discount**
- Prints the final price after discount

Q12. Write a function named `login_message(username)` that:
- Takes a username as a parameter
- Prints a welcome message for that user

---

## PF (Programming Fundamentals) Mega Practice Tasks


### Phase 1: Basics & Input/Output
Q1. Create variables to store **shop name** and **shop city** and print them in one line.

Q2. Take user input for **customer name** and print a welcome message.

Q3. Create variables for **item name** and **item price**, then print them.

---

### Phase 2: Strings & Concatenation
Q4. Concatenate customer name and item name to print:  
`<customer> is buying <item>`

Q5. Take input for **quantity** and print a sentence using concatenation showing quantity and item name.

---

### Phase 3: Conditions (if / elif / else)
Q6. If quantity is greater than 5, print `Bulk order`, otherwise print `Regular order`.

Q7. If item price is greater than 1000, print `Expensive item`, else print `Affordable item`.

Q8. Take input for **payment method** (`cash`, `card`, `online`) and print a confirmation message based on input.

---

### Phase 4: Loops
Q9. Use a loop to print item name **quantity number of times**.

Q10. Use a loop to print numbers from 1 to quantity.

Q11. Use a loop to calculate **total price** by adding item price quantity times.

---

### Phase 5: List
Q12. Create a list named `cart` and add **three item names** to it.

Q13. Print all items in the cart using a loop.

Q14. Ask the user to enter an item name and check if it exists in the cart.

---

### Phase 6: Tuple
Q15. Create a tuple of **available payment methods** and print them.

Q16. Check whether the user’s selected payment method exists in the tuple.

---

### Phase 7: Set
Q17. Create a set from the cart list to remove duplicate items and print unique items.

---

### Phase 8: Dictionary
Q18. Create a dictionary where:
- keys = item names
- values = item prices  
Print the dictionary.

Q19. Use a loop to calculate the **total bill** from the dictionary.

---

### Phase 9: Functions (Final Integration)
Q20. Create a function named `generate_bill()` that:
- Takes customer name, cart dictionary, and payment method
- Prints customer name
- Prints all items with prices
- Prints total bill
- Prints payment confirmation message

# **PF Projects**

### 1. Simple Calculator
**Concepts:** Variables, input/output, operators
**Description:**
Create a console-based calculator that performs addition, subtraction, multiplication, and division based on user choice.
**Skills Practiced:**
- `input()` / `print()`
- Arithmetic operators
- Basic control flow

---

### 2. Number Guessing Game
**Concepts:** Conditional statements, loops
**Description:**
The program generates a random number, and the user guesses until correct. Provide hints (higher/lower).
**Skills Practiced:**
- `if / elif / else`
- `while` loop
- `random` module

---

### 3. Student Grade System
**Concepts:** Conditions, logical operators
**Description:**
Take marks as input and calculate grade (A, B, C, Fail) based on predefined rules.
**Skills Practiced:**
- Conditional logic
- Comparison operators
- Input validation

---

### . Multiplication Table Generator
**Concepts:** Loops
**Description:**
Generate a multiplication table for a given number up to a specified range.
**Skills Practiced:**
- `for` loop
- Formatting output
- Iteration logic

---

### 5. To-Do List (Console Based)
**Concepts:** Lists, loops
**Description:**
Allow users to add, view, and remove tasks from a to-do list using a menu-driven program.
**Skills Practiced:**
- Lists
- Menu-based programs
- Loop control

---

### 6. Password Validator
**Concepts:** Strings, conditions
**Description:**
Check whether a password meets criteria (length, digits, uppercase, special character).
**Skills Practiced:**
- String methods
- Logical conditions
- Validation rules

---

### 7. ATM Simulation System
**Concepts:** Functions, conditionals
**Description:**
Simulate ATM operations: check balance, deposit, withdraw, and exit.
**Skills Practiced:**
- Functions
- State management
- Conditional branching

---

### 8. Contact Management System
**Concepts:** Dictionary, functions
**Description:**
Store contacts with name and phone number. Support add, search, update, and delete operations.
**Skills Practiced:**
- Dictionaries
- CRUD operations
- Function modularity

---

### 9. Quiz Application

**Concepts:** Lists, dictionaries, loops
**Description:**
Create a quiz with multiple questions, track score, and show final results.
**Skills Practiced:**
- Nested data structures
- Looping over data
- Scoring logic

---

### 10. Mini Banking System
**Concepts:** Functions, data structures, logic flow
**Description:**
Develop a small banking system with user accounts, login, balance tracking, and transaction history.
**Skills Practiced:**
- Functions + dictionaries
- Program flow control
- Real-world problem modeling

---
