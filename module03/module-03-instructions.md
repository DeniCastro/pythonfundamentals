# Module 3: Loops: Instructions

Read all three explanations before you start. Exercises 2 and 3 use the same pattern: a variable that grows as the loop runs.

## M3-E1 (Simple): Multiplication Table

* **How to answer:** To repeat an action a fixed number of times we must use a `for` loop together with the `range()` function. Remember that `range(start, stop)` includes the start value but **stops before** the stop value, so to reach 10 the stop value must be 11. The loop variable changes on every turn, so we can use it inside an f-string together with the number received from `input()` (converted with `int()`) to print each line of the table.

## M3-E2 (Medium): Sum of Numbers

* **How to answer:** To add values over many turns we must use the accumulator pattern: create a variable with the value `0` **before** the loop, and inside the loop add the current number to it using the `+=` operator. The loop itself is a `for` over `range()` (watch the stop value again). The `print()` that shows the final total must be written **after** the loop, with no indentation, so it runs only once at the end.

## M3-E3 (Hard): Even Numbers Counter

* **How to answer:** To keep track of two things at the same time we must create two accumulators before the loop, one starting at `0` to count how many even numbers were found and another starting at `0` to add them up. Inside the `for` loop, an `if` statement using the modulo operator (`%`) decides whether the current number is even, and only then are both accumulators updated (one with `+= 1`, the other with `+=` the current number). The results are printed after the loop ends.
