# Part 1

## Boot Sector Identifier

Code for boot Sector Identifier - 

```asm
times 510-($-$$) db 0
db 0x55, 0xaa
```

[Next Part >](https://github.com/Sherry65-code/Creating-an-OS/blob/main/Part%202.md)
