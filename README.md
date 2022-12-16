# Interpreter for Monty ByteCode files

Monty ByteCode contains opcodes specific to Monty. This is an interpreter for these special opcodes: push, pall, pint, pop, swap, swap, add, nop
Description of repo contents:

bytecode folder ----- holds Monty ByteCode files
monty.h ------------- holds all function prototypes for interpreter
main.c -------------- entry into program

# How to Compile

Usage: ./monty [filename]

$ git clone https://github.com/ace2016/monty
$ cd monty
$ gcc -Wall -Werror -Wextra -pedantic *.c -o monty
$ ./monty bytecodes/000.m
$ ./monty bytecodes/00.m
$ ./monty bytecodes/06.m
$ ./monty bytecodes/07.m
$ ./monty bytecodes/09.m
$ ./monty bytecodes/12.m

# Environment

Language: C (version C89)
OS: Ubuntu 20.04 LTS
Compiler: gcc 4.8.4
Style guidelines: Betty style

# Author
Owhofasa Mobo
