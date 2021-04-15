# Difference between Terminal, Shell and Console
We all have heard about terminals, shells and consoles while working with linux or in general as well, but we are often confused if they are the same or is there any major difference. So let's see the difference between the three of them :
### Terminal
It is basically the interface where we can type and execute text-based commands. Why do we use it? We use it because it is much faster to complete some tasks using a terminal than a GUI application. Being a programmer, you should learn how to use terminal commands since it makes your workfow faster. 
- Example - you want to create a python file and code it : you can do it by creating a file in file explorer or you can do the same from your text editor (if it has a feature for the same) and save it with the extension *.py* and then start coding. 
But you can do the same thing by using the terminal, you just have to change the directory to the desired location where you want to create the file which can be done be `cd <directory>` where cd stands for change directory. Then you can simply write `code file_name.py` which will automatically create a fiile and then can save it by ctrl+s. This might seem nothing but it makes you workflow much faster, you are not using your mouse, everything is happening with keyboard and just takes 2 commands. When you get more experienced this will hardly 5-10 secs. Now this arises a question that are there different terminal programs? If yes then do they have different commands? Well no. For this we need to understand what shell is, so here we go - 

### Shell
It is basically a computer program/software that interprets and executes the various commands that we type in the terminal. It is an environment in which we can run our commands, programs, and shell scripts. So the terminal sends the user input to the shell, the shell generates the output and sends it back to the terminal for display. In the above example of creating a file through terminal, it's shell which creates the file, and its terminal which enables us to enter the command. There are many types of shells out there and each type of shell has it's own set of recognised commands. It is independent of the terminal program/emulator we use.
- A prompt is issued by the shell like $ and %  which is displayed on the screen. We can also customize this prompt by using Environment variables. 
- In unix there are two major types of shells -
	- Bourne shell : In a Bourne-type shell the default prompt is the **$** character.
		- Bourne shell (sh)
		- Korn shell (ksh)
		- Bourne Again shell (bash)
		- POSIX shell (sh)
	- C shell : In a C-type shell the default prompt is the **%** character.
		- C shell (csh)
		- TENEX/TOPS C shell (tcsh)
		- zsh

### Console
Terminal and Console are basically synonyms. They are in general sense physcial terminals. They are equipments through which we can interact with computer. The name *terminal* came from an electronic point of view and *console* from a hardware point of view. 



