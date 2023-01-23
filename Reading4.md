## Reading 4
# 2.5.2
`int   matrix[50][100];`
- `matrix` is a 2D array of `int` values with 50 rows and 100 columns
`short little[10][10];`
- `little` is a 2D array of `short` values with 10 rows and 10 columns.
```
int   val;
short num;

val = matrix[3][7];  // get int value in row 3, column 7 of matrix
num = little[8][4];  // get short value in row 8, column 4 of little
```
- the parameter points to the argument’s array elements and therefore the function can change values stored in the passed array.
- you can leave the size of the first dimension unspecified
- allocated 2D arrays are arranged in memory in row-major order

Make a single call to `malloc`, allocating one large chunk of heap space to store all NxM array elements.
Make multiple calls to malloc, allocating an array of arrays.

# 2.9.2
- To write a program that takes command line arguments, the `main` function’s definition must include two parameters, `argc` and `argv`:
`int main(int argc, char *argv[]) { ...`
- the type of the second parameter could also be represented as `char **argv`
- `argc`, stores the argument count. Its value represents the number of command line arguments passed to the main function.
e.g
`./a.out 10 11 200`
- then `argc` will hold the value 4 (`a.out` counts as the first command line argument, and `10`, `11`, and `200` as the other three).
- `argv`, stores the argument vector. It contains the value of each command line argument.
- 
