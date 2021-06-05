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
- K&R  1978-02-22
- C89  1989-12-14
- C90  1990-12-20
- C95  1995-03-30
- C99  1999-12-16
- C11  2011-12-15

#### Executing C code
- `gcc <file.c> -o <executable_name>`
- Executing old C code like K&R using `-std=<value>` flag in GCC.

#### Variable types in C
- local
- global

#### Storage classes in C

![Storage classes in C]( https://github.com/khera-shanu/my-youtube-content/raw/main/system-programming-in-c/images/c_storage_classes.png "Storage classes in C")

- static
- auto
- extern
- register

#### Data types in C
- Numbers
  - Integers and long (signed and unsigned) - 2's complement representation
  - float and double
- Character - String literals, and .rodata / immutable
- Array
- Pointer

#### C compilation process
![C compilation process]( https://github.com/khera-shanu/my-youtube-content/raw/main/system-programming-in-c/images/c_compilation_steps.png "C compilation process")
```bash
gcc -E <file.c> # Preprocessing
gcc -S <file.c> # C to Assembly
gcc -c <file.c> # C to binary object file, try hexdump this .o file

# Linking -> loading -> execution
```

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
![C memory model]( https://github.com/khera-shanu/my-youtube-content/raw/main/system-programming-in-c/images/c_memory_layout.png "C memory model")
- Dynamic memory
- Functions and stack frames
