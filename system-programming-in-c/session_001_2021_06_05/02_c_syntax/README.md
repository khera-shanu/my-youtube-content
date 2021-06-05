### Programming in C

#### Classic hello world program from K&R (Brian Kernighan and Dennis Ritchie)

```c
#include <stdio.h>
main()
{
    printf("hello, world\n");
}
```

#### C language release versions
`
  K&R  1978-02-22
  C89  1989-12-14
  C90  1990-12-20
  C95  1995-03-30
  C99  1999-12-16
  C11  2011-12-15
`

#### Executing C code
- `gcc <file.c> -o <executable_name>`
- Executing old C code like K&R using `-std=<value>` flag in GCC.

#### Variable types in C
- local
- global

#### Storage classes in C
- static
- auto
- extern
- register

#### Data types in C
- Numbers
  - Integers and long (signed and unsigned) - 2's complement representation
  - float and double
- Character
- Pointer
- Array
- String literals, and .rodata / immutable

#### Operations in C - mostly standard
- `sizeof`
- `*` and `&` for dereference and address


#### Some functions
- `printf`
- `scanf`

#### Control flow
- If else
- Loops
- Switch case
- Jump

#### Functions and return types
- main as exception to return
- getting return value of main

#### C memory model
- Dynamic memory
- Functions and stack frames

#### C compilation process
```bash
gcc -E <file.c> # Preprocessing
gcc -S <file.c> # C to Assembly
gcc -c <file.c> # C to binary object file, try hexdump this .o file

# Linking -> loading -> execution
```
