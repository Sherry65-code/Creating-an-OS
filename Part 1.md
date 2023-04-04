# Part 1

## Boot Sector Identifier

Code for boot Sector Identifier - 

```asm
times 510-($-$$) db 0
db 0x55, 0xaa
```
