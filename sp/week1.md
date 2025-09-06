```bash
/usr/bin/time -p executable_or_command
# or
time -p executable_or_command
```
The command can measure the execution time in user mode and system mode. (`-p` means proportion)

## gdb
The following can add breakpoint before first function call.
```
b <function_name>
```

Stop running the code
```
kill
```

## Makefile

```
gcc -c
```
Compile or assemble the source files, but do not link. The linking stage simply is not done. The ultimate output is in the form of an object file for each source file.
```
gcc -Wall main.c -o main
```
This enables all the warnings about constructions that some users consider questionable, and that are easy to avoid (or modify to prevent the warning), even in conjunction with macros.
## OS concept
+ Every CPU knows its own ISA (Instruction Set Architecture)
+ micro-architecture: Data path, Control path
## course slide (screenshot)
https://drive.google.com/drive/folders/1NYrvnYXX1VeVUF-_PwQimv49yaINVIoe?usp=sharing
