# Libft - Your Very First Own C Library

![Libft](libft_logo.png)

## Table of Contents
- [Introduction](#introduction)
- [Common Instructions](#common-instructions)
- [Mandatory Part](#mandatory-part)
  - [Technical Considerations](#technical-considerations)
  - [Part 1 - Libc Functions](#part-1---libc-functions)
  - [Part 2 - Additional Functions](#part-2---additional-functions)
- [Bonus Part](#bonus-part)

## Introduction

Libft is a C programming project aimed at creating a custom C library containing a set of general-purpose functions. The goal is to understand and implement functions similar to those found in the standard C library (libc). This library will serve as a foundation for future C school assignments.

## Common Instructions

- **Language:** The project must be written in C.
- **Norm Compliance:** Ensure that your code complies with the Norm.
- **Functionality:** Functions should not quit unexpectedly, and memory must be properly managed to avoid leaks.
- **Makefile:** Provide a Makefile with rules for compiling and cleaning the project.
- **Testing:** Create test programs to validate your functions.

## Mandatory Part

### Technical Considerations

- Declaring global variables is forbidden.
- Use static functions for helper functions.
- Place all files at the root of your repository.
- Unused files are not allowed.
- Compilation flags: -Wall -Wextra -Werror.
- Use the `ar` command to create your library.

### Part 1 - Libc Functions

Implement libc functions with the 'ft_' prefix. Some functions include:
- isalpha
- isdigit
- strlen
- memcpy
- strchr
- atoi

### Part 2 - Additional Functions

Implement custom functions such as:
- `ft_substr`
- `ft_strjoin`
- `ft_strtrim`
- `ft_split`
- `ft_itoa`
- and more...

## Bonus Part

Expand your library to include functions for manipulating linked lists using the `t_list` structure.

Functions to implement include:
- `ft_lstnew`
- `ft_lstadd_front`
- `ft_lstsize`
- `ft_lstlast`
- `ft_lstadd_back`
- `ft_lstdelone`
- `ft_lstclear`
- `ft_lstiter`
- `ft_lstmap`

