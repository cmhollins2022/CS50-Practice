# Lecture 2 - Arrays

__Preprocessing - "Make" vs Clang__ - "Finds and replaces" the #includes and "copy and pastes" it into the code.
- Clang: The compiler that converts the source code to machine code.
- "Make": Automates this process, and is a useful tool to make things easier for when the code becomes more complicated. It "makes" it all happen.
  - "-o" tells clang to "output" the file... ```clang -o hello hello.c -lcs50```

__Compiling__ - Take code in the computers memory, then converts it into the assembly language.
__Assembling__ - To assemble code is turned into source code, (0's and 1's).
__Linkning__ - The linking command combines all of the different source code (0's and 1's) together, from the different programmers that may be included in a "compiled program".

__Debugging__ - You will always write code contained in bugs. How do you remove a bug? 🐜 🐞 🐛 
