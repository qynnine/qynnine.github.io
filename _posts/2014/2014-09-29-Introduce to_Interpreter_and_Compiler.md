---
layout: post
title: Introduce to Interpreter and Compiler
description: 

---

## Interpreter
There are two major approaches to implementing programming languages, compilers, and interpreters. So, what does an interpreter do?

<img src="{{ site.img_url }}/2014/compilers.png" alt="compiler" width="400px" />

Well, from the above picture, an interpreter is a box. It takes two inputs, your program and whatever data that you want to run the program on. And it produces the output directly. Meaning that it doesn't do any processing of the program before it executes it on the input, So you just write the program, and you invoke the interpreter on the data, and the program immediately begins running. 

And so, we can say that the interpreter is online, meaning it the work that it does is all part of running your program.

## Compiler
Now a compiler is structured differently. So, we can draw a picture here. 

<img src="{{ site.img_url }}/2014/interpreters.png" alt="interpreters" width="400px" />

The compiler takes as input just your program. And then it produces an executable. This executable is another program, might be assembly language or bytecode. It could be in any number of different implementation languages. But now this can be run separately on your data. And that will produce the output.

So in this structure the compiler is offline, meaning that we pre-process the program first. The compiler is essentially a pre-processing step that produces the executable, then we can run that same executable on many different inputs or data sets without having to recompile or do any other processing of the program. 





