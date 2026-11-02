# 01 - Python Fundamentals

The first course in the Python learning path. You will go from writing your first `print()` to building a small program of your own, using only the core building blocks of the language.

**Level:** Beginner (no programming experience needed)
**Modules:** 6 | **Exercises:** 18 | **Project:** 1

---

## What You Will Learn

By the end of this course you will be able to:

- Store and convert data with variables, types, and user input
- Make decisions in your code with conditionals
- Repeat actions with `for` and `while` loops
- Work with text and lists
- Organize data with dictionaries and tuples
- Write your own functions and use a first ready-made module (`random`)
- Combine all of the above in a complete project

## What You Need

- **Python 3.10 or newer.** Check your version by running `python --version` (or `python3 --version`) in a terminal. Download it from [python.org](https://www.python.org/downloads/) if needed.
- **A code editor.** [VS Code](https://code.visualstudio.com/) is a good free choice. IDLE, which comes with Python, also works.
- **Curiosity and a bit of patience.** Making mistakes is part of the process.

---

## Course Structure

| Module | Topic | You will practice |
|---|---|---|
| 1 | Variables, Types & I/O | `print`, `input`, f-strings, arithmetic |
| 2 | Conditionals | `if`/`elif`/`else`, comparison and logical operators |
| 3 | Loops | `for`, `range`, `while`, the accumulator pattern |
| 4 | Strings & Lists | indexing, slicing, methods, looping over data |
| 5 | Dictionaries & Tuples | key-value data, lookups, tuple unpacking |
| 6 | Functions + First Look at `import` | `def`, `return`, parameters, `import random` |
| Project | Contact Book | everything above, together |

Each module has **3 exercises**:

| Level | What to expect |
|---|---|
| Simple | One concept, applied directly |
| Medium | One concept, with a little more thinking |
| Hard | Two concepts combined (not impossible, just a challenge) |

---

## Repository Layout

```
python-fundamentals/
├── README.md
├── module-01-variables-types-io/
│   ├── exercises.md
│   └── instructions.md
├── module-02-conditionals/
├── module-03-loops/
├── module-04-strings-lists/
├── module-05-dictionaries-tuples/
├── module-06-functions-import/
└── project/
```

- **`exercises.md`** contains the problems for that module.
- **`instructions.md`** explains *how to approach* each exercise (which tools to use and why) without giving the answer.

---

## How to Use This Course

1. **Go in order.** Each module builds on the previous one.
2. **Read the exercise first** and try to solve it on your own for a few minutes.
3. **Stuck?** Open the module's `instructions.md`. It will point you to the right tools without spoiling the solution.
4. **Run your code** and compare the result with the example output in the exercise.
5. **Test different inputs.** Does your program still work with a different number, a different word, an edge case?
6. **Move on** only when all three exercises of the module work.

## Tips for Success

- **Type the code yourself.** Copy-pasting teaches much less than typing.
- **Read the error message.** It tells you the line number and the kind of problem. Start there.
- **Use `print()` to investigate.** If something behaves strangely, print the variables to see what they actually contain.
- **Take breaks.** A fresh mind often finds the bug in seconds.
- **Don't compare yourself to others.** Finishing the course at your own pace is a win.

---

## Common Mistakes to Watch For

- Using `=` (assignment) when you meant `==` (comparison)
- Forgetting that `input()` always returns text
- Off-by-one errors with `range()`, since the end value is **not** included
- Wrong indentation after `if`, `for`, or `def`
- Printing inside a loop when you meant to print once, after it

---

## What's Next

After completing this course, continue with **Python Essentials**, where you will learn file handling, error handling, comprehensions, the standard library, and how to write your own modules.

**Path:** Python Fundamentals → Python Essentials → Python Intermediate → Python Advanced

---

🐍
