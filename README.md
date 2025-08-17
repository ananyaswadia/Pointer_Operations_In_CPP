# Pointer_Operations_In_CPP
## Aim
To study and implement pointer operations (call by refernce and call by value) in C++.
## Tools
Visual Studio Code
## Theory
### Call by Value:
Mechanism: When an argument is passed by value, a copy of the actual argument's value is made and passed to the function's formal parameter.
Effect on Original Data: Any modifications made to the formal parameter within the function do not affect the original variable in the calling scope, as the function operates on a separate copy.
Syntax: Standard parameter declaration (e.g., void func(int x)).
### Call by Reference:
Mechanism:
When an argument is passed by reference, the address (or a reference/alias) of the actual argument is passed to the function's formal parameter. This means the formal parameter directly refers to the same memory location as the original variable.
Effect on Original Data:
Modifications made to the formal parameter within the function do affect the original variable in the calling scope, as both refer to the same data.
Syntax:
Using the reference operator (&) in the parameter declaration (e.g., void func(int& x)). Alternatively, passing a pointer to the variable allows for similar behavior, where the pointer holds the address of the original variable.

<img width="801" height="393" alt="image" src="https://github.com/user-attachments/assets/4575428a-c9eb-4e84-957a-7d09748d8368" />

## Algorithms
## Conclusion
