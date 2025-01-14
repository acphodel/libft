# libft
Overview

The Libft Project involves building a custom library of over 40 functions. These include replicas of standard C library functions, additional utility functions, and linked list manipulation functions.

Table of Contents

Part 1: Standard Library Functions

Part 2: Additional Functions

Part 3: Bonus Functions


Part 1: Standard Library Functions

These functions replicate existing C standard library functions. The goal is to mimic their behavior precisely, including edge cases.

Character and String Manipulation

ft_isalpha(), ft_isdigit(), ft_isalnum(), ft_isascii(), ft_isprint(): Validate characters based on specific criteria (alphabetic, numeric, alphanumeric, ASCII, printable).

ft_strlen(): Calculate the length of a string using the size_t type.

ft_toupper(), **ft_tolower(): Convert characters between uppercase and lowercase.

Memory Management

ft_memset(), ft_bzero(): Set memory areas to a specific value or zero them out.

ft_memcpy(), ft_memmove(): Copy memory blocks with or without overlap considerations.

ft_memchr(), ft_memcmp(): Search and compare memory blocks.

String Handling

ft_strchr(), ft_strrchr(): Locate characters in a string from the start or end.

ft_strlcpy(), ft_strlcat(): Copy and concatenate strings securely.

ft_strnstr(): Search for a substring within a string.

ft_strncmp(): Compare two strings up to a given length.

Conversion Functions

ft_atoi(): Convert a string to an integer.

Memory Allocation

ft_calloc(): Allocate zero-initialized memory.

ft_strdup(): Duplicate a string into newly allocated memory.


Part 2: Additional Functions

These functions extend beyond the standard library, implementing custom utilities for common tasks.

ft_substr(): Extract a substring from a given string.

ft_strjoin(): Concatenate two strings into a newly allocated string.

ft_strtrim(): Trim specified characters from the start and end of a string.

ft_split(): Split a string into an array of strings based on a delimiter.

ft_itoa(): Convert an integer into a string.

ft_strmapi(), ft_striteri(): Apply a function to each character of a string, returning a new string or modifying the original.

ft_putchar_fd(), ft_putstr_fd(), ft_putendl_fd(), ft_putnbr_fd(): Write characters, strings, and numbers to a specific file descriptor.


Part 3: Bonus Functions

The bonus functions introduce linked list manipulation, using the provided t_list structure:

ft_lstnew(): Create a new node.

ft_lstadd_front(), ft_lstadd_back(): Add nodes to the front or back of the list.

ft_lstsize(): Count the number of nodes in the list.

ft_lstlast(): Retrieve the last node of the list.

ft_lstdelone(), ft_lstclear(): Delete a single node or clear the entire list.

ft_lstiter(), ft_lstmap(): Apply a function to each node in the list or create a new list with transformed content.
