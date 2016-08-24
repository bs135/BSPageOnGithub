---
layout: post
title:  "Building AVR Toolchain for Windows"
categories: note
---

## Introduction

To compiling a avr source on windows, you can make either way:

* Install [Atmel Studio][Atmel Studio]: This way is very simple. [Atmel Studio][Atmel Studio] include almost everything: awesome IDE, toolchain for compiling, support debugger, downloader... But [Atmel Studio][Atmel Studio] only support for Windows. So, if you have an AVR-open-source written on linux, you will have trouble to compile it.

* Install AVR Toolchain for Windows

## Building AVR Toolchain for Windows

#### Installation requirements:

* [MinGW][MinGW]: Minimalist GNU for Windows.
	* It is a native Windows port of the GNU Compiler Collection (GCC), a minimalist development environment for native Microsoft Windows applications. 
	* Download and Install from [Sourceforge](https://sourceforge.net/projects/mingw/files/latest/download?source=files)
	* Install necessary MSYS packages: msys-base, msys-make, msys-core, msys-bash.
	* For testing, you can type command `make --version` in a Window Command Prompt.
* [AVR Toolchain][AVR Toolchain] for Windows
	* Download
		* [Atmel AVR 8-bit Toolchain for Windows](http://www.atmel.com/tools/ATMELAVRTOOLCHAINFORWINDOWS.aspx)
		* [Atmel 32-bit Toolchain for Windows](http://www.atmel.com/tools/ATMELAVRTOOLCHAINFORWINDOWS.aspx)
	* Install: extract downloaded packages to you disk, eg.:
		* `C:\atmel\avr8-gnu-toolchain`
		* `C:\atmel\avr32-gnu-toolchain`
	* Update PATH environment variable to these folder:
		* `C:\atmel\avr8-gnu-toolchain\bin`
		* `C:\atmel\avr32-gnu-toolchain\bin`
	* For testing, you can type command `avr-gcc --version` or `avr32-gcc --version` in a Window Command Prompt.

## References
* [Atmel Studio][Atmel Studio]
* [MinGW][MinGW]
* [AVR Toolchain][AVR Toolchain]

[Atmel Studio]: http://www.atmel.com/Microsite/atmel-studio
[MinGW]: http://www.mingw.org/
[AVR Toolchain]: http://www.atmel.com/tools/ATMELAVRTOOLCHAINFORWINDOWS.aspx