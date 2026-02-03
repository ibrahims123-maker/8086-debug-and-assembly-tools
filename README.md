# 8086 Assembly Tools (DOSBox + MASM + DEBUG)
This repository contains basic tools for learning 8086 Assembly Programming.
## Tools Included ##

 DEBUG.EXE – Debug and inspect registers/memory
 EDIT.COM – Write assembly code inside DOS
 MASM.EXE – Assemble .ASM files to .OBJ
 LINK.EXE – Convert .OBJ to .EXE

## Requirements ##
Download and install DOSBox:
https://www.dosbox.com/download.php?main=1

## Setup Steps ##
1. Install DOSBox.
2.  Short steps: Open File Explorer →  Go to This PC →  Local Disk (C:) →  Right-click empty space →  New → Folder Name it DOS
3. Copy all files from this repository into C:\DOS
4. Open DOSBox.
5. Type:
   mount c c:\dos
   after that
   c:
   after that
   c:debug
   
## Writing a Program ##
edit add.asm
## Assembling ##
masm add.asm
## Linking ##
link add.obj
## Running ##
add
## Debugging ##
debug add.exe

## basic DEBUG Commands ##
r  - show registers
u  - show instructions
t  - step instruction
d  - dump memory
q  - quit

##Example program##
8bit addition program
a-100
mov al,05
mov bl,03
add al,bl
int 21
check result 
g(memory loction of int 21 in code)
g0106 result it show 


_____________________________________________________________GOOD LUCK______________________________________________________

