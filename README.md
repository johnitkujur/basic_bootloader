Installing Dependencies

1. Qemu - x86 emulator needed to test our bootloader
   sudo apt install qemu qemu-system-x86

2. open watcom - 16 bit compiler to compile our c files
   clone and install it from open-watcom github

To run
1. make
2. qemu-system-i386 -fda build/main.img
