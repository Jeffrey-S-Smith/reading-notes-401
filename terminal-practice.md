Notes from https://ryanstutorials.net/linuxtutorial/

## The Command Line - What is it, how does it work and how do I get to one.

- A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.
- Within a terminal you have what is known as a shell. This is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you. There are various shells available but the most common one is called bash which stands for Bourne again shell.

## Basic Navigation - An introduction to the Linux directory system and how to get around it.

~ (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents
. (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).
.. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.

- In order to move around in the system we use a command called cd which stands for change directory.
pwd
Print Working Directory - ie. Where are we currently.
ls
List the contents of a directory.
cd
Change Directories - ie. move to another directory.
-Relative path
A file or directory location relative to where we currently are in the file system.
-Absolute path
A file or directory location in relation to the root of the file system.

## More About Files - Find out some interesting characteristics of files and directories in a Linux environment.

- Spaces in file and directory names are perfectly valid but we need to be a little careful with them. As you would remember, a space on the command line is how we separate items.
- Ways to get around this
The first approach involves using quotes around the entire item.
Another method is to use what is called an escape character, which is a backslash ( \ )

## Manual Pages - Learn how to make the most of the Linux commands you are learning.

- The manual pages are a set of pages that explain every command available on your system including what they do, the specifics of how you run them and what command line arguments they accept
- To exit the man pages press 'q' for quit.

man <command>
Look up the manual page for a particular command.
man -k <search term>
Do a keyword search for all manual pages containing the given search term.
/<term>
Within a manual page, perform a search for 'term'
n
After performing a search within a manual page, select the next found item.
  
## File Manipulation - How to make, remove, rename, copy and move files and directories.

- Linux organises it's file system in a hierarchical way.
- It's important that we create a directory structure that will help us organise that data in a manageable way.
- The Linux command line does not have an undo feature. Perform destructive actions carefully.
  
mkdir
Make Directory - ie. Create a directory.
rmdir
Remove Directory - ie. Delete a directory.
touch
Create a blank file.
cp
Copy - ie. Copy a file or directory.
mv
Move - ie. Move a file or directory (can also be used to rename).
rm
Remove - ie. Delete a file.

## Cheat Sheet - A quick reference for the main points covered in this tutorial.

[Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)