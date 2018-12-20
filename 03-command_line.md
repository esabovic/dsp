# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

* show current working directory path - pwd
* creating a directory - mkdir 'name of directory'
* deleting a directory - rmdir 'name of directory'
* creating a file using `touch` command - touch 'name of file'
* deleting a file - rm 'name of file'
* renaming a file - mv 'old name' 'new name'
* listing hidden files - ls -a
* copying a file from one directory to another - cp '/file path/' '/destination path/'
* return to main directory - cd ~
* return to previous directory - cd ../


---

### Q2.  List Files in Unix   

What do the following commands do:  

`ls`  - list files in directory
`ls -a`  - list all files (including hidden) in directory
`ls -l`  - list all files with dates created
`ls -lh`  - same as -l but with readable file size
`ls -lah`  - list all files (including hidden) with dates created & file sizes
`ls -t`  - lists all files sorted by datetime
`ls -Glp`  - list all contents and signifies if file or directory


---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

* ls -R - lists also all subdirectories
* ls -d - lists only directories
* ls -1 - lists files on each line
* ls -m - lists files in comma sep format
* ls -u - sorts by access time

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

It creates a template of a command:

'echo hobbies.txt | xargs touch'

 

