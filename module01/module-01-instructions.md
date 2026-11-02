# Module 1: Variables, Types & I/O: Instructions

Read all three explanations before you start. Each exercise builds on the previous one.

## M1-E1 (Simple): Variables & f-Strings

* **How to answer:** To store the numbers we must use the assignment operator (`=`) to define two integer variables, and to keep the sum we can store the calculation in a third variable using the `+` operator. To display the text dynamically we must use a `print()` statement containing an f-string (a string that starts with `f` before the quotes) where the variable names are enclosed in curly braces (`{}`).

## M1-E2 (Medium): Temperature Converter

* **How to answer:** To receive the temperature we must use the `input()` function, but remember that `input()` always returns text, so the value must be converted to a number with `float()` before any math is done. Then we write the conversion formula using the arithmetic operators (`*`, `/`, `+`), keeping in mind that Python follows the usual order of operations and that parentheses can be used to control it. To limit the decimal places we must wrap the result in the `round()` function, which takes the value and the number of decimals, and finally display everything with an f-string.

## M1-E3 (Hard): Bill Splitter

* **How to answer:** To receive the three values we must use three separate `input()` calls and convert each one to the right type: `float()` for the bill and `int()` for the tip percentage and the number of people. The best strategy is to solve the problem in small steps, storing each result in its own variable: first the tip (the bill multiplied by the percentage divided by 100), then the total (bill plus tip), and last the amount per person (total divided by the number of people). Each of the three results must be wrapped in `round()` with 2 decimals before being displayed with `print()` and f-strings.
