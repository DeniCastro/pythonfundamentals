# Module 2: Conditionals: Instructions

Read all three explanations before you start. Each exercise uses more of the same tools than the one before.

## M2-E1 (Simple): Even or Odd

* **How to answer:** To receive the number we must use `input()` and convert it with `int()`. To check if a number is even we must use the modulo operator (`%`), which gives the remainder of a division: a number is even when the remainder of dividing it by 2 is zero. The comparison must be made with the equality operator (`==`, two equal signs, not one), inside an `if` statement with an `else` that covers every other case.

## M2-E2 (Medium): Age Categorization

* **How to answer:** To choose between more than two outcomes we must use an `if` / `elif` / `else` chain. Python checks the conditions from top to bottom and runs only the first one that is true, so the order matters: if we start with the lowest range, each following `elif` only needs to check its upper limit, because the previous conditions have already ruled out the lower ages. Use comparison operators such as `<=` for the limits, and use `else` for the last category, which has no upper limit.

## M2-E3 (Hard): Leap Year Checker

* **How to answer:** To solve this we must first translate the three rules into conditions using the modulo operator (`%`) to test divisibility (a year is divisible by a number when the remainder is `0`). Then there are two valid approaches: build one single condition combining the rules with the logical operators `and`, `or` and `not` (using parentheses to group them), or build an `if` / `elif` / `else` chain that checks the most specific rule first and the most general rule last. Whichever you choose, test your program with the four years given in the exercise, since they were chosen to exercise every rule.
