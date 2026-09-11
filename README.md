# LearnShell
LearnShell platform

## Section 1

### First lesson - Echo
echo "Hello World"
This will print something to the CLI.

Note: The general format is <command> <argument>, so in this case, "echo" is the command, and "Hello World" is the argument. Another thing to remember is that the CLI is case-sensitive.  Therefore, cat and CAT are two different things. 

### Second lesson - Comments
A "#" indicates that everything after that symbol on that line is a comment. This will indicate to the person reading the script any information that the programmer wanted to include. It will also tell the environment to not run whatever is contained in the comment. 

### Third lesson - Shebang
A "shebang" is a special type of comment at the beginning of a script that tells the system which shell to use.
An example of a shebang is:
"#!/bin/bash
echo "Hello World!""

### Fourth lesson - TODO
A TODO comment marks a future task that needs to be completed.
"#TODO: Add error handling here"

### Fifth lesson - pwd
The command "pwd" will print the current directory that you are in (if it is not part of the prompt).
To use it, type "pwd".

### Sixth lesson - list files
The command "ls" will show you  on the screen a list of files and any nested directories. To use it, type "ls". To add options, which will provide additional information, you can use the following:
ls - a general list of the contents of the directory
ls -l - shows a detailed list of the contents of a directory, with information such as file size, permissions and dates
ls -a - shows all files, even those that are hidden
ls -al - shows all files will all of the information.
