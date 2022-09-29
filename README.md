# WLP4 Compiler

This repository contains _executables_ for different parts of a compiler written in **C++** for the WLP4 language. WLP4 stands for "Waterloo Language Plus Pointers Plus Procedures" and is a subset of the C language. The formal language specification can be found [here](https://student.cs.uwaterloo.ca/~cs241/wlp4/WLP4.html) and a tutorial can be found [here](https://student.cs.uwaterloo.ca/~cs241/wlp4/WLP4tutorial.html).

The compiler scans a `.wlp4` file, tokenizes it, passes the tokens to a LR(1) parser which generates a WLP4I (WLP4 Intermediate) file. The WLP4I file is then fed into the code generator which then generates corresponding MIPS assembly code and outputs a `.asm` file. Each component can be found in the `compiler` subdirectory.

See `compiler/README.md` for details on how to run the compiler.

If you are interested in the source code for this project, please send an email stating your purpose to aritrakar2002 at gmail.com.
