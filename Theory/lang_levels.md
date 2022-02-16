# What's a High and Low Level Language?

Languages come in different levels, most notably high and low ones. Although seemingly complicated, the differences between these languages are mostly simple, but let's start at the lower end.

## Low Level

Low level languages typically interface directly with memory (RAM) or the CPU. Assembly languages always fall under this category as they force the programmer to make direct use of memory, CPU registers, and CPU operation codes (which won't be heavily explained here). Other languages such as C (and oftentimes C++, Rust, et al.) may fall under this category as well because of the existence of **pointers**. Pointers allow a programmer to access memory directly instead of using higher level abstractions. The existence of these objects, however, does not force a language to be low level as they can easily be bypassed (through functions and structures in C, smart pointers in C++, etc). It is only the direct use of pointers that typically make a language low level. These languages are, therefore, almost always compiled.

## High Level

As opposed to low level languages, higher level languages, such as Python, Java, JavaScript, and others, don't allow the programmer to access memory or the CPU directly. Instead, these languages provide **abstractions** such as *classes* and *garbage collection* which allow the language to do the heavy lifting itself. Higher level languages tend to be interpreted as this allows the interpreter to deal with everything and allows the program to "sit back and relax".

### Esoteric Languages?

Esoteric languages typically fall under the high level classification. Languages such as [Malbolge](https://esolangs.org/wiki/Malbolge) and [l33t](https://esolangs.org/wiki/l33t) are very high level languages as they severely limit the abilities of programs written in them and provide complex abstractions for every operation. These languages also oftentimes cause the programmer to compute calculations on their own to simply write a program.

A number of esoteric languages do limit the programmer to using only a pointer to a preallocated block of memory. However, since this memory is not directly related to a computer's actual memory, it can't be considered as directly interfacing with real memory.

## In Short:

Low level languages allow a program to use memory directly. High level languages don't. Assembly, C, and C++ can all be examples of low level languages and Python, Java, JavaScript, and many esoteric languages are examples of high level languages.

---

Happy debugging,

Raniconduh | Engrafa Team
