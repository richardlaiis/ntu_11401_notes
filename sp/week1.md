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

## OS concept
+ Every CPU knows its own ISA (Instruction Set Architecture)
![[Pasted image 20250906193231.png]]
+ micro-architecture: Data path, Control path
![[Pasted image 20250906195247.png]]![[Pasted image 20250906195501.png]]
