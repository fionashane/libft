
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
git clone https://github.com/your_username/libft.git
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
- ft_memset
- ft_bzero
- ft_memcpy
- ft_memccpy
- ft_memmove
- ft_memchr
- ft_memcmp
- ft_calloc
- ft_strdup

### String functions
- ft_strlen
- ft_strlcpy
- ft_strlcat
- ft_strchr
- ft_strrchr
- ft_strnstr
- ft_strncmp
- ft_atoi
- ft_itoa
- ft_substr
- ft_strjoin
- ft_strtrim
- ft_split
- ft_strmapi
- ft_putchar_fd
- ft_putstr_fd
- ft_putendl_fd
- ft_putnbr_fd

### Character functions
- ft_isalpha
- ft_isdigit
- ft_isalnum
- ft_isascii
- ft_isprint
- ft_toupper
- ft_tolower

## Credits

The **libft** project was developed by [42 school](https://www.42adel.org.au). 

## License

This project is licensed under the [MIT license](https://opensource.org/licenses/MIT).
