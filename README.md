
# Project Printf

---

## Description

The `_printf` function prints output to the standard output (stdout) stream based on the given format string.

This version of `_printf` only handles basic formatting options and does not support advanced features like flag characters, field width, precision, or length modifiers.

This implementation is a simple demonstration and not a complete replacement for the standard `printf` function.

It supports the following format specifiers:

| Format Specifier | Output              |
|-------------------|---------------------|
| `%c`              | Character          |
| `%s`              | String             |
| `%d`              | Decimal integer    |
| `%i`              | Integer            |
| `%%`              | Percent character `%` |

---


## Compilation
$ gcc -Wall -Werror -Wextra -pedantic -std=gnu89 -Wno-format *.c
## Usage/Examples

```c
#include <stdio.h>

int main() {
    printf("Hello, world!");
    return 0;
}

```


## Output
Hello World!
## Files
- **main.h file**: It serves as an interface for other files to access the functions defined in the implementation.
- **_printf.c** : Contains the main function that handles the custom format specifiers: It takes the format string and any additional arguments, processes the format specifiers, and calls the appropriate functions to handle each specifier.
- **functions.c** : Contains a set of functions that handle specific format specifiers: %i, %d, %s, %c, and %%. Each function takes the corresponding argument and prints it in the desired format.
- **get_func.c** : Determines the appropriate printing function based on the provided format specifier character (i, d, s, c, %).

## Authors

- Derick Quinones Medina [@DerickJoel-dev](https://github.com/DerickJoel-dev)
