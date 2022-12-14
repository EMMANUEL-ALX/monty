0x19. C - Stacks, Queues - LIFO, FIFO

 The Monty language
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

Monty byte code files

Files containing Monty byte codes usually have the .m extension. Most of the industry uses this standard but it is not required by the specification of the language. There is not more than one instruction per line. There can be any number of spaces before or after the opcode and its argument:



The monty program

Usage: monty file
where file is the path to the file containing Monty byte code
If the user does not give any file or more than one argument to your program, print the error message USAGE: monty file, followed by a new line, and exit with the status EXIT_FAILURE
If, for any reason, it’s not possible to open the file, print the error message Error: Can't open file <file>, followed by a new line, and exit with the status EXIT_FAILURE
where <file> is the name of the file
If the file contains an invalid instruction, print the error message L<line_number>: unknown instruction <opcode>, followed by a new line, and exit with the status EXIT_FAILURE
where is the line number where the instruction appears.
Line numbers always start at 1
The monty program runs the bytecodes line by line and stop if either:
it executed properly every line of the file
it finds an error in the file
an error occured
If you can’t malloc anymore, print the error message Error: malloc failed, followed by a new line, and exit with status EXIT_FAILURE.
You have to use malloc and free and are not allowed to use any other function from man malloc (realloc, calloc, …)
Tasks
0. push, pall
Implement the push and pall opcodes.
1. pint
Implement the pint opcode.
2. pop
Implement the pop opcode.
3. swap
Implement the swap opcode.
4. add
Implement the add opcode.
5. nop
Implement the nop opcode.
6. sub
Implement the sub opcode.
7. div
Implement the div opcode.
8. mul
Implement the mul opcode.
9. mod
Implement the mod opcode.
10. comments
Every good language comes with the capability of commenting. When the first non-space character of a line is #, treat this line as a comment (don’t do anything).
11. pchar
Implement the pchar opcode.
12. pstr
Implement the pstr opcode.
13. rotl
Implement the rotl opcode.
14. rotr
Implement the rotr opcode.
15. stack, queue
Implement the stack and queue opcodes.
16. Brainf*ck
Write a Brainf*ck script that prints School, followed by a new line.
17. Add two digits
Add two digits given by the user.
18. Multiplication
Multiply two digits given by the user.
19. Multiplication level up
Multiply two digits given by the user.
Author black🔏🔏🔏🔏✒️ 
EMMANUEL ANAEDOBE
