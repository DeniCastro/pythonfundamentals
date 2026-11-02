# 🟢 Python Fundamentals: Exercises

**Total Exercises:** 18 (3 per module: Simple, Medium, Hard)  
**Allowed Tools:** `print`, `input`, variables, operators, conditionals, loops, strings, lists, dictionaries, tuples, functions, and (`Module 6` only) `import random` / `import math`.

---

## Module 1: Variables, Types & I/O

### M1-E1 (Simple): Variables & f-Strings
Create a program that defines two integer variables, calculates their sum, and prints the result using an f-string with a custom message.

**Example Output (with 10 and 25):**
```text
The sum of 10 and 25 is 35.
```

---

### M1-E2 (Medium): Temperature Converter
Create a program that asks the user for a temperature in Celsius, converts it to Fahrenheit using the formula $F = (C \times 9 / 5) + 32$, and prints the result using an f-string. Round the result to 1 decimal place.

**Example Output (input `25`):**
```text
25.0°C is equal to 77.0°F.
```

---

### M1-E3 (Hard): Bill Splitter
Create a program that asks the user for three values: the bill total (decimal), the tip percentage (whole number), and the number of people. Calculate the tip, the final total, and how much each person pays. Print all three results, rounded to 2 decimal places.

**Example Output (inputs `120`, `10`, `4`):**
```text
Tip: 12.0
Total with tip: 132.0
Each person pays: 33.0
```

---

## Module 2: Conditionals

### M2-E1 (Simple): Even or Odd
Create a program that asks the user for a whole number and prints whether it is even or odd.

**Example Output (input `7`):**
```text
The number 7 is odd.
```

---

### M2-E2 (Medium): Age Categorization
Create a program that asks the user for their age and prints their category using these ranges:
* `0 to 12`: Child
* `13 to 19`: Teenager
* `20 to 64`: Adult
* `65 or more`: Senior

**Example Output (input `25`):**
```text
Adult
```

---

### M2-E3 (Hard): Leap Year Checker
Create a program that asks the user for a year and prints whether it is a leap year. A year is a leap year if it is divisible by 4, except years divisible by 100, which are not leap years, unless they are also divisible by 400.

*Test your program with 2024 (leap), 1900 (not leap), 2000 (leap), and 2023 (not leap).*

**Example Output (input `1900`):**
```text
1900 is not a leap year.
```

---

## Module 3: Loops

### M3-E1 (Simple): Multiplication Table
Create a program that asks the user for a number and prints its multiplication table from 1 to 10.

**Example Output (input `5`):**
```text
5 x 1 = 5
5 x 2 = 10
...
5 x 10 = 50
```

---

### M3-E2 (Medium): Sum of Numbers
Create a program that uses a loop to add all the numbers from 1 to 50 (including both) and prints the final total. Do not use a mathematical formula; the loop must perform the cumulative addition.

**Example Output:**
```text
The sum of numbers from 1 to 50 is 1275.
```

---

### M3-E3 (Hard): Even Numbers Counter
Create a program that goes through every number from 1 to 100 (including both). It must count how many of them are even and add those even numbers together. Print both results at the end.

**Example Output:**
```text
Even numbers found: 50
Sum of even numbers: 2550
```

---

## Module 4: Strings & Lists

### M4-E1 (Simple): String Methods and Length
Create a program that stores the name `"Ada Lovelace"` in a variable and prints it in uppercase, in lowercase, its total number of characters (spaces count), and its first and last character.

**Example Output:**
```text
Uppercase: ADA LOVELACE
Lowercase: ada lovelace
Total characters: 12
First character: A
Last character: e
```

---

### M4-E2 (Medium): List Statistics
Create a program with the list `[14, 3, 27, 9, 21]`. Using a loop (do not use `max()`, `min()`, or `sum()`), find and print the largest number, the smallest number, and the average.

**Example Output:**
```text
Largest: 27
Smallest: 3
Average: 14.8
```

---

### M4-E3 (Hard): Palindrome and Vowel Counter
Create a program that asks the user for a word. It must print whether the word is a palindrome (reads the same forwards and backwards, ignoring case) and how many vowels (`a`, `e`, `i`, `o`, `u`) it contains.

**Example Output (input `Level`):**
```text
"Level" is a palindrome.
Vowels: 2
```

---

## Module 5: Dictionaries & Tuples

### M5-E1 (Simple): Person Dictionary
Create a dictionary with a person's name, age, and country. Print each value using an f-string. Then change the age to a new value, add a new key called `city`, and print the complete dictionary.

**Example Output:**
```text
Name: Ana
Age: 30
Country: Brazil
{'name': 'Ana', 'age': 31, 'country': 'Brazil', 'city': 'Manaus'}
```

---

### M5-E2 (Medium): Inventory Lookup
Create a dictionary with at least four products as keys and their stock quantities as values (for example, `"apple": 10`). Ask the user for a product name. If the product exists, print its stock. If it does not, print a message indicating it is not in the inventory.

**Example Output (input `apple`, then input `grape`):**
```text
apple: 10 units in stock.
grape is not in the inventory.
```

---

### M5-E3 (Hard): Gradebook
Create a dictionary where each key is a student's name and each value is a list of three grades. Loop through the dictionary and print each student's average (rounded to 1 decimal place). At the end, print the name of the student with the highest average.

**Example Output:**
```text
Ana: 8.7
Bruno: 7.0
Carla: 9.3
Top student: Carla
```

---

## Module 6: Functions + First Look at `import`

### M6-E1 (Simple): Simple Function
Create a function named `calculate_area` that takes two parameters (`length` and `width`). The function should calculate the area of a rectangle and return the result. Call the function and print the returned value using an f-string.

**Example Output (with `5` and `10`):**
```text
The area of the rectangle is 50.
```

---

### M6-E2 (Medium): Prime Number Function
Create a function named `is_prime` that takes one whole number and returns `True` if it is a prime number and `False` if it is not. *(A prime number is greater than 1 and divisible only by 1 and itself.)* Then use a loop to call the function for every number from 1 to 20 and print only the prime ones.

**Example Output:**
```text
Prime numbers from 1 to 20: 2 3 5 7 11 13 17 19
```

---

### M6-E3 (Hard): Dice Game
Import the `random` module and create a function named `play_round` that simulates one round of a dice game. The function rolls one die for the player and one for the computer using `random.randint(1, 6)`, and returns a text result: `"Player wins"`, `"Computer wins"`, or `"Tie"`. Call the function three times in a loop and print the dice values along with the result of each round.

**Example Output (results will vary due to randomness):**
```text
Round 1: Player 4, Computer 2 -> Player wins
Round 2: Player 3, Computer 3 -> Tie
Round 3: Player 1, Computer 6 -> Computer wins
```

> **Tip for the course author:** Since `play_round` produces dice values dynamically, ensure the function either prints the values internally or returns them alongside the text result (e.g., as a tuple) so they can be formatted cleanly in the output loop.