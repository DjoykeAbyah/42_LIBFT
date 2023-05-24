# Libft

libft.a - My Very First Own Library

## Description
Libft is a custom library consisting of various functions that will be a valuable asset for your programming journey.

- [Installation](#installation)
- [Usage](#usage)
- [Part 1 - Libc Functions](#part 1 - libc functions)
- [Part 2 - Additional Functions](#part 2 - additional functions)
- [Bonus](#bonus)

## Installation
1. Clone the repository or download the source code files.
2. Compile the using the provided Makefile by simply running:

```$ make```

3. Create a main to test out the individual functions.

## Usage

The library provides a collection of functions categorized into different parts. You can use them in any C project.

### Part 1 - Libc Functions

In this section, you will find functions that replicate standard libc functions. 
These functions have the same behavior as their original counterparts but with names prefixed by "ft_". They include:

- isalpha
- isdigit
- isalnum
- isascii
- isprint
- strlen
- memset
- bzero
- memcpy
- memmove
- strlcpy
- strlcat
- toupper
- tolower
- strchr
- strrchr
- strncmp
- memchr
- memcmp
- strnstr
- atoi

Additionally, there are two functions, calloc and strdup, that require the use of malloc().

### Part 2 - Additional Functions

This section contains additional functions that are either not present in the libc or have a different form. 
These functions include:

- ft_substr: Allocates and returns a substring from a string.
- ft_strjoin: Concatenates two strings and returns the result.
- ft_strtrim: Trims specified characters from the beginning and end of a string.
- ft_split: Splits a string into an array of substrings using a delimiter.
- ft_itoa: Converts an integer into a string.
- ft_strmapi: Applies a function to each character of a string and creates a new string.
- ft_striteri: Applies a function to each character of a string, passing the index as an argument.
- ft_putchar_fd: Outputs a character to a file descriptor.
- ft_putstr_fd: Outputs a string to a file descriptor.
- ft_putendl_fd: Outputs a string to a file descriptor, followed by a newline.
- ft_putnbr_fd: Outputs an integer to a file descriptor.

### Bonus Part

his section focuses on manipulating linked lists. 
It provides functions to create, modify, and traverse linked lists. 
The bonus functions include:

- ft_lstnew: Creates a new node.
- ft_lstadd_front: Adds a node at the beginning of a list.
- ft_lstsize: Counts the number of nodes in a list.
- ft_lstlast: Returns the last node of a list.
- ft_lstadd_back: Adds a node at the end of a list.
- ft_lstdelone: Deletes a node and frees its memory.
- ft_lstclear: Deletes and frees a list and its nodes.
- ft_lstiter: Iterates over a list and applies a function to each node.
- ft_lstmap: Iterates over a list, applies a function to each node, and creates a new list.

