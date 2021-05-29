# Git

Most developers have come across git sooner or later. Git is a version-control system. But wait? What's a version control system, you ask? Let's start there.



### Version Control System

A version control system is a system software that helps managing the changes made to the source code of a project. This is a very important thing, especially for group projects.

Let's say for example you're developing an application and suddenly got an idea for a new feature, but you're not sure if it will fit in with your current code. So what you can do is using a version control system, test these new changes and if you like them, you keep them and in case you don't, revert back to the previous state of the application, when you didn't have this feature.

Version control system also helps in keeping track of who did what in a project, and makes it easy to calculate the total contribution of each individual member.

### Git

Git is the most popular version control system out there. It was developed by Linus Torvalds, the same man who wrote the linux kernel. It's very commonly used simultaneously with a git hosting service like GitHub to host projects so that others can view and contribute to them.

### Basics of Git

Git can look overwhelming at the start, but it's really very simple:

| commands                    | description                                                  |
| --------------------------- | ------------------------------------------------------------ |
| git init                    | Initialize a git repo                                        |
| git status                  | Check working tree status                                    |
| git add <filename>          | Add files to staging area (required before committing)       |
| git commit -m 'commit name' | Commit files (make sure the commit name is short and concise) |
| git log                     | Check commit history                                         |

That should be enough to get you started.

### Branches

Branches is a very powerful feature of git. Essentially, a branch represents an independent path of code development. This can be very useful.

Taking our earlier example, when we want to test out a new feature, we can make a new branch, do the development in there, and if we think it's good enough, we merge it into the original branch. But in case we don't want to keep that feature anymore, we can just remove this new branch and return to the original one.

By default, there is only one branch known as `main`.

Here are some git commands to work with branches:

| commands               | description                                      |
| ---------------------- | ------------------------------------------------ |
| git branch             | List all branches                                |
| git branch <name>      | Make a new branch <name> without checking it out |
| git checkout -b <name> | Make a new branch <name> and check it out        |
| git branch -d <name>   | Delete branch <name>                             |
| git branch -m <name2>  | Rename branch                                    |

### Working with remote

Remote repositories are versions of your project that are hosted on the Internet or network somewhere.

The most popular place to host git repositories is GitHub, an alternative is GitLab.

Here are some commands to work with remote:

| commands                      | description                 |
| ----------------------------- | --------------------------- |
| git clone                     | Make a local copy of remote |
| git pull                      | Fetch updates from remote   |
| git push                      | Push new commits to remote  |
| git remote rename <old> <new> | Rename remote               |
| git remote remove <remote>    | Remove remote               |

---