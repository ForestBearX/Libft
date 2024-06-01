# 🌟 Libft - Your Custom C Library

Welcome to **Libft**, your very own library of essential C functions. This project will have you implementing a variety of functions, providing a solid foundation for future coding endeavors. Let's dive into the details!

## 📁 File Structure

### `.c` Files 
All your function implementations will reside here. Keep your code modular and organized!

### `.h` (Header) File
Your header file serves two primary purposes:
- **Centralized Includes:** Instead of including headers like `#include <unistd.h>` in all your `.c` files, simply include them once in your header file. All `.c` files will reference this header.
- **Function Prototypes:** If a function from one `.c` file is needed in another, use `#include "libft.h"`. This header file will manage your function declarations.

**Reminder:** Always add `#include "libft.h"` at the top of your `.c` files.

### `Makefile`
Automate your compilation process with a Makefile. Unlike in the piscine, where you used `gcc` manually, you can now compile your project with a single `make` command.

## 📜 Libft Functions

### 🆎 Functions from `<ctype.h>`

- [`ft_isalpha`](ft_isalpha.c) - Checks for an alphabetic character.
- [`ft_isdigit`](ft_isdigit.c) - Checks for a digit (0 through 9).
- [`ft_isalnum`](ft_isalnum.c) - Checks for an alphanumeric character.
- [`ft_isascii`](ft_isascii.c) - Checks if the character fits into the ASCII set.
- [`ft_isprint`](ft_isprint.c) - Checks for any printable character.
- [`ft_toupper`](ft_toupper.c) - Converts char to uppercase.
- [`ft_tolower`](ft_tolower.c) - Converts char to lowercase.

### 🔠 Functions from `<string.h>`

- [`ft_memset`](ft_memset.c) - Fills memory with a constant byte.
- [`ft_strlen`](ft_strlen.c) - Calculates the length of a string.
- [`ft_bzero`](ft_bzero.c) - Zeros a byte string.
- [`ft_memcpy`](ft_memcpy.c) - Copies memory area.
- [`ft_memmove`](ft_memmove.c) - Copies memory area safely.
- [`ft_strlcpy`](ft_strlcpy.c) - Copies a string to a specific size.
- [`ft_strlcat`](ft_strlcat.c) - Concatenates a string to a specific size.
- [`ft_strchr`](ft_strchr.c) - Locates a character in a string.
- [`ft_strrchr`](ft_strrchr.c) - Locates a character in a string from the end.
- [`ft_strncmp`](ft_strncmp.c) - Compares two strings.
- [`ft_memchr`](ft_memchr.c) - Scans memory for a character.
- [`ft_memcmp`](ft_memcmp.c) - Compares memory areas.
- [`ft_strnstr`](ft_strnstr.c) - Locates a substring in a string.
- [`ft_strdup`](ft_strdup.c) - Creates a duplicate of a string.

### 🔢 Functions from `<stdlib.h>`

- [`ft_atoi`](ft_atoi.c) - Converts a string to an integer.
- [`ft_calloc`](ft_calloc.c) - Allocates memory and initializes it to zero.

### 🚀 Non-standard Functions

- [`ft_substr`](ft_substr.c) - Returns a substring from a string.
- [`ft_strjoin`](ft_strjoin.c) - Concatenates two strings.
- [`ft_strtrim`](ft_strtrim.c) - Trims the beginning and end of a string with specified characters.
- [`ft_split`](ft_split.c) - Splits a string using a specified character.
- [`ft_itoa`](ft_itoa.c) - Converts a number to a string.
- [`ft_strmapi`](ft_strmapi.c) - Applies a function to each character of a string.
- [`ft_striteri`](ft_striteri.c) - Applies a function to each character of a string, passing its index.
- [`ft_putchar_fd`](ft_putchar_fd.c) - Outputs a char to a file descriptor.
- [`ft_putstr_fd`](ft_putstr_fd.c) - Outputs a string to a file descriptor.
- [`ft_putendl_fd`](ft_putendl_fd.c) - Outputs a string to a file descriptor, followed by a new line.
- [`ft_putnbr_fd`](ft_putnbr_fd.c) - Outputs a number to a file descriptor.

### 🌿 Linked List Functions

- [`ft_lstnew`](ft_lstnew.c) - Creates a new list element.
- [`ft_lstadd_front`](ft_lstadd_front.c) - Adds an element to the beginning of a list.
- [`ft_lstsize`](ft_lstsize.c) - Counts the number of elements in a list.
- [`ft_lstlast`](ft_lstlast.c) - Returns the last element of a list.
- [`ft_lstadd_back`](ft_lstadd_back.c) - Adds an element to the end of a list.
- [`ft_lstclear`](ft_lstclear.c) - Deletes and frees a list.
- [`ft_lstiter`](ft_lstiter.c) - Applies a function to each element of a list.
- [`ft_lstmap`](ft_lstmap.c) - Applies a function to each element of a list, returning a new list.

Embrace the power of C with Libft, and happy coding! 🚀
