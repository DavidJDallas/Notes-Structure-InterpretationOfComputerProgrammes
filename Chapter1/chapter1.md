##

Computional processes are abstract things that manipulate data. The evolution of a process is direct by programmes which are patterns of rules. 

The lisp language is chosen here because it posses unique features that make it good for studying programming constructs and data structures. 
Lisp processes - procedures - can themselves be represented and manipulated as Lisp data. 

## 1.1 Elements of Programming

A language serves as a framework within which we organize our ideas about processes. Every powerful language has 3 mechanisms for accomplishing this:

- Primitive Expressions.
The simplest entities the language is concerned with

- Means of Combination
Compound elements are built from simpler ones

- Means of abstraction
Compound elements can be named and manipulated as units. 

Data is stuff that we want to manipulate, and procedures are descriptions of the rules for manipulating the data. 

### 1.1.2 Naming and Environment

A critical part of a programming language is the means it provides for using names to refer to computational objects. The name identifies a variable whose value is the object. 

Defining a variable as an expression, whether this be a function, class, data structure , or just a number, is a means of abstraction. We abstract away complexity behind the scenes and we present something far simpler. 

Abstraction is crucial: complex programmes are constructed by building, step-by-step, computational objects of increasing complexity. 

The fact that languages can associate values with symbols and later retrieve them means that the interpreter must maintain some sort of memory that keeps track of this. This memory is called the environment. 