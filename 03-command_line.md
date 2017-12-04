# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

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

> > * `pwd`: show current working directory path
> > * `mkdir`: creating a directory
> > * `rmdir`: deleting a directory
> > * `touch newfile.txt`: creating a file using `touch` command
> > * `rm`: deleting a file
> > * `mv`: renaming a file
> > * `ls -a`: listing hidden files
> > * `cp`: copying a file from one directory to another
> > * `echo >`: redirect the output of a command to a .txt file
> > * `cat`: print whole file to the screen
> > * `cd`: change directories
---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> >`ls`: list files in a directory
> >`ls -a`: list all files in a directory including hidden ones
> >`ls -l`: list files in a directory in Long Output Format (with permissions, owner, size...)
> >`ls -lh`: list files and sizes in human readable format
> >`ls -lah`: list all files including hidden ones with sizes in human readable format
> >`ls -t`: list files in directories by time modified
> >`ls -Glp`: list files, display group numbers, in Long Output Format, add / after directory namess

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > `ls -lah`
> > `ls- lt`
> > 'ls- Lr'
> > 'ls- d'
> > `ls -1` 

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > `xargs` reads data from standard input and executes the command in its arguments
> > `xargs` can be used with `|` to build pass output from a `find` function and execute a command on those, like `rm`
> > for example: `find  -name "*.txt" | xargs rm

 

