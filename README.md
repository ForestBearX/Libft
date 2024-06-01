libft

libft is a custom C library developed as a project for 42 School. This library is a collection of essential functions that are commonly used in various C programming tasks. It includes implementations of functions from the standard C library as well as some additional utility functions.
Table of Contents

    Installation
    Usage
    Functions
    Contributing
    License

Installation

To use libft in your own projects, follow these steps:

    Clone the repository:

    sh

git clone https://github.com/yourusername/libft.git

Navigate to the project directory:

sh

cd libft

Compile the library:

sh

    make

    The compiled library libft.a can now be linked with your C projects.

Usage

To use libft functions in your project, include the header file and link the compiled library:

    Include the header file at the beginning of your source files:

    c

#include "libft.h"

Compile your project with the libft library. For example:

sh

    gcc -Wall -Wextra -Werror yourfile.c -L. -lft -o yourprogram

Functions

libft includes a variety of functions. Here are some categories and examples:
String Manipulation

    ft_strlen - Calculate the length of a string
    ft_strdup - Duplicate a string
    ft_strjoin - Concatenate two strings

Memory Management

    ft_memset - Fill memory with a constant byte
    ft_memcpy - Copy memory area
    ft_memmove - Move memory area

Character Checks and Conversions

    ft_isalpha - Check for alphabetic character
    ft_isdigit - Check for digit character
    ft_tolower - Convert uppercase letter to lowercase

Linked List Operations

    ft_lstnew - Create a new list element
    ft_lstadd_front - Add an element at the beginning of a list
    ft_lstmap - Apply a function to each element of a list and create a new list

For a full list of functions, refer to the header file or the source files in the repository.

This project is licensed under the MIT License - see the LICENSE file for details.
