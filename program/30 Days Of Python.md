## Day1 - Introduction

### Introduction

Python is a high-level programming language for general-purpose programming. It is an open source, interpreted, objected-oriented programming language.

>It is a programming language which is very close to human language and because of that it is easy to learn and use.

### Basic Python

Indentation in many languages is used to increase code readability, however Python uses indention to create block of codes.

Any text starting with # in Python is a comment:
```pthon
# this is single line comment 
"""
this is multiline comment
"""
```

Data types:
-   Number
    -   Integer
    -   Float
    -   Complex
-   String
-   Boolean
-   List
-   Dictionary
-   Tuple
-   Set

## Day2 - Variables, Built-in Functions

### Built-in Functions

Built-in functions are globally available for your use that mean you can make use of the built-in functions without importing or configuring.

### Variables

Variables store data in a computer memory. A mnemonic variable is a variable name that can be easily remembered and associated. A variable refers to a memory address in which data is stored. Number at the beginning, special character, hyphen are not allowed when naming a variable.

Python Variable Name Rules:
-   A variable name must start with a letter or the underscore character
-   A variable name cannot start with a number
-   A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, _)
-   Variable names are case-sensitive

>Standard Python Variable Naming Style: use underscore character after each word for a variable containing more than one word.

## Day3 - Operators

### Boolean

A boolean data type represents one of the two values: `True` or `False`.

### Operators

-   Assignment Operators are used to assign values to variables.
-   Arithmetic Operators
-   Comparison Operators
    -   …
    -   is: Returns true if both variables are the same object
    -   is not: Returns true if both variables are not the same object
    -   in: Returns True if the queried list contains a certain item
    -   not in: Returns True if the queried list doesn’t have a certain item
-   Logical Operators

## Day4 - Strings

Any data under single, double or triple quote are strings.

old style string formatting:
- `%s`
- `%d`
- `%f`
- `%.number of digitsf`

new style string formatting: `str.format`

string interpolation / f-strings.

## Day5 - Lists

There are four collection data types in Python:
- List is a collection which is ordered and changeable(modifiable). Allows duplicate members.
- Tuple is a collection which is ordered and unchangeable or unmodifiable(immutable). Allows duplicate members.
- Set is a collection which is unordered, un-indexed and unmodifiable, but we can add new items to the set. Duplicate members are not allowed.
- Dictionary is a collection which is unordered, changeable(modifiable) and indexed. No duplicate members.