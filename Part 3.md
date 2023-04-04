# Part 3

## Compiling and running code

- I recommend you use linux cause' assembly will be a mess in windows.
- So if you are in Linux, then follow with me - 
  - First Install `NASM` and `qemu`
  
    For Ubuntu
  
      ```bash
      sudo apt install nasm qemu-system-x86
      ```
  
    For Arch
  
      ```bash
      sudo pacman -S nasm qemu
      ```
  
   - Now compile your program using
  
      ```bash
      nasm <your program name> -o <any name for your program>.iso
      ```
  
      for example
  
      ```bash
      nasm ./hello.asm -o hello.iso
      ```
  
   - Then run it in your virtual machine
  
      ```bash
      qemu-system-x86_64 ./hello.iso
      ```
  
  And its **DONE**
  
  [Next Page >](https://github.com/Sherry65-code/Creating-an-OS/blob/main/Part%204.md)
