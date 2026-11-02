# Module 5: Dictionaries & Tuples: Instructions

Read all three explanations before you start. Dictionaries store data as pairs, so most of the work is choosing the right key.

## M5-E1 (Simple): Person Dictionary

* **How to answer:** To create a dictionary we must use curly braces with `key: value` pairs separated by commas, and to read a value we must write the dictionary name followed by the key in square brackets. To change an existing value or to add a new key, we use the same square-bracket syntax with the assignment operator (`=`): if the key already exists its value is replaced, and if it does not exist it is created. When reading dictionary values inside an f-string, remember that the quotes around the key must be different from the quotes that wrap the f-string (for example, single quotes inside double quotes).

## M5-E2 (Medium): Inventory Lookup

* **How to answer:** To receive the product name we must use `input()`. To check whether the product exists we have two options: the `in` operator (which tells us whether a key is in the dictionary) combined with an `if` / `else`, or the `.get()` method, which looks up a key and returns a default value of our choosing when the key is missing. Either way, the program must print a different message for each situation, and the same f-string can be reused for the product name.

## M5-E3 (Hard): Gradebook

* **How to answer:** To visit every student we must use a `for` loop over the dictionary's `.items()` method, which gives both the name (key) and the list of grades (value) on every turn. Inside the loop we calculate the average with an accumulator that adds the grades and a division by `len()` of the list, then round it and print it. To find the top student we must keep two extra variables created before the loop (one for the best average so far, starting at `0`, and one for the best name) and update both with an `if` whenever the current average is higher than the stored one.
