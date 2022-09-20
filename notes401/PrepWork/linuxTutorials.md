# Linux Tutorials

[Command Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)

## The CLI
- Within the terminal is called the shell, this is part of the OS that defines how the terminal will behave and execute commands


## Basic Navigation
- pwd or print working directory shows the present working directory
- ls, short for list, will show you the files and directories in the present working directory
- Absolute path specifies a location in relation to the root directory
- Relative paths specify a location in relation to where we currently are in the system
- ~ is a shortcut to the home directory
- . is a reference to your current directory
- .. is a reference to your parent directory
- cd, change directory allows you to move to another directory

## More About Files
- Everything in linux is a file, even your monitor and keyboard
- Linux is extensionless, it ignores any file extension and looks directly into the file to see whats in it
- file [path] will tell you which type of file your dealing with
- linux is case sensitive
- when dealing with directories or files we spaces we must either use quotes or escape characters
- files that start with a . are hidden files, if you want to see the hidden files use the command option -a with ls

## Manual Pages
- manual pages are a set of pages that explain every command available on your system, including what they do
- it also shows the different options that can be run with that command

## File Manipulation
- mkdir will create a new directory
- rmdir will remove a directory
- touch will create a blank file
- cp will copy a file
-mv will move a file
- rm -r will remove non empty directories

``` cp [options] <source> <destination> ```

``` mv [options] <source> <destination> ```


