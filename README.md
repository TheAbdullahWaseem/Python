# Python

My notes and practice for core Python, split into 14 topics. They start with basic syntax and built-in data structures and finish with regular expressions, iterators, and generators.

I'm building my skills in data analysis and working toward machine learning, and this is the programming foundation for everything else in my learning path. The goal was not to memorize syntax but to understand how Python actually behaves, so the libraries I use later (NumPy, pandas, Matplotlib, scikit-learn) don't feel like black boxes.

---

## Contents

| #  | Topic                                                                                     | What it covers                                                                 |
| -- | ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| 01 | [Core Syntax and Environment](01_Python_Core_Syntax_and_Environment_Setup.ipynb)          | Syntax, variables, data types, operators, input/output, type conversion        |
| 02 | [String Methods](02_Python_String_Methods.ipynb)                                          | Indexing, slicing, searching, formatting, transforming, and validating strings |
| 03 | [Lists](03_Python_Lists.ipynb)                                                            | Indexing, slicing, methods, nested lists, copying, iteration                   |
| 04 | [Sets](04_Python_Sets.ipynb)                                                              | Uniqueness, membership, set operations, practical use cases                    |
| 05 | [Tuples](05_Python_Tuples.ipynb)                                                          | Immutability, unpacking, nesting, tuple operations                             |
| 06 | [Dictionaries](06_Python_Dictionaries.ipynb)                                              | Key-value data, methods, iteration, nested dictionaries                        |
| 07 | [Control Flow](07_Python_Control_Flow.ipynb)                                              | Conditions, loops, `break`, `continue`, `pass`                                 |
| 08 | [Functions](08_Python_Functions.ipynb)                                                    | Parameters, arguments, scope, return values, recursion, lambda                 |
| 09 | [Comprehensions and Generators](09_Python_Comprehensions_and_Generator_Expressions.ipynb) | List, set, and dict comprehensions; generator expressions                      |
| 10 | [File Handling](10.%20Python%20File%20Handling/)                                          | File modes, reading, writing, appending, context managers                      |
| 11 | [Error Handling and Exceptions](11_Python_Error_Handling_and_Exceptions.ipynb)            | `try`, `except`, `else`, `finally`, raising and custom exceptions              |
| 12 | [Modules and Packages](12_Python_Modules_and_Packages.ipynb)                              | Imports, namespaces, the standard library, organizing code                     |
| 13 | [Regular Expressions](13_Python_Regular_Expressions.ipynb)                                | Patterns, character classes, quantifiers, groups, substitution                 |
| 14 | [Iterators and Generators](14_Python_Iterators_and_Generators.ipynb)                      | The iterator protocol, custom iterators, `yield`, lazy evaluation              |

---

## How the topics are ordered

The order is deliberate. Each topic builds on the ones before it:

```text
Syntax and types → Data structures → Control flow → Functions
→ Comprehensions → Files → Exceptions → Modules → Regex → Iterators and generators
```

Data structures come before loops and functions because it's much easier to write a loop once you know what you're looping over. Iterators and generators come last because they make more sense after comprehensions, functions, and a decent feel for how Python handles objects.

If you're following along, I'd suggest going in order.

---

## How I studied each topic

For every topic I tried to answer the same questions:

* What is Python doing under the hood?
* Why does it behave this way?
* What's the difference between similar options, and when do I pick one over the other?
* What are the common mistakes?
* Where would this show up in real code, especially in data work?

Examples use realistic situations like customers and transactions, employees and departments, text cleaning, and file-based data, instead of abstract `foo` and `bar` examples.

---

## Running the code

You need Python 3 installed. The material is provided as Jupyter notebooks, so you can open them with Jupyter Notebook/JupyterLab or run them in Google Colab.

Some topics contain multiple notebooks, particularly File Handling, where the material is divided into phases.

---

## Repository structure

```text
Python/
├── README.md
├── 01_Python_Core_Syntax_and_Environment_Setup.ipynb
├── 02_Python_String_Methods.ipynb
├── 03_Python_Lists.ipynb
├── 04_Python_Sets.ipynb
├── 05_Python_Tuples.ipynb
├── 06_Python_Dictionaries.ipynb
├── 07_Python_Control_Flow.ipynb
├── 08_Python_Functions.ipynb
├── 09_Python_Comprehensions_and_Generator_Expressions.ipynb
├── 10. Python File Handling/
│   ├── 10_Python_File_Handling_Phase_1.ipynb
│   ├── 10_Python_File_Handling_Phase_2.ipynb
│   ├── 10_Python_File_Handling_Phase_3_.ipynb
│   ├── 10_Python_File_Handling_Phase_4.ipynb
│   └── 10_Python_File_Handling_Phase_5.ipynb
├── 11_Python_Error_Handling_and_Exceptions.ipynb
├── 12_Python_Modules_and_Packages.ipynb
├── 13_Python_Regular_Expressions.ipynb
└── 14_Python_Iterators_and_Generators.ipynb
```

Each topic is kept as a separate notebook or folder, making the material easy to review and expand independently.

---

## What comes next

This repository is the base for the rest of my path: NumPy, pandas, data visualization, SQL, statistics, and then machine learning. Object-oriented Python is the next Python topic I'm working on.

---

## Status

Substantially complete. I still come back to these topics to fix mistakes and add examples.

---

## Author

**Abdullah Waseem**
BS Computer Science, University of Haripur

GitHub: [TheAbdullahWaseem](https://github.com/TheAbdullahWaseem)

---

These notes are a record of my learning and a reference I can return to. If you find a mistake or have a suggestion, feel free to open an issue.
