# Uncommon C Pointer Bug: Unexpected Variable Modification
This repository demonstrates a subtle but common error related to pointer usage in C. The code appears to modify a variable indirectly, but it actually leads to an unintended side effect of changing the value of the original variable.

**Bug Description:**
The main function initializes an integer variable 'x' and a pointer 'ptr' that points to the address of 'x'. The value pointed to by 'ptr' is modified, but this unexpectedly changes the value of 'x'.

**Solution:**
The solution explains how to understand and modify the behavior to avoid the unexpected variable modification.

**Learning Points:**
* Understand how pointers and variables interact in C memory management.
* Recognize and avoid unintended side effects of pointer manipulations.
* Learn best practices to write cleaner and more maintainable C code.