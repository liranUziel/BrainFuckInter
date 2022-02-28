# Brain Fuck
<img src="brainf.png" width="50">

Simple **c** base interpeter

base onf *Urban Müller* esoteric programming language
## Supported Commands

| Character | README |
| ------ | ------ |
| > | Increment the data pointer (to point to the next cell to the right). |
| < | Decrement the data pointer (to point to the next cell to the left).  |
| + | Increment (increase by one) the byte at the data pointer.            |
| - | Decrement (decrease by one) the byte at the data pointer.            |
| . | Output the byte at the data pointer.                                 |
| [ | If the byte at the data pointer is zero, then instead of moving the instruction pointer forward to the next command, jump it forward to the command after the matching ] command. |
| ] | 	If the byte at the data pointer is nonzero, then instead of moving the instruction pointer forward to the next command, jump it back to the command after the matching [ command. |
## Installing 
All need is to complie the code using any complie.

example 
**gcc**
```sh
gcc brainf.c -o brainf.exe
```
## Runing the code
Can run any file in this version. in later version will support only bf files
```sh
brainf code.bf
```

## Code snipit
This project include **hello world** code example
```
>++++++ a{1} = 6
a{0} = 0
[<++++++++++>-] a{0} plus 10 a{1} minus 1
<+++++ letter = a{0} plus 5

set a{i} to letter, a{i} plus letter minus 'A'
+++++++
. print a{0} = 'A' 65

> a{1} = 0
>+++++++++ a{2} = 9
[<++++++++++>-] a{1} plus 10 a{2} minus 1
<+++++++ a{1} plus 7
set a{i} to letter, a{i} plus letter minus 'A'
++++
.
> a{1} = 0
>+++++++++ a{2} = 9
[<++++++++++>-] a{1} plus 10 a{2} minus 1
<+++++++ a{1} plus 7
set a{i} to letter, a{i} plus letter minus 'A'
+++++++++++
.
> a{1} = 0
>+++++++++ a{2} = 9
[<++++++++++>-] a{1} plus 10 a{2} minus 1
<+++++++ a{1} plus 7
set a{i} to letter, a{i} plus letter minus 'A'
+++++++++++
.
> a{1} = 0
>+++++++++ a{2} = 9
[<++++++++++>-] a{1} plus 10 a{2} minus 1
<+++++++ a{1} plus 7
set a{i} to letter, a{i} plus letter minus 'A'
++++++++++++++
.
> a{1} = 0
>+++ a{2} = 3
[<++++++++++>-] a{1} plus 10 a{2} minus 1
<++ a{1} plus 2
.
> a{1} = 0
>+++++++ a{2} = 9
[<++++++++++>-] a{1} plus 10 a{2} minus 1
<+++++ a{1} plus 7
set a{i} to letter, a{i} plus letter minus 'A'
++++++++++++
.
> a{1} = 0
>+++++++++ a{2} = 9
[<++++++++++>-] a{1} plus 10 a{2} minus 1
<+++++++ a{1} plus 7
set a{i} to letter, a{i} plus letter minus 'A'
++++++++++++++
.
> a{1} = 0
>+++++++++ a{2} = 9
[<++++++++++>-] a{1} plus 10 a{2} minus 1
<+++++++ a{1} plus 7
set a{i} to letter, a{i} plus letter minus 'A'
+++++++++++++++++
.
> a{1} = 0
>+++++++++ a{2} = 9
[<++++++++++>-] a{1} plus 10 a{2} minus 1
<+++++++ a{1} plus 7
set a{i} to letter, a{i} plus letter minus 'A'
+++++++++++
.
> a{1} = 0
>+++++++++ a{2} = 9
[<++++++++++>-] a{1} plus 10 a{2} minus 1
<+++++++ a{1} plus 7
set a{i} to letter, a{i} plus letter minus 'A'
+++
.
```


