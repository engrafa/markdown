# Choosing the right programming language

There are hundreds of programming languages available out there... Javascript, Python, Java and Rust are the some of the popular ones, but how to choose one to start with?

This article explains what I think are some of the most important points to consider before choosing a programming language.

But to understand which programming language to choose,
first we will have to understand what it is.

## Programming language

A programming language is a language you use to write "computer programs". A program is basically a set of instructions and data you give to your computer (for example, a calculator app tells the computer to calculate 2+2 and then it gives you the result).

The following are some points for choosing the right programming language.
- Application
- Speed
- Security
- Portability
- Cross-platform compatibility
- Syntax Difficulty

### Application
Certain programming languages are more suited for a particular field. For example, if you want to do Machine Learning (subset of AI), you would most probably use something like Python and not C.

### Speed
Everybody wants their code to be executed quickly. Speed is an important criteria when it comes to [time critical applications](https://www.sciencedirect.com/science/article/pii/S1877050915030653)

[This](https://github.com/drujensen/fib) is the test conducted by a GitHub user which calculates the time needed for the execution of a nth [Fibonacci](https://en.wikipedia.org/wiki/Fibonacci_number) number.

The [results]() shows that low-level and compiled languages take much less time than high-level and interpreted ones.

Compiled languages such as C, C++, Rust, Golang all complete the execution in under 10 seconds.
But interpreted languages such as lua and Python3, take 495 and 598 seconds respectively.

You should also keep in mind that using a fast language is not enough, if your implementation is bad, your program will perform slowly, no matter which language you use.

### Security
Security is an important criteria as it is always a big concern when it comes to dealing with data.

But, what is an insecure programming language? An insecure programming language is a programming language which is vulnerable. Or in simple words, the user's system resources can easily be leaked **without** authorization by the user.

These are the most insecure programing languages: C, Java, JavaScript, Python, Ruby, PHP, C++ in the same order.

Brief explanation on insecure programming languages can be found [here](https://www.zdnet.com/article/which-are-the-most-insecure-programming-languages/)

### Portability
The only reason that I feel why C and C++ are still popular today is because of their portability.
**Compiled languages** are more portable than **interpreted languages**.

In compiled languages you can easily compile code in a binary [executable](https://en.wikipedia.org/wiki/Executable), which can be run by users without installing the actual programming language you have written the code in.

Whereas, in interpreted languages you cannot interprete code into a binary executable easily.*You can convert python3 and javascript code in executables, but it does not work all the time.*

### Cross-platform compatibility
Cross-platform compatibility means ability to execute the same application distribution on different platforms (for more: link to Cross-Platform Article).

Compiled languages have more issues in Cross-platform compatibility while interpreted languages work well in different platforms.

While taking executables into consideration, the OS and it is dependencies come into picture while compiling the code and that's why this executable cannot be run in different platforms.

The executable written for `Windows x32` will not work on `Windows x64` and also any unix systems.

Interpreted languages do not have this issue as the interpreter installed on the user's machine gives instructions to the machine's processor.

This can be done only if a runtime environment is present on the user's machine

### Syntax difficulty
I feel that if you are learning your first programing language, the [syntax](https://en.wikipedia.org/wiki/Syntax) should be an easy one.

It does not matter if it is a compiled language or an interpreted one if you are developing software at the basic level.

Some of the languages having the easiest syntaxes are Python, Lua, JavaScript and Ruby and are great for being the first language you learn.
Only after, you know a certain concepts, I feel you should go for learning languages like Java, C#, R, etc.

### Job Opportunities
If you are learning programming for getting a job, this criteria is for you. 
If you want to get a job then what is the advantage in learning which is outdated or not in demand?

You should research about what is the most demanded language in your area of interest, and go for learning that language first.
You can find some of the most popular and demanded languages in the world [here](https://towardsdatascience.com/top-10-in-demand-programming-languages-to-learn-in-2020-4462eb7d8d3e)

*Spoiler Alert: The programming language having the most job opportunities worldwide is Python3*

If you are a skilled programmer and you want to add a new language to your portfolio, find where the industry is headed. 
The StackOverflow developer surveys are very accurate and show the state of the industry. 

### My Recommendation
If you ask me, i think python is the best language for you to start with, for a number of reasons:
- It's one of the most **relevant languages** today. You find it being discussed in a lot of programming forums, and there is an ocean of resources to learn and master it online
- **Very easy syntax**, this does not discourage new programmers, and then can focus solely on understanding and mastering the basic concepts
- **Applications**, Python has a lot of applications, ranging from web dev to game dev to ML (Maching Learning). New programmers can play around with these and figure out for themselves which field they're most interested in, and then choose a different language to pursue it if they feel like it's better.


Happy debugging,

Sk9, MetaStag|_Engrafa Team_
