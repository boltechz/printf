# printf
This is a project to create a Standard GNU C Printf function in the ALX SE Program

# Description
The function printf writes output to standard output. The function writes under the control of a format string that specifies how subsequent arguments (accessed via the variable-length argument facilities of stdarg) are converted for output.

# Prototype
int _printf(const char *format, ...);

# Format Specifier
| Type |      Output       |
| -----| ----------------- |
| C    | single character  |
| s    | string            |
| r	   | string in reverse |
| R    | string in rot13   |
| d    | integer in decimal|
| i	   | integer           |
| %    | percent sign      |
| x	   | lowercase hex     |
| X    | uppercase hex     |
| b	   | binary            |
| o	   | octal             |
| u	   | unsigned          |
| p    | pointer           |
| F	   | expletive         |

# EXAMPLE
Character: printf("%c", 'Z'); Output:: Z

String: printf("%s", 'This is ALX team project.'); Output: This is ALX team project.

Integer: printf("%i", 5); Output: 5

# Project Requirements
. Allowed editors: vi, vim, emacs
. All your files will be compiled on Ubuntu 20.04 LTS
. Your programs and functions will be compiled with gcc using the flags -Wall -Werror -Wextra and -pedantic
. A README.md file, at the root of the folder of the project is mandatory
. Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl.
. You are not allowed to use global variables
. In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
. The prototypes of all your functions should be included in your header file called main.h
. Don’t forget to push your header file
. All your header files should be include guarded
. Note that we will not provide the _putchar function for this project.

# Compilation
gcc -Wall -Werror -Wextra -pedantic *.c

# Authors
Boluwatife Akinola
Udochukwu Reginald
