# Module 4: Strings & Lists: Instructions

Read all three explanations before you start. Strings and lists share many ideas, such as indexing and looping.

## M4-E1 (Simple): String Methods and Length

* **How to answer:** To store the text we must assign the string to a variable. String methods are called with a dot after the variable name, followed by parentheses (for example, one method turns everything to uppercase and another to lowercase). To count characters we must use the built-in `len()` function, and to get a single character we must use indexing with square brackets: the first character is at position `0`, and negative positions count from the end, so `-1` is the last one.

## M4-E2 (Medium): List Statistics

* **How to answer:** To find the largest and smallest values without the built-in helpers we must start with a variable holding the first item of the list and then use a `for` loop to visit every item, using an `if` statement to replace the stored value whenever a better one is found (one variable for the largest, another for the smallest). For the average we must use an accumulator that adds every item during the loop and divide the final total by the list's length, obtained with `len()`. All results are displayed after the loop with f-strings.

## M4-E3 (Hard): Palindrome and Vowel Counter

* **How to answer:** To ignore uppercase and lowercase differences we must first convert the word to lowercase with a string method. To check the palindrome we must create the reversed version of the word using slicing (the slice `[::-1]` walks the text backwards) and compare it to the original with `==` inside an `if` / `else`. To count the vowels we must create a counter starting at `0`, loop over every character of the word, and use the `in` operator to check whether the current character is found inside a string that contains all five vowels, increasing the counter when it is.
