# Module 6: Functions + First Look at `import`: Instructions

Read all three explanations before you start. This module brings together everything from the previous five.

## M6-E1 (Simple): Simple Function

* **How to answer:** To create a function we must use the `def` keyword followed by the function name and parameters in parentheses, and to have it work we must send the calculated result back using the `return` statement before calling the function by its name. The returned value can then be stored in a variable and displayed with an f-string.

## M6-E2 (Medium): Prime Number Function

* **How to answer:** To decide if a number is prime, the function must first return `False` right away for numbers smaller than 2. Then it must use a `for` loop to test the possible divisors, using the modulo operator (`%`) to check whether any of them divides the number evenly, and return `False` as soon as one does, since `return` ends the function immediately. If the loop finishes without finding any divisor, the `return True` must be written **after** the loop, with no indentation. To print the results, a second loop calls the function for each number from 1 to 20 and collects the primes (for example, by adding them to a string or a list) so they can be shown in a single line.

## M6-E3 (Hard): Dice Game

* **How to answer:** To use a ready-made tool we must write `import random` at the top of the file, and then call it with the module name, a dot, and the function name, as in `random.randint(1, 6)`, which gives a random whole number between the two values (both included). Inside the function, roll one die for the player and one for the computer, compare them with an `if` / `elif` / `else`, and send the answer back with `return`. Since a function can return more than one value separated by commas (a tuple), it can send back both dice and the result text, and the loop that calls the function three times can unpack them into separate variables before printing each round with an f-string.
