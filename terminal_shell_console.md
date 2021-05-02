# Difference between Terminal, Shell and Console
We have all heard about terminals, shells and consoles while working with Linux or in general as well, but we are often confused whether they are the same or is there any major difference between them. So let's see the differences between the three of them :
### Terminal
It is basically the interface where we can type and execute text-based commands. Why do we use it? We use it because it is much faster to complete some tasks using a terminal than a GUI application. Being a programmer, you should learn how to use terminal commands since it makes your workflow faster. 
- **Example** - you want to create a python file and open it in a text editor: you can do it by creating a file in file explorer or you can do the same from your text editor (if it has a feature for the same) and save it with the extension *.py* and then start coding. 
But you can do the same thing by using the terminal, you just have to change the directory to the desired location where you want to create the file which can be done by `cd /path/to/folder/` where cd stands for change directory. Then you can simply write `touch file_name.py` which will automatically create a file and then you can open it in your preferred text editor, for example -> `vim file_name.py` or `nano file_name.py` or whatever text editor you're using. This might seem nothing but it makes you workflow much faster, you are not using your mouse, everything is happening with the keyboard and it just takes 2 commands. When you get more experienced this will hardly take 5-10 secs. Now this arises a question... are there different terminal programs? If yes then do they have different commands? Well no. For this we need to understand what a shell is, so here we go - 

### Shell
It is basically a computer program/software that interprets and executes the various commands that we type in the terminal. It is an environment in which we can run our commands, programs, and shell scripts. So the terminal sends the user input to the shell, the shell generates the output and sends it back to the terminal for display. In the above example of creating a file through terminal, it's the shell which creates the file, and it is the terminal which enables us to enter the command. There are many types of shells out there and each type of shell has it's own set of recognized commands. It is independent of the terminal we use.

- In Unix there are two major types of shells -
	- Bourne shell : In a Bourne-type shell the default prompt is the **$** character.
		- Bourne shell (sh)
		- Korn shell (ksh)
		- Bourne Again shell (bash)
		- POSIX shell (sh)
	- C shell : In a C-type shell the default prompt is the **%** character.
		- C shell (csh)
		- TENEX/TOPS C shell (tcsh)
		- zsh

A prompt is issued by the shell, it's a prefix automatically printed by the shell before each command, it can show useful information like the host name or the current path. Some shells like bash and zsh allow you to make custom prompts, and you can also use a third party program like starship which provides a more powerful prompt

### Console
Terminal and Console are basically synonyms. They are in general sense physical terminals. They are equipment through which we can interact with computer. The name *terminal* came from an electronic point of view and *console* from a hardware point of view. 

---

Happy debugging,

Emperor, MetaStag| Engrafa Team
