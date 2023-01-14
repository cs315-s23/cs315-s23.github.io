---
layout: assignment
due: 2023-02-06 23:59:59 -0800
github_url: https://classroom.github.com/a/piZ4HSTb
---

## Requirements

1. You will develop C and RISC-V assembly language implementations of the following arithmetic problems. 
1. Your executable must be compiled with a Makefile
1. Before you add files to your repo, do a `$ make clean` so you don't add/commit build products like executables or .o files
1. We will test the labs using autograder

**add4:** Adds four 32-bit integers together and returns the result. Example:

    $ ./add4 1 2 3 4
    C: 10
    Asm: 10

**quadratic:** Runs the quadratic equation (ax^2 + bx + c) on the 32-bit integers x, a, b, c and returns the result. Example:

    $ ./quadratic 4 3 2 1
    C: 57
    Asm: 57

**min:** Calculates the smaller of two 32-bit integers and returns its value. Example:

    $ ./min 2 3
    C: 2
    Asm: 2

## Given

We will demonstrate a framework for compiling C and assembly language source files, and calling assembly language functions from C

## Rubric

1. Your lab will receive the score indicated by the autograder
1. To get the test cases, `git pull` in the tests repo