## printf()
The printf project is a collaboration between Fortunatus Felix and Nancy Idiong, students of Software Engineering at ALX, were a function named "_printf" imitates the actual "printf" command located in the stdio.h library. It contains some of the basic features and functions found in the manual 3 of "printf".

_printf() is a function that performs formatted output conversion and print data. 

Integer

Input: _printf("There are %i dozens in a gross\n", 12);
Output: There are 12 dozens in a gross
Character

Input: _printf("The first letter in the alphabet is %c\n", 'A');
Output: The first letter in the alphabet is A
String

Input: _printf("%s\n", 'This is a string.');
Output: This is a string.
Decimal:

Input: _printf("%d\n", 1000);
Output: 1000

## File Description 


### _printf.c

contains the fucntion _printf, which uses the prototype int _printf(const char *format, ...);. The format string is composed of zero or more directives. See man 3 printf for more detail. _printf will return the number of characters printed (excluding the null byte used to end output to strings) and will write output to stdout, the standard output stream.

------------

### main.h
Header File Were All Prototypes Are Saved.

------------

### functions.c functions1.c functions2.c

contains all function of each specifier used for _printf.
all function have its own description inside the file.

------------

### get_flags.c
contains all function for each flag use for _printf.
```

------------

### get_precision.c
Function That Writes The String To Stdout.
```c
/* Indetifier : %s */
```

------------

### get_size.c
Function That Prints:
Decimal In Uppercase Hexadecimal /* Indetifier : %X */
An Unsigned Integer /* Indetifier : %u */
Decimal In Octal /* Indetifier : %o */. 
Decimal In Hexadecimal /* Indetifier : %x */

------------

### get_width.c
contains functions to get width for spcifics spcifiers.

------------

### handle_print.c
contains arguments types used for _printf.

------------

### utils.c
contains some necessary functionalities for _printf.


------------

### write_handlers.c
contains write functions.


------------

### Authors
Fortunatus Felix and Nancy Idiong

------------

### End
