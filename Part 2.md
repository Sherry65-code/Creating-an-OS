# Part 2

## Learning Assembly Syntax

- Assembly uses registers instead of RAM which enables it to function extremly fast. Read [this page](https://www.tutorialspoint.com/assembly_programming/assembly_registers.htm#) for explaination.
- `mov` is used to move something from one place to another.
- `add` & `sub` are some mathematical operations.
- `cmp` is used to compare two values.
- `jmp` is used to jump to another places in code.
- `jne` & `je` are some common comparison jump statements.
- `times` refers for loops.
- `hlt` is used to halt a program.
- `0x10` are some registers that perform specific functions.

Learn assembly from [here](https://www.tutorialspoint.com/assembly_programming/index.htm).

- A program in assembly to say hello world.

  ```asm
  mov ah, 0x0e
  mov al, 'H'
  int 0x10
  mov al, 'e'
  int 0x10
  mov al, 'l'
  int 0x10
  int 0x10
  mov al, 'o'
  int 0x10
  mov al, ' '
  int 0x10
  mov al, 'W'
  int 0x10
  mov al, 'o'
  int 0x10
  mov al, 'r'
  int 0x10
  mov al, 'l'
  int 0x10
  mov al, 'd'
  int 0x10
  mov al, '!'
  int 0x10
  times 510-($-$$) db 0
  db 0x55, 0xaa
  ```
  
  To run this program see the next part.
  
  [Next Page >](https://github.com/Sherry65-code/Creating-an-OS/blob/main/Part%203.md)
