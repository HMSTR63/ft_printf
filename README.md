# ft_printf

## Summary
`ft_printf` is a custom implementation of the standard C library function `printf`. It provides formatted output conversion and supports various format specifiers.

## Functions
- `ft_printf`: The main function that handles formatted output. It supports the following format specifiers:
  - `%c`: Prints a single character.
  - `%s`: Prints a string.
  - `%d`/`%i`: Prints an integer.
  - `%u`: Prints an unsigned integer.
  - `%x`/`%X`: Prints a hexadecimal number (lowercase/uppercase).
  - `%p`: Prints a pointer address.
  - `%%`: Prints a percent sign.

## Note
The `main.c` file contains full tests for this project, demonstrating the usage and functionality of the `ft_printf` function.