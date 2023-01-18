# Reading 3
- An array is a C construct that creates an ordered collection of data elements of the same type and associates this collection with a single program variable
- Ordered means that each element is in a specific position in the collection of values
## 1.5
- C version uses an array of `int` types to store the collection of values.
- when declaring an array variable in C, the programmer must specify its type.
```
int  arr[10];  // declare an array of 10 ints
char str[20];  // declare an array of 20 chars
```
```
int array[10];   // an array of size 10 has valid indices 0 through 9
array[10] = 100;  // 10 is not a valid index into the array
```
- the function can alter the elements in the passed array or list.
- The `[]` after the parameter name tells the compiler that the type of the parameter arr is `array of int`, not `int` like the parameter `size`.
- strings in C must end with a special character value, the null character (`'\0'`), to indicate the end of the string.
- Strings that end with a null character are said to be null-terminated.
- Programs that use these string library functions need to include the `string.h` header.
- use the `%s` placeholder in the format `string`.
- The `strlen` function in the C string library returns the number of characters in its string argument. 
## 2.1


