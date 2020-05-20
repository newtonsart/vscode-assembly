# visual-studio-assembly
[![contributions welcome](https://img.shields.io/static/v1.svg?label=Contributions&message=Welcome&color=0059b3&style=flat-square)](https://github.com/newtonsart/visual-studio-assembly/blob/master/CONTRIBUTING.md)&nbsp;

Assembling and debugging assembly in Visual Studio Code
## Demo

![Running](https://raw.githubusercontent.com/newtonsart/visual-studio-assembly/master/Screenshotvs.png)

## Installing

### Visual Studio Code
I guess you already have this installed...
If not, go [here](https://visualstudio.microsoft.com/downloads/)
### GDB
Install your distro gdb package:

Archlinux
```
sudo pacman -S gdb
```
Debian
```
sudo apt install gdb
```
Fedora
```
yum install gdb
```
### [GDB Debug](https://marketplace.visualstudio.com/items?itemName=DamianKoper.gdb-debug&ssr=false#qna) Extension
Press ``ctrl + p`` inside of visual studio code and paste the following command:
```
ext install DamianKoper.gdb-debug
```
### Json files
You'll need to append the [tasks.json](https://github.com/newtonsart/visual-studio-assembly/blob/master/tasks.json) file and the [launch.json](https://github.com/newtonsart/visual-studio-assembly/blob/master/launch.json) files to your config files.

### Optional
- [ASM Code Lens](https://marketplace.visualstudio.com/items?itemName=maziac.asm-code-lens) for syntax highlighting, completions and more.
- [x86 Instruction Reference](https://marketplace.visualstudio.com/items?itemName=whiteout2.x86) for useful information about x86 instructions

## Supported architectures
The default tasks.json file allows you to assemble x86_32 asm files, but you can edit the shell command to assemble and link for any architecture you want. 
