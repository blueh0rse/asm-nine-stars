# Learning

## Assembly

### Nine Stars

This code displays 9 times the `*` char.

To assemble the program:

````bash
nasm -f elf ninestars.asm
````

To link the object file and create an executable file:

````bash
ld -m elf_i386 -s -o ./NineStars ninestars.o
````

To execute it:

````bash
$ ./NineStars 
Displaying 9 stars
*********
````
