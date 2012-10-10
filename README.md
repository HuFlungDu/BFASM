BFASM
=====

A 65c816 assembler written entirely in the brainfuck language

This was a school project I created as part of a study on turing machines. Besides this part of the project there was also a multi tape turing machine emulator and BF interpreter created in a turing machine.

Possibly the third longest brainfuck program in existence, after Jon Ripley's "Lost Kingdom" and "Adv" games, though those have a lot more printing than this does, so, control logic wise, this may be the longest.

This is not a fully portable BF program; it requires a compiler that uses an unsigned byte cell size, and it will not compile on the original BF compiler because it creates a buffer overflow, because the program is too long.

Usage: BFASM < File.asm > File.bin
