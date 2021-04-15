# Basic Stuff You Need To Know About Programming

## There are two types of languages
Programming languages are divided into 2 groups: compiled and interpreted.

Compiled are languages for which a special program called a compiler is used. It turns a piece of code into machine language, the one a computer can understand (e.g. an .exe file).

Then, there are interpreted, like python, where a separate program, called an interpreter, is used to read and execute your code line-by-line. That's why you can't really turn a python program into .exe. There are attempts that try packaging python and your .py file together, like pyinstaller, but there are a lot of problems with using those (aka they don't usually work at all). 

*[More info here](https://www.programiz.com/article/difference-compiler-interpreter) .*


## Interpreted languages are easier, but mostly only used for websites
Python is usually used for developing web servers (though not only, it's used whenever someone is not sure what to use). When you visit a website, your computer "requests" the website from a server. A server is just a computer like yours (though usually immensely more powerful, but as if that matters) that's running a special program.
That program, when "a request is received", runs some code you wrote, and sends the execution result (aka a webpage) to you. Any code running on the server is called "backend code", if you want to learn backend basics, I suggest you start by learning flask.
Then there's frontend - the stuff you see yourself. Html, CSS and JavaScript are usually used for developing webpages. (Important: not to be confused with Java, Java and JavaScript are similar in the same way as a car and a carpet).
There are a lot of frameworks used to simplify html, css and javascript programming. If you plan on getting into frontend, I personally recommend learning react.js. 

*[More info here](https://www.conceptatech.com/blog/difference-front-end-back-end-development) .*


## Gamedev
This is where compiled languages shine. While they are much more difficult to learn and use, they are much faster, and, as a result, most video games are written with these.
If you want to get into game development, you would have to choose an engine. It takes care of all the actually hard to program stuff (e.g. 3d displaying, physics, cross-platform compatibility). Popular ones are unreal (code written in c++) and unity (code written in c#).


## Machine learning
Mostly python is used here. Machine learning is a really complicated topic and requires a pretty good understanding of high-level maths to do.
It's when instead of writing a big and complicated algorithm for doing some task you tell the computer "ok, here's what are some examples of the task, here are some example solutions, train to do this.
And, after fine tuning and training, the algorithm gets pretty good at the task. Examples of this in the wild are self-driving cars, face recognition on your smartphone camera, and other tasks that even - to some extent - require creativity.

Here's a pretty advanced example of what computer can do: [generate new images that look real](https://thisxdoesnotexist.com/)


## Electron.js
There are some tools that let you turn your website into an `.exe`, a linux and macOS executable by just copying your code (or writing a desktop app with javascript like you are supposed to).
The most popular library is electron.js, popular programs like Discord, whatsApp and vscode use it. It allows you to run html, css  and javascript code in a separate window without having a server set up.
You can use your favorite javascript frameworks as well, for example, Discord for desktop uses react.js + electron.js. Electron takes out all the hastle of turning your code into an .exe file, a linux and macOS executable.


_Author: [rizerphe](https://github.com/BohdanOpyr)_
