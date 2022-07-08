# Lecture 2 - Arrays
Quick reminder: _How to make and execute files in C..._

```code file_name.c```\n
```make file_name```\n
```make file_name```

__Preprocessing - "Make" vs Clang__ - "Finds and replaces" the #includes and "copy and pastes" it into the code.
- Clang: The compiler that converts the source code to machine code.
- "Make": Automates this process, and is a useful tool to make things easier for when the code becomes more complicated. It "makes" it all happen.
  - "-o" tells clang to "output" the file... ```clang -o hello hello.c -lcs50```

__Compiling__ - Take code in the computers memory, then converts it into the assembly language.
__Assembling__ - To assemble code is turned into source code, (0's and 1's).
__Linkning__ - The linking command combines all of the different source code (0's and 1's) together, from the different programmers that may be included in a "compiled program".

__Debugging__ - You will always write code contained in bugs. How do you remove a bug? 🐜 🐞 🐛
Diagnose the problem. Utilize "Print" or an equivelent to better understand the problem.

A debugger allows for an in depth walkthrough of code. Step through your code "step by step" by utilizing a debugger. (Rather than repetative "print" statements.

Rubber Duck Debugging? 🦆 - Just talk through your problems when Programming Bugs arrise. Simply hearing yourself can better help you to understand and discern the logic of what could be the problem.

__Types__:
- bool: 1 byte
- char: 8 bytes
- double: 4 bytes
- float: 4 bytes
- int: 4 bytes
- long: 8 bytes
- string: ? bytes

__Memory__ - Data that is taking up some number of Bytes.s
