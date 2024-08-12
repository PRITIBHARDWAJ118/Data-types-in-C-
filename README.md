# Data types in C++ 
## AIM: This repository contains information about the basic data types in C++ and their respective sizes. 
## Theory:
Primitive data types are the most fundamental data types that C++ offers. They serve to specify the kind of variable or return value of a function. In C++, the primary primitive data types are:
1. int: Used to store integers.
2. float: Used to store single-precision floating-point numbers.
3. double: Used to store double-precision floating-point numbers.
4. char: Used to store single characters.
5. bool: Used to store boolean values (true or false).
6. string: Used to store sentences(strings).
7. long:  Used to store larger integer values compared to the int data type.
8. unsigned integer: The unsigned int data type is a variation of the int data type that only stores non-negative integer values.
### sizeof() function:
In C++, the sizeof function is used to determine the size (in bytes) of a data type or object. It returns a value of type size_t, which represents the size of the type or object in bytes.
### Storage class:
 Storage classes in C++ define the scope (visibility) and lifetime of variables or functions within a C++ program.
1. auto: Deduces the type of the variable at compile-time. It is commonly used in modern C++ to let the compiler infer the type.
2. register: Suggests to the compiler to store the variable in a CPU register for faster access, though it's only a suggestion and not a directive.
3. static: Limits the visibility of a variable to the file, function, or block where it is defined, while also preserving its value between function calls.
4. extern: Indicates that the variable or function is defined in another file or later in the same file, facilitating sharing of variables across multiple files.
## Explanation of the code:
1. sizeof(int): Returns the size of an int type in bytes.
2. sizeof(float): Returns the size of a float type in bytes.
3. sizeof(double): Returns the size of a double type in bytes.
4. sizeof(char): Returns the size of a char type in bytes.
5. sizeof(string): Returns the size of a string type. Note that sizeof(string) may not give the expected result because string is a class, and sizeof returns the size of the object, not the size of its contents.
6. sizeof(unsigned int): Returns the size of an unsigned int type in bytes.
7. sizeof(long): Returns the size of a long type in bytes.
8. sizeof(bool): Returns the size of a bool type in bytes.
## Output:
The output of the code is:
![Screenshot 2024-08-12 062728](https://github.com/user-attachments/assets/1f2271e9-7fe3-4ea5-be59-4d16be85158e)
![Screenshot 2024-08-12 065409](https://github.com/user-attachments/assets/70170bd9-ab85-495d-b9ab-0b7b3efb1f2c)

