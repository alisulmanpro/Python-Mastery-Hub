## Variable

A **variable** in Python is a name used to store data in memory, and its value can change during program execution.

**For Example**

```python
x = 10
name = "Ali"
print(x, name)
```

### Practice Questions

1. Write a program to store your name in a variable and print it.
2. Write a program to store your age in a variable and display it.
3. Write a program to store two numbers in variables and print their sum.
4. Write a program to store two numbers and print their difference.
5. Write a program to store two numbers and print their product.
6. Write a program to store two numbers and print their division.
7. Write a program to take a number from the user, store it in a variable, and print it.
8. Write a program to store a floating-point number in a variable and print it.
9. Write a program to swap values of two variables.
10. Write a program to store length and width in variables and calculate the area of a rectangle.
11. Write a program to store marks of three subjects in variables and calculate total marks.
12. Write a program to store total marks and obtained marks in variables and calculate percentage.
13. Write a program to store temperature in Celsius in a variable and convert it to Fahrenheit.
14. Write a program to store a number in a variable and check whether it is positive or negative.
15. Write a program to store two numbers in variables and check which one is greater.



## Data Types

**Data types** in Python define the type of data a variable can store, such as numbers, text, or true/false values.

**For Example**

```python
age = int(input("Enter age: "))
price = float(input("Enter price: "))
name = input("Enter name: ")
is_student = bool(input("Enter status: "))
print(age, price, name, is_student)
```

## Practice Questions

1. Write a program to take an integer input and print its type.
2. Write a program to take a float input and display it.
3. Write a program to take a string input and print it.
4. Write a program to take two integers and print their sum.
5. Write a program to take two float numbers and print their product.
6. Write a program to take an integer and convert it into float.
7. Write a program to take a float and convert it into integer.
8. Write a program to take age as input and check whether its data type is integer.
9. Write a program to take a number as string and convert it into integer.
10. Write a program to take name and age as input and print them in one line.
11. Write a program to take marks of three subjects and calculate total and average.
12. Write a program to take price and quantity and calculate total bill.
13. Write a program to take a number and check whether it is even or odd.
14. Write a program to take temperature in Celsius and convert it to Fahrenheit.
15. Write a program to take two numbers and check which one is greater.



## Operators

**Operators** in Python are symbols used to perform operations on variables and values, such as addition, comparison, and logical decisions.

**For Example**

```python
a = int(input("Enter a: "))
b = int(input("Enter b: "))
result = a + b
print(result)
```

### Practice Questions

1. Write a program to add two numbers.
2. Write a program to subtract one number from another.
3. Write a program to multiply two numbers.
4. Write a program to divide two numbers.
5. Write a program to find the remainder of two numbers using modulus operator.
6. Write a program to check whether two numbers are equal or not.
7. Write a program to check which number is greater between two numbers.
8. Write a program to check whether a number is greater than 10 or not.
9. Write a program to calculate the square of a number.
10. Write a program to calculate power of a number.
11. Write a program to check whether a number is positive or negative.
12. Write a program to check whether a number is even or odd (take value from user).
13. Write a program to compare three numbers and find the largest one.
14. Write a program to check whether a number lies between 1 and 100 (take value from user).
15. Write a program to calculate total marks, percentage, and check pass or fail using operators.

## Decision Making (`if`, `else`, `elif`)

**Decision making** in Python allows the program to choose between different actions using conditions. `if` checks a condition, `elif` checks another condition if the first is false, and `else` runs when all conditions are false.

**For Example**

```python
marks = int(input("Enter marks: "))
if marks >= 80:
    print("Grade A")
elif marks >= 60:
    print("Grade B")
else:
    print("Fail")
```

### Practice Questions

1. Write a program to check if a number is positive, negative, or zero.
2. Write a program to check if a student has passed or failed (pass >= 40).
3. Write a program to check if a number is even or odd.
4. Write a program to check if a person is eligible to vote (age >= 18).
5. Write a program to find the largest of two numbers.
6. Write a program to find the largest of three numbers.
7. Write a program to check if a number is divisible by 5.
8. Write a program to check if a year is a leap year (take value from user).
9. Write a program to assign grades A, B, C, or F based on marks.
10. Write a program to check if a number is within the range 1–100.
11. Write a program to check if a character is a vowel or consonant (take value from user).
12. Write a program to check if a person is a minor, adult, or senior citizen based on age.
13. Write a program to check eligibility for driving and voting based on age.
14. Write a program to check if a number is divisible by both 3 and 5 (take value from user).
15. Write a program to calculate total marks, percentage, and assign grade using `if`, `elif`, `else`.

## Loops

**Loops** in Python are used to repeat a block of code multiple times. `for` loop is used when the number of repetitions is known, and `while` loop is used when a condition needs to be true to continue.

**For Example**

```python
for i in range(1, 6):
    print(i)
```

### Practice Questions

1. Write a program to print numbers from 1 to 10.
2. Write a program to print even numbers between 1 and 20.
3. Write a program to print odd numbers between 1 and 20.
4. Write a program to calculate the sum of first 10 natural numbers.
5. Write a program to calculate the factorial of a number (take value from user).
6. Write a program to print multiplication table of a number (take value from user).
7. Write a program to print numbers from 10 to 1 in reverse.
8. Write a program to calculate the sum of all even numbers between 1 and 50.
9. Write a program to print all numbers divisible by 3 between 1 and 30.
10. Write a program to count the number of digits in a number (take value from user).
11. Write a program to print a pattern of stars:
    ```cmd
    *
    **
    ***
    ****
    ```

12. Write a program to calculate the sum of digits of a number (take value from user).
13. Write a program to find the largest number in a list of 5 numbers (take values from user).
14. Write a program to print Fibonacci series up to n terms (take value from user).
15. Write a program to reverse a number using a loop (take value from user).

## Strings

A **string** in Python is a sequence of characters enclosed in quotes, used to store text data. Strings can be manipulated with indexing, slicing, and built-in functions.

**For Example**

```python
name = input("Enter your name: ")
print("Hello " + name)
print("First character:", name[0])
```

### Practice Questions

1. Write a program to take a string and print it.
2. Write a program to find the length of a string.
3. Write a program to print the first and last character of a string (take value from user).
4. Write a program to convert a string to uppercase.
5. Write a program to convert a string to lowercase.
6. Write a program to count the number of vowels in a string (take value from user).
7. Write a program to reverse a string.
8. Write a program to print a substring of a string (take value from user).
9. Write a program to check if a word exists in a string (take value from user).
10. Write a program to replace a word in a string with another word (take value from user).
11. Write a program to remove spaces from a string.
12. Write a program to print each character of a string in a new line.
13. Write a program to concatenate two strings (take values from user).
14. Write a program to check if a string starts with a specific letter (take value from user).
15. Write a program to count how many times a character appears in a string (take value from user).

## Lists

A **list** in Python is a collection of items enclosed in square brackets `[]`. Lists can store multiple values of different data types and can be changed (mutable).

**For Example**

```python
numbers = [int(input("Enter first number: ")), int(input("Enter second number: "))]
print("List:", numbers)
numbers.append(int(input("Add another number: ")))
print("Updated List:", numbers)
```

### Practice Questions

1. Write a program to create a list of 5 numbers and print it.
2. Write a program to find the length of a list.
3. Write a program to print the first and last element of a list (take values from user).
4. Write a program to append a new element to a list (take value from user).
5. Write a program to insert an element at a specific position in a list (take value from user).
6. Write a program to remove an element from a list (take value from user).
7. Write a program to find the sum of all elements in a list.
8. Write a program to find the largest number in a list (take values from user).
9. Write a program to find the smallest number in a list (take values from user).
10. Write a program to sort a list in ascending order.
11. Write a program to reverse a list.
12. Write a program to count how many times a number appears in a list (take values from user).
13. Write a program to create a list of strings and print each string in a new line.
14. Write a program to combine two lists into one (take values from user).
15. Write a program to remove duplicate elements from a list.

## Tuples 

A **tuple** in Python is a collection of items enclosed in parentheses `()`. Tuples are **immutable**, which means their values cannot be changed after creation.

**For Example**

```python
my_tuple = (input("Enter first item: "), input("Enter second item: "))
print("Tuple:", my_tuple)
print("First item:", my_tuple[0])
```

### Practice Questions

1. Write a program to create a tuple of 4 items and print it.
2. Write a program to find the length of a tuple.
3. Write a program to print the first and last element of a tuple (take values from user).
4. Write a program to access a specific element of a tuple.
5. Write a program to concatenate two tuples (take values from user).
6. Write a program to check if an item exists in a tuple (take value from user).
7. Write a program to find the maximum value in a tuple of numbers.
8. Write a program to find the minimum value in a tuple of numbers.
9. Write a program to count how many times an element appears in a tuple (take value from user).
10. Write a program to convert a tuple into a list.
11. Write a program to convert a list into a tuple (take values from user).
12. Write a program to print all elements of a tuple using a loop.
13. Write a program to slice a tuple (take values from user).
14. Write a program to combine three tuples into one.
15. Write a program to find the index of a specific element in a tuple (take value from user).

## Sets

A **set** in Python is a collection of **unique items** enclosed in curly braces `{}`. Sets are **unordered** and **mutable**, which means you can add or remove items, but duplicates are not allowed.

**For Example**

```python
my_set = {int(input("Enter first number: ")), int(input("Enter second number: "))}
print("Set:", my_set)
my_set.add(int(input("Add another number: ")))
print("Updated Set:", my_set)
```

### Practice Questions

1. Write a program to create a set of 4 numbers and print it.
2. Write a program to add a new element to a set (take value from user).
3. Write a program to remove an element from a set (take value from user).
4. Write a program to find the length of a set.
5. Write a program to check if an element exists in a set (take value from user).
6. Write a program to combine two sets into one (take values from user).
7. Write a program to find the union of two sets.
8. Write a program to find the intersection of two sets.
9. Write a program to find the difference between two sets.
10. Write a program to clear all elements from a set.
11. Write a program to convert a list into a set (take values from user).
12. Write a program to convert a tuple into a set (take values from user).
13. Write a program to print all elements of a set using a loop.
14. Write a program to find the largest number in a set of numbers.
15. Write a program to remove duplicate values from a list using a set.

## Dictionary

A **dictionary** in Python is a collection of **key–value pairs** enclosed in curly braces `{}`. Each key is unique, and values can be of any data type. Dictionaries are **mutable**, so values can be changed after creation.

**For Example**

```python
student = {
    "name": input("Enter name: "), 
    "age": int(input("Enter age: "))
}
print("Student Dictionary:", student)
print("Name:", student["name"])
```

### Practice Questions

1. Write a program to create a dictionary with 3 key-value pairs and print it.
2. Write a program to add a new key-value pair to a dictionary (take value from user).
3. Write a program to remove a key-value pair from a dictionary (take key from user).
4. Write a program to find the number of items in a dictionary.
5. Write a program to check if a key exists in a dictionary (take key from user).
6. Write a program to update the value of an existing key (take key and value from user).
7. Write a program to print all keys of a dictionary.
8. Write a program to print all values of a dictionary.
9. Write a program to print all key-value pairs using a loop.
10. Write a program to merge two dictionaries (take values from user).
11. Write a program to get the value of a key safely (take key from user).
12. Write a program to clear all items in a dictionary.
13. Write a program to convert two lists into a dictionary (take values from user).
14. Write a program to find the maximum value in a dictionary of numbers.
15. Write a program to find the key with the minimum value in a dictionary of numbers.


## Functions

A **function** in Python is a block of reusable code that performs a specific task. Functions help to organize code, avoid repetition, and can accept inputs (parameters) and return outputs.

**For Example**

```python
def add_numbers(a, b):
    return a + b

num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
print("Sum:", add_numbers(num1, num2))
```

### Practice Questions

1. Write a function to print “Hello, World!”.
2. Write a function to take a number as input and print it.
3. Write a function to add two numbers and return the result.
4. Write a function to calculate the square of a number (take value from user).
5. Write a function to find the largest of two numbers.
6. Write a function to find the largest of three numbers (take values from user).
7. Write a function to check if a number is even or odd (take value from user).
8. Write a function to calculate factorial of a number.
9. Write a function to print multiplication table of a number (take value from user).
10. Write a function to calculate the sum of elements in a list (take values from user).
11. Write a function to reverse a string.
12. Write a function to count vowels in a string (take value from user).
13. Write a function to check if a number is prime (take value from user).
14. Write a function to convert Celsius to Fahrenheit (take value from user).
15. Write a function to check if a given year is a leap year (take value from user).

## Lambda Functions | Python

A **lambda function** in Python is a small anonymous function defined using the `lambda` keyword. It can have any number of arguments but only **one expression**, which is returned automatically.

**For Example**

```python
square = lambda x: x**2
num = int(input("Enter a number: "))
print("Square:", square(num))
```

### Practice Questions

1. Write a lambda function to add two numbers.
2. Write a lambda function to multiply two numbers (take values from user).
3. Write a lambda function to find the square of a number.
4. Write a lambda function to find the cube of a number (take value from user).
5. Write a lambda function to find the largest of two numbers.
6. Write a lambda function to check if a number is even.
7. Write a lambda function to calculate the sum of three numbers (take values from user).
8. Write a lambda function to return the absolute value of a number.
9. Write a lambda function to add 10 to a number (take value from user).
10. Write a lambda function to divide two numbers (take values from user).
11. Write a lambda function to find the remainder of two numbers.
12. Write a lambda function to check if a number is positive or negative (take value from user).
13. Write a lambda function to calculate the area of a square.
14. Write a lambda function to multiply a number by 5 (take value from user).
15. Write a lambda function to check if a number is greater than 100 (take value from user).

