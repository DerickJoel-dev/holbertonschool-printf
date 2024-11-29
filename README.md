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

## Prototype

```c
int _printf(const char *format, ...);

Compilation
To compile the code, use the following command:
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 -Wno-format *.c
Usage
Syntax
To call the _printf() function, include the header file main.h and follow this structure:
#include "main.h"

int main()
{
    _printf("string to print");
    return 0;
}
Compilation
To compile the program using a makefile, run the following command:
$ make -f makefile
This will create an executable file named main.out.
To run the program, use the following command:
$ ./main.out
Authors
Derick Quiñones Medina
