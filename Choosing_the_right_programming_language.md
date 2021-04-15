# Choosing the right programming language.

There are hundreds of programming languages available out there... Javascript, Python, Java, Rust are the some of the popular ones, but how to choose one to start with?

This article explains what I think are some of the most important points to consider before choosing a programming language.

But to understand which programming language to choose,
first we will have to understand what it is.

# Programming language

A programming language is a language which the compiler or an interpreter understands.But wait what are compilers and interpreters?

A computer cannot understand human readable code, but a compiler or an interpreter understands.These two basically convert human readable code into computer readable code.
For a brief description read this (hyperlink for compiler vs interpreter article)

The following are some points for choosing the right programming language.

When you write a piece of code, your biggest concerns should be **speed, portability, syntax difficulty, security, job opportunities** and **cross-platform compatibility.*

# Speed
Everybody wants their code to be executed quickly. Speed is a point which is very important when it comes to larger projects.

[This](github.com/drujensen/fib) is the test conducted by a GitHub user which calculates the time needed for the execution of a nth [Fibonacci](https://en.wikipedia.org/wiki/Fibonacci_number) number.

The [results](https://github.com/drujensen/fib#natively-compiled-statically-typed) shows that low-level and compiled languages take much less time than those who are high-level and interpreted.

Compiled languages such as C, C++, Rust, Golang all complete the execution in under 10 seconds.
But interpreted languages such as lua and Python3, take 495 and 598 seconds respectively.

# Security
Security is an important criteria as it is always a large concern when it comes to dealing with data.

But, what is an insecure programming language? An insecure programming language is a programming language which is vulnerable. Or in simple words, the user's system resources can easily be leaked **without** authorization by the user.

These are the most insecure programing languages: C, Java, JavaScript, Python, Ruby, PHP, C++ in the same order.

Brief explanation on insecure programming languages can be found here(hyperlink for https://www.zdnet.com/article/which-are-the-most-insecure-programming-languages/)

# Portability
The only reason that I feel why C and C++ are still popular today is because of their portability.
**Compiled languages** are more portable than **interpreted languages**.

In compiled languages you can easily compile code in a binary executable(hyperlink on executable's wikipedia)(```.exe```), which can be run by users without installing the actual programming language you have written the code in.

Whereas, in interpreted languages you cannot interprete code into a binary executable easily.*You can convert python3 and javascript code in executables, but it does not work all the time.*

# Cross-platform compatibility
Cross-platform compatibility means having the same executable in different platforms (for more: link to Cross-Platform Article).
Compiled languages have more issues in Cross-platform compatibility while interpreted languages work well in different platforms.
While taking executables into consideration, the OS and it is dependencies com into the picture while running the code and that's why this executable cannot be run in different platforms.
So, the executable written on ```Windows x32``` will not work on ```Windows x64``` and also on any unix systems.
Whereas, the interpreted languages do not have this issue as the interpreter installed on the user's machine gives instructions to the machine's processor.
_This can be done only if a runtime environment is present on the user's machine_

# Syntax difficulty
I feel that if you are learning your first programing language, the syntax(hyperlink for syntax wikipedia) should be an easy one.

It does not matter if it is a compiled language or an interpreted one if you are developing software at the basic level.

Some of the languages having the easiest syntaxes are Python, lua, JavaScript, Ruby, Golang, Rust and are great for being the first language you learn.
Only after, you know a certain concepts, I feel you should go for learning languages like Java, C#, R, etc.

# Job Opportunities
If you are learning programming for getting a job, this criteria is for you. 
If you want to get a job then what is the advantage in learning which is outdated or not in demand?

You should research about what is the most demanded language in your area, and go for learning that language first.
You can find some of the most popular and demanded languages in the world [here](https://towardsdatascience.com/top-10-in-demand-programming-languages-to-learn-in-2020-4462eb7d8d3e)

_Spoiler Alert: The programming language having the most job opportunities worldwide is Python3_

If you are a skilled programmer and you want to add a new language to your portfolio, find where the industry is headed. 
The StackOverflow developer surveys are very accurate and show the state of the industry. 

If you are going to ask me today which programming language should you learn, I would say Python, JavaScript, Golang, Dart and Rust should be the ideal choice.

Happy debugging,

Engrafa team
