# pointer-basics
## Contents
- [Aim](#aim)
- [Software Used](#software-used)
- [Theory](#theory)
  * [Definition](#definition)
  * [Features](#features)
  * [Drawbacks](#drawbacks)
- [Algorithms](#algorithms)
- [Conclusion](#conclusion)

## Aim 
To use basic pointers.

## Software Used 
VS Code

## Theory
**Definition**
<br>
A pointer is a variable that stores the memory address of another variable. It does not hold any actual data value like a normal variable, instead holds the location where the data is stored in memory. Pointers allow for efficient array and memory management, and can be used to directly manipulate memory.
Using pointers significantly improves performance for repetitive operations, like traversing iterable data structures (e.g. strings). In particular, it is often much cheaper in time and space to copy and dereference pointers than it is to copy and access the data to which the pointers point.  
The basic syntax to define a pointer is:
```cpp
int a = 5;
int *ptr = &a;
```
<br>  

> Visual Representation of memory address:
<br>
