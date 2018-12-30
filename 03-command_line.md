# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path >>  pwd
* creating a directory >> mkdir
* deleting a directory >> rmdir if empty, else rm -r
* creating a file using `touch` command >> touch
* deleting a file >> rm
* renaming a file >> mv original_name new_name
* listing hidden files >> ls -a
* copying a file from one directory to another >> cp

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

look up command info >> man
update file permissions (must do to execute) >> chmod

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  >> lists the contents of the directory
`ls -a`  >> lists contents, including hidden files
`ls -l`  >> long format view, includes details like file permissions
`ls -lh` >> long format view + uses appropriate size unit suffixes (e.g. Gb)
`ls -lah` >> long format view + show hidden files + unit suffixes
`ls -t`  >> sort by time modified
`ls -Glp`  >> enable colorized output + long format + show with a / when a file is a directory


---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

-R displays subdirectories
-d displays only directories
-F flags whether a file is a directory, executable file, symbolic link, socket, whiteout, FIFO
-S sorts files by size
-H follows symbolic links

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

Allows the user to build and execute command lines from standard input. For example: 
Natalias-MacBook-Pro:xargs_test natalia$ xargs touch
test1 test2 test3
Natalias-MacBook-Pro:xargs_test natalia$ ls
test1	test2	test3


 

