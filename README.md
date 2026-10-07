\# Python



My notes and practice for core Python, split into 14 topics. They start with basic syntax and built-in data structures and finish with regular expressions, iterators, and generators.



I'm building my skills in data analysis and working toward machine learning, and this is the programming foundation for everything else in my learning path. The goal was not to memorize syntax but to understand how Python actually behaves, so the libraries I use later (NumPy, pandas, Matplotlib, scikit-learn) don't feel like black boxes.



\---



\## Contents



| #  | Topic                                                                                     | What it covers                                                                 |

| -- | ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |

| 01 | \[Core Syntax and Environment](01\_Python\_Core\_Syntax\_and\_Environment\_Setup.ipynb)          | Syntax, variables, data types, operators, input/output, type conversion        |

| 02 | \[String Methods](02\_Python\_String\_Methods.ipynb)                                          | Indexing, slicing, searching, formatting, transforming, and validating strings |

| 03 | \[Lists](03\_Python\_Lists.ipynb)                                                            | Indexing, slicing, methods, nested lists, copying, iteration                   |

| 04 | \[Sets](04\_Python\_Sets.ipynb)                                                              | Uniqueness, membership, set operations, practical use cases                    |

| 05 | \[Tuples](05\_Python\_Tuples.ipynb)                                                          | Immutability, unpacking, nesting, tuple operations                             |

| 06 | \[Dictionaries](06\_Python\_Dictionaries.ipynb)                                              | Key-value data, methods, iteration, nested dictionaries                        |

| 07 | \[Control Flow](07\_Python\_Control\_Flow.ipynb)                                              | Conditions, loops, `break`, `continue`, `pass`                                 |

| 08 | \[Functions](08\_Python\_Functions.ipynb)                                                    | Parameters, arguments, scope, return values, recursion, lambda                 |

| 09 | \[Comprehensions and Generators](09\_Python\_Comprehensions\_and\_Generator\_Expressions.ipynb) | List, set, and dict comprehensions; generator expressions                      |

| 10 | \[File Handling](10.%20Python%20File%20Handling/)                                          | File modes, reading, writing, appending, context managers                      |

| 11 | \[Error Handling and Exceptions](11\_Python\_Error\_Handling\_and\_Exceptions.ipynb)            | `try`, `except`, `else`, `finally`, raising and custom exceptions              |

| 12 | \[Modules and Packages](12\_Python\_Modules\_and\_Packages.ipynb)                              | Imports, namespaces, the standard library, organizing code                     |

| 13 | \[Regular Expressions](13\_Python\_Regular\_Expressions.ipynb)                                | Patterns, character classes, quantifiers, groups, substitution                 |

| 14 | \[Iterators and Generators](14\_Python\_Iterators\_and\_Generators.ipynb)                      | The iterator protocol, custom iterators, `yield`, lazy evaluation              |



\---



\## How the topics are ordered



The order is deliberate. Each topic builds on the ones before it:



```text

Syntax and types → Data structures → Control flow → Functions

→ Comprehensions → Files → Exceptions → Modules → Regex → Iterators and generators

```



Data structures come before loops and functions because it's much easier to write a loop once you know what you're looping over. Iterators and generators come last because they make more sense after comprehensions, functions, and a decent feel for how Python handles objects.



If you're following along, I'd suggest going in order.



\---



\## How I studied each topic



For every topic I tried to answer the same questions:



\* What is Python doing under the hood?

\* Why does it behave this way?

\* What's the difference between similar options, and when do I pick one over the other?

\* What are the common mistakes?

\* Where would this show up in real code, especially in data work?



Examples use realistic situations like customers and transactions, employees and departments, text cleaning, and file-based data, instead of abstract `foo` and `bar` examples.



\---



\## Running the code



You need Python 3 installed. The material is provided as Jupyter notebooks, so you can open them with Jupyter Notebook/JupyterLab or run them in Google Colab.



Some topics contain multiple notebooks, particularly File Handling, where the material is divided into phases.



\---



\## Repository structure



```text

Python/

├── README.md

├── 01\_Python\_Core\_Syntax\_and\_Environment\_Setup.ipynb

├── 02\_Python\_String\_Methods.ipynb

├── 03\_Python\_Lists.ipynb

├── 04\_Python\_Sets.ipynb

├── 05\_Python\_Tuples.ipynb

├── 06\_Python\_Dictionaries.ipynb

├── 07\_Python\_Control\_Flow.ipynb

├── 08\_Python\_Functions.ipynb

├── 09\_Python\_Comprehensions\_and\_Generator\_Expressions.ipynb

├── 10. Python File Handling/

│   ├── 10\_Python\_File\_Handling\_Phase\_1.ipynb

│   ├── 10\_Python\_File\_Handling\_Phase\_2.ipynb

│   ├── 10\_Python\_File\_Handling\_Phase\_3\_.ipynb

│   ├── 10\_Python\_File\_Handling\_Phase\_4.ipynb

│   └── 10\_Python\_File\_Handling\_Phase\_5.ipynb

├── 11\_Python\_Error\_Handling\_and\_Exceptions.ipynb

├── 12\_Python\_Modules\_and\_Packages.ipynb

├── 13\_Python\_Regular\_Expressions.ipynb

└── 14\_Python\_Iterators\_and\_Generators.ipynb

```



Each topic is kept as a separate notebook or folder, making the material easy to review and expand independently.



\---



\## What comes next



This repository is the base for the rest of my path: NumPy, pandas, data visualization, SQL, statistics, and then machine learning. Object-oriented Python is the next Python topic I'm working on.



\---



\## Status



Substantially complete. I still come back to these topics to fix mistakes and add examples.



\---



\## Author



\*\*Abdullah Waseem\*\*

BS Computer Science, University of Haripur



GitHub: \[TheAbdullahWaseem](https://github.com/TheAbdullahWaseem)



\---



These notes are a record of my learning and a reference I can return to. If you find a mistake or have a suggestion, feel free to open an issue.



