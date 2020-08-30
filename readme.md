# SimpleMD: Simple Molecular Dynamics

This is a readme file for a simple molecular dynamics (MD) program 
for Lennard-Jones potential.

## 0. Prerequisites
Only needed is C compiler.

## 1. How to compile and run
If the C compiler on your computer is cc (also common is gcc for Gnu C compiler), type:

cc -O -o md md.c -lm

This will create an executable named md. To run the executable, type:

./md < md.in


## 2. Files
The following files are included in this folder, in addition to this readme file, readme.md.
md.c: Main C program
md.h: Header file for md.c
md.in: Input parameter file (to be redirected to the standard input)
