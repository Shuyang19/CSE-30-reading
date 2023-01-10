# reading 1
- C program is expressed as a sequence of statements (steps)
- C programs are structured as a set of functions (procedures)
- Must have the main function
- C doesn’t have support for object-oriented programming
## 1.1
 - C version might be put in a file named `hello.c`
```
/*
    The Hello World Program in C
 */

/* C math and I/O libraries */
#include <math.h>
#include <stdio.h>

/* main function definition: */
int main() {
    // statements end in a semicolon (;)
    printf("Hello World\n");
    printf("sqrt(4) is %f\n", sqrt(4));

    return 0;  // main returns value 0
}
```

Difference between python and C:

- In C, multiline comments begin with `/*` and end with `*/`, and single-line comments begin with `//`
- In C, libraries are included (imported) using `#include`. All `#include` statements appear at the top of the program, outside of function bodies.
- In C, blocks (for example, function, loop, and conditional bodies) start with `{` and end with `}`.
- In C, `int main(){ }` defines the main function. The `main` function returns a value of type `int`, which is C’s name for specifying the signed integer type (signed integers are values like -3, 0, 1234). The main function returns the int value 0 to signify running to completion without error.
- In C, each statement ends with a semicolon`;`. In C, statements must be within the body of some function (in `main` in this example).
- In C, the `printf` function prints a formatted string. Values for the placeholders in the format string are additional arguments separated by commas (for example, the value of sqrt(4) will be printed in place of the `%f` placeholder in the format string).
- C’s `printf` function doesn’t automatically print a newline character at the end like Python’s print function does. As a result, C programmers need to explicitly specify a newline character (`\n`) in the format string when a newline is desired in the output.
 
 
