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
### Swapping numbers using Call by Value
1. Start.

2. Input two numbers a and b.

3. Call swap(x, y) (values passed).

4. Swap occurs inside function but does not affect original variables.

5. Print values (remain unchanged).

6. End.
### Swapping numbers using call by reference 
1. Start.

2. Input two numbers a and b.

3. Use a function swap(&x, &y) with references.

4. Store x in temp.
   
5. Assign y to x.

6. Assign temp to y.

7. Print swapped values (original variables get swapped).

8. End.
### Reversing a string
1. Start.

2. Input a string.

3. Count its length.

4. Swap characters from start and end moving towards the center.

5. Print the reversed string.

6. End.
### Salary hike 
1. Start.

2. Input: years completed, research projects, new research projects, company profit.

3. Initialize conditions_met = 0.

4. Check each condition:

5. If years > 1 → increment conditions_met.---If research projects ≥ 1 → increment.---If new projects ≥ 1 → increment.---If profit > 100000 → increment.

6. If conditions_met ≥ 3:

7. Input current salary.

8. Increase it by 20% (using bonus function).

9. Print new salary.

10. If conditions not met → Print "Not eligible for salary hike".

11. End.
## Conclusion
We learnt to use pointers in different types of operations . We learnt about 'call by refernce ' and 'call by value' methods .
