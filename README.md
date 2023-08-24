
# libft - 42 Project

![libft](https://img.shields.io/badge/libft-42-success)

The **libft** project is part of the curriculum at [42 school](https://www.42adel.org.au) and aims to create a personal library of useful functions in C that will be used in subsequent projects. 

## Project Objectives

The project aims to introduce students to the basics of C programming and provides them with an opportunity to practice the following skills:
- Implementation of basic data structures, such as linked lists and binary trees
- Memory allocation and management
- String manipulation
- File input/output
- Basics of linked lists and sorting algorithms

## How to use

To use the functions in the **libft** library, you need to:
1. Clone the repository to your local machine
```bash
git clone https://github.com/fionashane/libft.git
```

2. Compile the library using the Makefile
```bash
make
```

3. Link the library to your C project 
```bash
gcc -Wall -Werror -Wextra -L. -lft -o my_program my_program.c
```

4. Include the appropriate header file in your C file
```c
#include "libft.h"
```

## Functions

The **libft** library contains the following functions:

### Memory functions

- `ft_memset(void *s, int c, size_t n)`: sets a block of memory to a specified value.
- `ft_bzero(void *s, size_t n)`: sets a block of memory to zero.
- `ft_memcpy(void *dst, const void *src, size_t n)`: copies a block of memory from source to destination.
- `ft_memccpy(void *dst, const void *src, int c, size_t n)`: copies a block of memory from source to destination until a specified character is found.
- `ft_memmove(void *dst, const void *src, size_t len)`: copies a block of memory from source to destination, handling overlapping regions.
- `ft_memchr(const void *s, int c, size_t n)`: searches a block of memory for a specified character.
- `ft_memcmp(const void *s1, const void *s2, size_t n)`: compares two blocks of memory.
- `ft_calloc(size_t count, size_t size)`: allocates a block of memory and sets it to zero.
- `ft_strdup(const char *s1)`: duplicates a string.

### String functions

- `ft_strlen(const char *s)`: returns the length of a string.
- `ft_strlcpy(char *dst, const char *src, size_t dstsize)`: copies a string to a specified destination buffer with a specified length limit.
- `ft_strlcat(char *dst, const char *src, size_t dstsize)`: appends a string to a specified destination buffer with a specified length limit.
- `ft_strchr(const char *s, int c)`: searches a string for a specified character and returns a pointer to the first occurrence.
- `ft_strrchr(const char *s, int c)`: searches a string for a specified character and returns a pointer to the last occurrence.
- `ft_strnstr(const char *haystack, const char *needle, size_t len)`: searches a string for a specified substring with a specified length limit.
- `ft_strncmp(const char *s1, const char *s2, size_t n)`: compares two strings with a specified length limit.
- `ft_atoi(const char *str)`: converts a string to an integer.
- `ft_itoa(int n)`: converts an integer to a string.
- `ft_substr(char const *s, unsigned int start, size_t len)`: extracts a substring from a string.
- `ft_strjoin(char const *s1, char const *s2)`: concatenates two strings.
- `ft_strtrim(char const *s1, char const *set)`: removes leading and trailing whitespace from a string.
- `ft_split(char const *s, char c)`: splits a string into an array of substrings.
- `ft_strmapi(char const *s, char (*f)(unsigned int, char))`: applies a function to each character in a string.
- `ft_putchar_fd(char c, int fd)`: writes a character to a file descriptor.
- `ft_putstr_fd(char *s, int fd)`: writes a string to a file descriptor.
- `ft_putendl_fd(char *s, int fd)`: writes a string followed by a newline character to a file descriptor.
- `ft_putnbr_fd(int n, int fd)`: writes an integer to a file descriptor.

### Character functions
- `ft_isalpha(int c)`: checks if a character is an alphabetic character.
- `ft_isdigit(int c)`: checks if a character is a decimal digit character.
- `ft_isalnum(int c)`: checks if a character is an alphabetic or decimal digit character.
- `ft_isascii(int c)`: checks if a character is a 7-bit ASCII character.
- `ft_isprint(int c)`: checks if a character is a printable character.
- `ft_toupper(int c)`: converts a lower-case alphabetic character to upper-case.
- `ft_tolower(int c)`: converts an upper-case alphabetic character to lower-case.

## Credits

The **libft** project was developed by [42 school](https://www.42adel.org.au).
