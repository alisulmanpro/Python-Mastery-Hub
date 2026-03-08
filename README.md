# Programming Fundamentals | Python

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
![Status](https://img.shields.io/badge/status-Ready--to--Learn-darkblue)

This is a simple step-by-step Python learning hub for complete beginners. You start from zero and slowly become good at coding. We have 7 levels. Each level teaches one important topic with easy practice questions. Practice is the only way to learn coding well – do every question yourself. After the levels, try the 20 fun console projects to use everything you learned.

---

![Image](https://github.com/user-attachments/assets/78a742f8-9334-4f86-b25d-98d0ca2242d8)

---

## Table of Contents
- [Set 1: Variables & Input/Output](#set-1-variables--inputoutput)
- [Set 2: Strings](#set-2-strings)
- [Set 3: If/Elif/Else - Conditionals](#set-3-ifelifelse---conditionals)
- [Set 4: Loops](#set-4-loops)
- [Set 5: Lists & Tuples](#set-5-lists--tuples)
- [Set 6: Sets & Dictionaries](#set-6-sets--dictionaries)
- [Set 7: Functions](#set-7-functions)
- [Projects](#projects)

---

### Set 1: Variables & Input/Output

**Purpose**  
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

### Set 2: Strings

**Purpose**  
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

4. **Formatted Bill**  
   Ask item name, quantity, price. Print neat bill with total.

   ```markdown
   Example: Input `Apple`, `5`, `50` → Output:  
   `Item: Apple`  
   `Quantity: 5`  
   `Total: Rs.250`
   ```

---

### Set 3: If/Elif/Else - Conditionals

**Purpose**  
Learn how to make your program choose different actions using if/elif/else.

1. **Even or Odd**  
   Ask a number. Print Even or Odd.
   
   ```markdown
   Example: Input `7` → Output: `Odd`
   ```

2. **Compare Two Numbers**  
   Ask two numbers. Print which is bigger or if equal.

   ```markdown
   Example: Input `10` `5` → Output: `10 is greater`
   ```
   

3. **Pass or Fail**  
   Ask marks. Print Pass (≥40) or Fail.

   ```markdown  
   Example: Input `35` → Output: `Fail`
   ```
4. **Count Vowels**  
   Ask for a word. Count vowels (a,e,i,o,u – ignore case).

   ```markdown
   Example: Input `education` → Output: `Number of vowels: 5`
   ```
   
5. **Positive, Negative, Zero**  
   Ask a number. Print what it is.

   ```markdown
   Example: Input `-4` → Output: `Negative`
   ```

6. **Grade System**  
   Ask percentage. Print A (≥80), B (60-79), C (40-59), Fail.

   ```markdown
   Example: Input `85` → Output: `A Grade`
   ```

7. **Simple Calculator**  
   Ask two numbers and operation (+ - * /). Print result. Show error for divide by zero.

      ```markdown
      Example: Input `10`, `5`, `/` → Output: `Result: 2.0`
      ```

---

### Set 4: Loops

**Purpose**  
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

### Set 5: Lists & Tuples

**Purpose**  
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

### Set 6: Sets & Dictionaries

**Purpose**  
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

### Set 7: Functions

**Why this level?**  
Learn how to make functions so you can use same code again easily.

1. **Add Two Numbers Function**  
   Make function add(a, b) that returns sum. Call it and print.

2. **Check Even/Odd Function**  
   Make function is_even(num) that returns True or False. Use it.

3. **Maximum of Three**  
   Make function max_of_three(a,b,c) that returns biggest number.

4. **Factorial Function**  
   Make function factorial(n) using loop. Return n!.

5. **Greeting Function**  
   Make function greet(name, age) that prints welcome message.

6. **Area Calculator Function**  
   Make function area(shape, values) that calculates rectangle or triangle area.

---

## Projects

### 1. Number Guessing Game
**Skills:** `variables`, `loops`, `conditionals`, `random`, `input validation`, `functions`.
#### Milestones
- **V1 (starter):** Computer picks 1–100, student guesses, give higher/lower hints, track attempts. <br>
- **V2 (required):** Add input validation, allow multiple rounds, show best score (fewest attempts). <br>
- **Stretch (self-learn):** Add difficulty levels (range changes), timer, and persistent high-score file. <br>
**Starter hint:** `import random` → `secret = random.randint(1,100);` loop until guessed. <br>
**Quick tests:** guess correctly in N attempts; invalid input doesn't crash.

### 2. Simple Calculator (CLI)
**Skills:** `functions`, `exception handling`, `parsing strings`, `loops`.
#### Milestones
- **V1:** Support `+ - * /` for two numbers via input prompts. <br>
- **V2:** Support chaining operations, handle divide-by-zero and bad input. <br>
- **Stretch:** implement expression parsing (e.g., "3 + 4 * 2") or REPL mode. <br>
**Starter hint:** separate `parse_input()`, `compute(a, op, b)` functions. Use try/except. <br>
**Quick tests:** 3/0 handled gracefully; "abc" prompts again.

### 3. **To-Do List with File Save/Load**
**Skills:** `lists`, `file I/O (text or JSON)`, `CRUD operations`, `functions`.
#### Milestones
- **V1:** add/view/remove tasks stored in memory. <br>
- **V2:** save/load tasks to a JSON/text file so tasks survive program restart. <br>
- **Stretch:** search/filter tasks, mark priority, and sort by date added. <br>
**Starter hint:** use json module: write tasks (list of dicts) to disk. <br>
**Quick tests:** add task → saved file contains task; restart program → tasks loaded.

### 4) **Contact Book (CSV or JSON)**
**Skills:** dictionaries, lists, file I/O, simple validation, search.
#### Milestones
- **V1:** basic add/view/search by name (in-memory). <br>
- **V2:** persist using CSV/JSON; update/delete contact. <br>
- **Stretch:** export/import VCF, or search fuzzy matches. <br>
**Starter hint:** store each contact as `{ "name":..., "phone":..., "email":... }` and use list comprehension for search. <br>
**Quick tests:** add → find by name; remove → no longer found; file persists.

### 5) **Mad Libs / Story Generator**
**Skills:** `strings`, `concatenation`, `user input`, `functions`, `lists`.
#### Milestones
- **V1:** ask for a few words and print the story. <br>
- **V2:** support multiple story templates chosen by user. <br>
- **Stretch:** read templates from files, randomize templates, or add grammar checks. <br>
**Starter hint:** use placeholders like {noun} and .format(**answers). <br>
**Quick tests:** given inputs, output contains those words in expected places.

### 6) Dice Rolling Simulator + Probability Estimator
**Skills:** `random`, `loops`, `counters`, `basic plotting (optional)`, `statistics`.
#### Milestones
- **V1:** Simulate rolling N dice and show outcomes counts. <br>
- **V2:** Run many trials, show empirical probabilities and compare to expected. <br>
- **Stretch:** Display histogram (matplotlib optional) and let user choose dice types. <br>
**Starter hint:** Collections.Counter is handy for counts. <br>
**Quick tests:** 6-sided die → approx 1/6 frequency in many trials (students can see convergence).

### 7) Expense Tracker (CLI)
**Skills:** `lists/dicts`, `file I/O (CSV/JSON)`, `aggregation`, `date handling (optional)`.
#### Milestones
- **V1:** Add expense (amount + category) and show total per run. <br>
- **v2:** Persist to CSV, show totals per category and monthly totals. <br>
- **Stretch:** Import bank CSV, filter by date ranges. <br>
**Starter hint:** Represent each record as {"amount":float, "cat":str, "date": "YYYY-MM-DD"}; use csv or json. <br>
**Quick tests:** Add entries → category totals correct.

### 8) CLI Quiz System (question bank JSON)
**Skills:** `JSON`, `loops`, `input validation`, `scoring`, `functions`.
#### Milestones
- **V1:** Ask 5 questions from an in-memory list; compute score. <br>
- **V2:** Load questions from JSON, randomize order, show correct answers at end. <br>
- **Stretch:** Timed questions, multiple users, and persistent user scores. <br>
**Starter hint:** JSON schema: {"q":"...", "options":["a","b"], "answer":0}. <br>
**Quick tests:** Scoring matches expected answers; JSON loads properly.

### 9) FizzBuzz Variants & Pattern Printing (algorithmic thinking)
**Skills:** `loops`, `conditionals`, `modulo arithmetic`, `nested loops for patterns`.
#### Milestones
- **V1:** Classic FizzBuzz (print 1..N with rules). <br>
- **V2:** Extend rules (e.g., multiple keyword mapping), and write unit tests. <br>
- **Stretch:** Generate ASCII shapes (pyramids) and analyze complexity (O(n), O(n^2)). <br>
**Starter hint:** Use modular checks in order (if i % 15 == 0 before %3/%5). <br>
**Quick tests:** Known sequences for first 20 values.

### 10) Word Frequency Counter (file input)
**Skills:** `file I/O`, `string processing`, `dicts`, `sorting`.
#### Milestones
- **V1:** Read a text file and output top-10 words. <br>
- **V2:** Ignore stopwords/punctuation, case-insensitive, show counts. <br>
- **Stretch:** Build concordance or show sentence locations for top words. <br>
**Starter hint:** Normalize text (.lower()), remove punctuation (str.translate) and use Counter. <br>
**Quick tests:** For short sample file, expected top words & counts.

### 11) Simple Bank Account Simulator (state and simple OOP optional)
**Skills:** `functions`, `state management`, `optional classes`, `input validation`.
#### Milestones
- **V1:** Simulate deposit/withdrawal and show balance (functional style). <br>
- **V2:** Add transaction history (list) and persist to JSON. <br>
- **Stretch:** Convert to Account class, support multiple accounts and transfers. <br>
**Starter hint:** Start with procedural approach before introducing class Account: as a stretch. <br>
**Quick tests:** Deposits and withdrawals update balance; cannot withdraw over balance.
