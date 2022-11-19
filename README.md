# LPCC-Assignment

A Reference for Lex Specifications

Being a programmer requires all-around knowledge of a lot of subjects. One of the most underrated among these would definitely be compiler design. Knowing what goes behind the scenes when a program is run can help one understand the source of errors and warnings (which is definitely a big help since it helps optimize the time taken to run a program successfully). Today, we’re going to be looking at one of the steps performed by a compiler before it executes the program: it’s called lexical analysis. We will understand what does a lexical analyzer do? We have also included a simple lexical analyzer program in C++, which should help you learn about how a compiler functions behind the scenes.
What is a Compiler?

Before moving to lexical analysis in C++, we need to have a basic understanding of a compiler.

Most of the programs we type in are in English (or some other language). A computer cannot understand English; it can interpret only a stream of 1’s and 0’s. In other words, binary is the only language comprehensible to a computer. Hence, it is necessary to convert these “high-level” language programs to binary before the computer can understand the instructions. That is exactly what a compiler and an interpreter are used for. They make our programs comprehensible to the computer.

Despite performing the same functions, compilers and interpreters are slightly different by nature. A compiler is normally quite huge in size, while an interpreter is considerably smaller and occupies fewer system resources. A compiler converts the entire program to binary codes at once and then executes it. If there is an error in any part of the code, the program won’t give any output. However, an interpreter converts the program to binary line-by-line while executing each line it has converted. This ensures that some output is always given before it comes across an error. As is already evident, a compiler is much faster than an interpreter. There are some more differences between them.

Most programming languages use either a compiler or an interpreter under the hood for conversion to binary code (also called “machine language”). C++ uses a compiler, while Python uses an interpreter. Some languages like Java use both. You can also check our online compiler for your programming needs.

he definition section can include the literal block, definitions, internal table declarations, start conditions, and translations. (There is a section on each in this reference.) Lines that start with whitespace are copied verbatim to the C file. Typically this is used to include comments enclosed in “/*” and “*/”, preceded by whitespace.
