---
layout: post
title: "General Instructions"
category: Other Resources
permalink: /other_resources/general_guide
tags: 
    - guide
    - assignment
    - instruction
---

## General Guide line

- This document could potentially change up to a day before submission. :smile:

- You **cannot** leave **any** additional file in your submission directory.

- [RTFM](https://en.wikipedia.org/wiki/RTFM):sunglasses:: Your reference guide is called **Google / man / the Internet / ...**.

## Code Standard

### 1. Why impose a standard?

- To format and standardize your code so that anyone can read and understand them easily.
- To guide you in writing short and simple code.

### 2. The standard for submissions

- All of your files must repect the standard. If you made any standard error you'll get a 0:boom: for the assignment or even for the whole project.:sob:

### 3. Suggestions

- You will realize soon enough that the standard isn't as intimidating as it seems. On the contrary, it'll help you more than you know. It'll allow you to read others' code more easily and vice versa. A source file containing one standard error will be treated the same way as a source file containing 10 standard errors. I strongly advise you to keep the standard in mind while coding - even though you may feel it's slowing you down at first. In time, it'll become a reflex.:fist:

## Standard

### 1. Variables

- Variables and functions names can only contain lowercases, digits and '\_'
- Files and directories names can only contain lowercases, digits and '\_'
- The file must compile.
- Characters that aren't part of the standard ascii table are forbidden.

### 2. Formatting

- All your files must begin with the standard header.
- You must indent your code with 4-space tabs.
- Each function must be maximum 25 lines, not counting the function's own curly brackets.
- Each line must be at most 80 columns wide, comments included.
- One instruction per line.
- An empty line must be empty: no spaces or tabs.
- A line can never end with spaces or tabs.
- You need to start a new line after each curly bracket or end of control structure.
- Unless it's the end of file, each comma or semi-colon must be followed by a space.
- Each operator or operand must be seperated by one - and only one - space.
- Each variable declaration must be indented on the same column.
- The asterisks(\*) that go with pointers must be stuck to variable names.
- One single variable declaration per line.
- We cannot stick a declaration and an initialization on the same line, except for global variables and static variables.
- Declarations must be at the beginning of a function, and must be separated by an empty line.
- There cannot be an empty line between declarations or implementations(initializations).
- No Multiple assignments.
- You may add a new line after an instruction or control structure(if-else, loops), but you'll have to add an indentation with brackets or affectation operator. Operators must be at the beginning of a line.

### 3. Functions

- Parameters in functions' prototypes must be named.
- A function can take 4 named parameters max.
- A function that doesn't take arguments must be explicitely prototyped with the word "void" as argument.
- Each function must be separated from the next by an empty line.

### 4. Typedef, struct, enum, union

- Add a tab between two parameters of a typedef
- You cannot declare a struct in a .c file.

### 5. Headers

- The Things allowed in header files are : header inclusions, declarations, defines, prototypes and macros.
- All includes (.c or .h) must be at the beginning of the fine.
- Functions' prototypes must exclusively be in .h files.
- Unused header inclusions (.h) are forbidden.

### 6. Macros and Pre-processors

- Only macros names are uppercase.
- Multiline macros are forbidden.
- You must indent characters following `#if, #ifdef, or #ifndef`

### 7. Comments

- You are allowed to comment your code in your source files.
- Comments can not be inside functions' bodies.
- Comments start and end by a single line. All intermediary lines must align and start by "\*\*"
- No comments with //

### 8. Files

- You cannot include a .c file. (#include)
- You cannot have more than 5 function-definitions in a .c file.
