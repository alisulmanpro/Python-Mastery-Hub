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

## Practice Set 03: Conditionals (if/elif/else)

1. **Check Even or Odd**  
   Ask the user to enter a number. Print whether it is **even** or **odd**.  


   ```markdown
   Example:  
   Input: `4` → Output: `Even`  
   Input: `7` → Output: `Odd`
   ```

1. **Compare Two Numbers**  
   Ask the user to enter two numbers. Print which one is greater (or if they are equal).  


   ```markdown
   Example:  
   Input: `10` and `5` → Output: `10 is greater`  
   Input: `8` and `8` → Output: `Both are equal`
   ```

2. **Determine Age Category**  
   Ask the user for their age. Print:  
   - `Child` if age < 13  
   - `Teenager` if age is 13–19  
   - `Adult` otherwise  

   
   ```markdown
   Example:  
   Input: `10` → Output: `Child`  
   Input: `16` → Output: `Teenager`  
   Input: `25` → Output: `Adult`
   ```
   
3. **Pass or Fail**  
   Ask the user for their marks (out of 100). Print `Pass` if marks ≥ 40, otherwise `Fail`.  

   
   ```markdown
   Example:  
   Input: `55` → Output: `Pass`  
   Input: `35` → Output: `Fail`
   ```

4. **Positive, Negative, or Zero**  
   Ask the user to enter a number. Print whether it is **positive**, **negative**, or **zero**.  

   
   ```markdown
   Example:  
   Input: `8` → Output: `Positive`  
   Input: `-3` → Output: `Negative`  
   Input: `0` → Output: `Zero`
   ```

5. **Divisible by 3**  
   Ask the user to enter a number. Check and print if it is divisible by 3 or not.  

   
   ```markdown
   Example:  
   Input: `9` → Output: `Divisible by 3`  
   Input: `10` → Output: `Not divisible by 3`
   ```

6. **Assign Grade Based on Percentage**  
   Ask the user for their percentage (0–100). Print the grade:  
   - `A Grade` if ≥ 80  
   - `B Grade` if 60–79  
   - `C Grade` if 40–59  
   - `Fail` otherwise  

   
   ```markdown
   Example:  
   Input: `85` → Output: `A Grade`  
   Input: `45` → Output: `C Grade`
   ```

7. **Day of the Week Message**  
   Ask the user to enter a day of the week (e.g., "Monday"). Print a custom message:  
   - Monday → `Start of the week!`  
   - Friday → `Weekend is near!`  
   - Saturday or Sunday → `Enjoy your weekend!`  
   - Any other → `Keep going!`
     
   
   ```markdown
   Example:  
   Input: `Friday` → Output: `Weekend is near!`  
   Input: `Sunday` → Output: `Enjoy your weekend!`
   ```

8. **Simple Calculator**  
   Create a basic calculator:  
   - Ask for two numbers.  
   - Ask for an operation (`+`, `-`, `*`, `/`).  
   - Use if/elif/else to perform the operation and print the result.  
   - Handle division by zero with a message like `Cannot divide by zero!`.
       
   
   ```markdown
   Example:  
   Inputs: `10`, `5`, `+` → Output: `Result: 15`  
   Inputs: `20`, `4`, `/` → Output: `Result: 5.0`  
   Inputs: `8`, `0`, `/` → Output: `Cannot divide by zero!`
   ```

## 04 – Practice Questions Set (Loops: while & for)

Q1. Write a program using a `while loop` to print numbers from 1 to 10.

Q2. Write a program using a `for loop` to print numbers from 1 to 10.

Q3. Write a program using a loop to print **even numbers from 1 to 20**.

Q4. Write a program using a loop to print the **table of 5** e.g. `5 x 1 = 5`.

Q5. Write a program using a loop to print the **sum of numbers from 1 to 10**.

Q6. Write a program that takes a number from the user and prints numbers from **1 to that number**.

Q7. Write a program that prints numbers from **10 to 1** using a loop.

Q9. Write a program to print given blow outputs using a loop:
``` cmd
1)                2)                3)              4)                  05)
*                 * * * * *             *           1                   * * * * *
* *               * * * *              * *          1 2                 *       *
* * *             * * *               * * *         1 2 3               *       *
* * * *           * *                * * * *        1 2 3 4             *       *
* * * * *         *                 * * * * *       1 2 3 4 5           * * * * *
```

### Practice Set 05: Lists & Tuples

1. **Create and Print a List**  
   Ask the user to enter 5 favorite fruits (one by one). Store them in a list and print the complete list.  

   ```markdown
   Example:  
   Inputs: `Apple`, `Banana`, `Orange`, `Mango`, `Grape` → Output: `['Apple', 'Banana', 'Orange', 'Mango', 'Grape']`
   ```

1. **Access List Elements**  
   Create a list of 5 numbers. Print the first, last, and middle element using indexing.  
   
   ```markdown
   Example:  
   List: `[10, 20, 30, 40, 50]` → Output:  
   `First: 10`  
   `Middle: 30`  
   `Last: 50`
   ```

2. **List Slicing**  
   Create a list of numbers from 1 to 10. Print:  
   - First 5 elements  
   - Last 3 elements  
   - Elements from index 2 to 7  
   
   ```markdown
   Example Output:  
   `First 5: [1, 2, 3, 4, 5]`  
   `Last 3: [8, 9, 10]`  
   `Index 2 to 7: [3, 4, 5, 6, 7, 8]`
   ```

3. **Modify List with Append and Insert**  
   Start with an empty list. Ask the user for 3 items to add using `append()`. Then insert a new item at index 1 using `insert()`. Print the final list.  
   
   ```markdown
   Example:  
   Inputs: `Book`, `Pen`, `Notebook` → Insert `Pencil` at index 1 → Output: `['Book', 'Pencil', 'Pen', 'Notebook']`
   ```

4. **Remove Elements**  
   Create a list: `['Apple', 'Banana', 'Cherry', 'Banana']`. Remove the first 'Banana' using `remove()`, then remove the last element using `pop()`. Print the list after each operation.  
   
   ```markdown
   Example Output:  
   `After remove: ['Apple', 'Cherry', 'Banana']`  
   `After pop: ['Apple', 'Cherry']`
   ```

5. **List Operations**  
   Ask the user for 5 numbers (one by one). Store in a list. Print:  
   - Length of the list  
   - Sum of all numbers  
   - Maximum and minimum values  
   
   ```markdown
   Example:  
   Inputs: `10, 20, 30, 40, 50` → Output:  
   `Length: 5`  
   `Sum: 150`  
   `Max: 50`  
   `Min: 10`
   ```

6. **Introduction to Tuples**  
   Create a tuple of 5 days of the week. Print the tuple, its length, and access the 3rd day. Try to change one element (it should show an error — mention this in comments).  
   
   ```markdown
   Example:  
   Tuple: `('Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday')` → Output:  
   `Tuple: ('Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday')`  
   `Length: 5`  
   `3rd Day: Wednesday`
   ```

7. **Tuple Unpacking**  
   Create a tuple with name, age, and city. Unpack it into three variables and print a message: `Name: [name], Age: [age], City: [city]`.  
   
   ```markdown
   Example:  
   Tuple: `('Ali', 20, 'Islamabad')` → Output: `Name: Ali, Age: 20, City: Islamabad`
   ```

8. **Convert Between List and Tuple**  
   Ask the user for 4 subjects. Store as a list. Convert to a tuple and print both. Then convert back to a list, add one more subject, and print the updated list.  
   
   ```markdown
   Example:  
   Inputs: `Math`, `Physics`, `Chemistry`, `English` → Add `Computer` → Output:  
   `Original List: ['Math', 'Physics', 'Chemistry', 'English']`  
   `As Tuple: ('Math', 'Physics', 'Chemistry', 'English')`  
   `Updated List: ['Math', 'Physics', 'Chemistry', 'English', 'Computer']`
   ```

## 06 – Practice Questions Set (Set & Dictionary)

Q1. Create a set of **your favorite fruits** and print it. Add `"mango"` to the set and print again.

Q2. Create a set of **numbers from 1 to 5** and another set of **numbers from 4 to 8**. Print the **common numbers** using set operations.

Q3. Create a dictionary for a **student** with keys: `name`, `age`, `grade`. Print the dictionary.

Q4. Update the student dictionary to add a new key `city` and print the updated dictionary.

Q5. Write a program where the user can input a **fruit name**. If the fruit exists in your dictionary of fruits and their prices, print its price; otherwise print `"Not available"`.

Q6. Create a set of **your favorite movies**. Remove one movie using `discard()` and print the set.

Q7. Create two dictionaries: `dict1 = {'a': 1, 'b': 2}` and `dict2 = {'b': 3, 'c': 4}`. Merge them and print the result.

Q8. Write a program to **find unique words** in a sentence entered by the user using a set.

Q9. Create a dictionary with **subject names as keys** and **marks as values**. Print all subjects where marks are above 50.

Q10. Write a program to **count how many times each word appears** in a sentence using a dictionary.

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
