## Foreword

This gives a general overview of computer programming, it's importance and what it is. Much of it is a certain type of philosophical contemplation on computers and programming that isn't of interest to me. For instance: 

`Every computer program is a model, hatched in the mind, of a real or mental process` pxiii

`The source of the exhilaration associated with computer programming is the continual unfolding within the mind and on the computer of mechanisms expressed as programs and the explosion of perception they generate` pxiv.

This could be true, or it could not. Problems with Logical Positivism and it's undeniable decline put to one side, the verification principle advocated by several prominent members seems particularly suitable here: meaning - semantic content - of a proposition is determined by its ability to be empirically verified. This statement seems to not be so. 

There is a brief discussion of LISP, which is the central language used for examples in this book, so it's worth saying a little bit about this:

### Lisp

Originally appearing in 1960 by John McCarthy, Lisp was a staple language of the Hacker community. It's the second oldest high-level programming language that is still in common use, with the oldest being Fortran. It's a dynamically typed language and a strongly typed language. Recall that dynamic typing contrasts with static typing, and strongly typed contrasts with weakly typed. 

Dynamic typing vs static typing:

In dynamic typing, the type is inferred at runtime. Types are attached to values at run-time, and an attempt to mix values of diff types can cause a run-time error. Statically typed languages are explicitly stated. 

Weak vs strong typing:

Although apparently no universally regarded clear definition, weakly typed seems to mean something like implicit conversion or implicit casting is available via some sort of loophole in the language. 

Note that there's an important difference between run time and compile time. Compile time refers to the phase when the source code of a programme is translate into machine code or an intermediate code by the compiler. Run time is the phase *after* the programme has been compiled and is then executed by the CPU. Thus compile-time erros occur during compilation and run-time errors occur during run-time. 


Languages such as Racket and Clojure are Lisp dialects. 

Lisp pioneered many ideas in CS, inc tree data structures, automatic storage management, dynamic typing, conditionals, higher-order functions, recursion, and self-hosting compiler. 

There includes general thoughts on programmes as they grow in size:

`As programs get large and complicated... the adequacy, consistency and correctness of the specifications themselves become open to doubt, so that complete formal arguments of correctness seldom accompany large programs`. (pxiv)