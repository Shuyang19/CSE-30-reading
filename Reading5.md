# Reading 5
## 1.6
- structs are used to create a collection of data elements of different types.
- defining and using struct types:
  1) Define a new `struct` type that represents the structure.
  2) Declare variables of the new `struct` type.
  3) Use dot (`.`) notation to access individual field values of the variable.
```
struct <struct_name> {
    <field 1 type> <field 1 name>;
    <field 2 type> <field 2 name>;
    <field 3 type> <field 3 name>;
    ...
};
```
e.g.
```
struct studentT {
    char name[64];
    int age;
    float gpa;
    int grad_yr;
};
```
- name of our new struct type is two words, `struct studentT`
```
struct studentT student1, student2; // student1, student2 are struct studentT
```
- To access field values in a struct variable, use dot notation:
```
<variable name>.<field name>
```
## 2.7

