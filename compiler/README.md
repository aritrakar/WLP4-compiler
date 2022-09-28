# Structure

- **asm**: MIPS Assembler.
- **wlp4scan**: Scans a WLP4 program and tokenizes the input.
- **wlp4parse**: Takes a scanned WLP4 program and produces a [WLP4I](https://student.cs.uwaterloo.ca/~cs241/wlp4/wlp4i.html) file representing the parse tree for the program.
- **wlp4gen**: Takes a WLP4I file and generates the corresponding MIPS assembly code.
- **linker**: Links two or more [MERL](https://student.cs.uwaterloo.ca/~cs241/merl/merl.html) files together into a single MERL file.
- **WLP4.lr1**: Contains formal rules for the WLP4 language.

# Usage (Linux)

`cat [test_file].wlp4 | ./wlp4scan | ./wlp4parse | ./wlp4gen > [test_file].asm`

or

```
$ chmod u+x run
$ ./run -i [test_file]
```

Try it out with one of the many test WLP4 files in the `tests` directory!
