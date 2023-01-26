# vscode-assembly
[![contributions welcome](https://img.shields.io/static/v1.svg?label=Contributions&message=Welcome&color=0059b3&style=flat-square)](https://github.com/newtonsart/visual-studio-assembly/blob/master/CONTRIBUTING.md)&nbsp;
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

Assembling and debugging assembly in Visual Studio Code

Currently it supports:
- Assembly x86_32 Intel and AT&T syntax
- Assembly x86_64 Intel and AT&T syntax
- Assembly x86_32 with C libraries
- Assembly x86_64 with C libraries

## Demo

![Running](https://raw.githubusercontent.com/newtonsart/vscode-assembly/master/vscode.png)

## Installing

### Visual Studio Code
I guess you already have this installed...
If not, go [here](https://code.visualstudio.com/)
### GDB
Install your distro gdb package:

Archlinux
```
sudo pacman -S gdb gcc binutils
```
Debian
```
sudo apt install gdb gcc binutils
```
Fedora
```
yum install gdb gcc binutils
```
### [GDB Debug](https://marketplace.visualstudio.com/items?itemName=DamianKoper.gdb-debug&ssr=false#qna) Extension
Press ``ctrl + p`` inside of visual studio code and paste the following command:
```
ext install DamianKoper.gdb-debug
```
### Json files
You'll need to put the [.vscode](https://github.com/newtonsart/vscode-assembly/tree/master/.vscode) folder in your visual studio workspace

### How to allow breakpoints
Just follow the next steps: VS->Settings->Debug and change "debug.allowBreakpointsEverywhere" to true

### Optional
- [ASM Code Lens](https://marketplace.visualstudio.com/items?itemName=maziac.asm-code-lens) for syntax highlighting, completions and more.
- [x86 Instruction Reference](https://marketplace.visualstudio.com/items?itemName=whiteout2.x86) for useful information about x86 instructions

## License

vscode-assembly is licensed under the GNU General Public License v3.0

