# Libft

## Description
Libft is a fundamental project at 42 that involves creating a library of useful C functions to be used in future projects. The library includes standard string manipulation functions, memory allocation functions, linked list functions, and additional utility functions. Developing Libft enhances proficiency in programming concepts and improves the ability to work with data structures in C.

## Features
- Standard string manipulation functions (`strlen`, `strcpy`, `strcat`, etc.)
- Memory allocation functions (`malloc`, `free`, `memcpy`, etc.)
- Linked list functions (`lstnew`, `lstadd_front`, `lstmap`, etc.)
- Additional utility functions for character checking, string manipulation, and more

## Usage
1. Clone this repository: `git clone git@github.com:manugonz42/Libft.git`
2. Navigate to the project directory: `cd Libft`
3. Compile the library: `make`
4. Link the library to your future projects by including the header file and compiling with the library.

## Example
```c
#include "libft.h"

int main(void) {
    // Example usage of Libft functions
    char *str = "Hello, Libft!";
    int len = ft_strlen(str);
    ft_putstr_fd("Length of the string: ", 1);
    ft_putnbr_fd(len, 1);
    ft_putchar_fd('\n', 1);

    return 0;
}
