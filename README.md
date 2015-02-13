# lab_01_commandline_02
Intro and Navigating the File System
Lab - Navigating the File System
==========
Follow the instructions line-by-line.  

* Type in the commands as is, but ignore the beginning prompt.  
* Enter, tab, up and down are represented by <ENTER><TAB>,<UP> and <DOWN>.  
* "No output" or "nothing happens" are valid answers to any of the questions.
==========

==========
1. Open a new terminal window.
----------

==========
2. Create a directory called mtec1003.
----------

==========
3. Change your directory so that you're in mtec1003.
----------

==========
4. Type:

$ pwd

Check that the output ends with mtec1003 (something like this: /Users/bree/mtec1003).

If it doesn't, start at #1 again, or ask for help before moving on!

Copy and paste the output of pwd below.
----------

/Users/juancarlosospino/mtec1003
Juancarloss-Air:mtec1003 juancarlosospino$ 


==========
5. Type:

$ mkdir animals
$ ls

Copy and paste the output below.
----------

Juancarloss-Air:mtec1003 juancarlosospino$ ls
animals


==========
6. Type:

$ mkdir food
$ ls

Copy and paste the output below.
----------

Juancarloss-Air:mtec1003 juancarlosospino$ ls
animals	food

==========
7. Type:

$ c$ ls

Copy and paste the output below.
----------

Juancarloss-Air:mtec1003 juancarlosospino$ c$ ls
-bash: c$: command not found

==========
8. Type:

$ cd foo/bar/baz/qux
$ pwd

Copy and paste the output below.
----------

Juancarloss-Air:mtec1003 juancarlosospino$ cd foo/bar/baz/qux
-bash: cd: foo/bar/baz/qux: No such file or directory
Juancarloss-Air:mtec1003 juancarlosospino$ pwd
/Users/juancarlosospino/mtec1003

==========
9. Type:

$ cd ../..
$ pwd

Copy and paste the output below.
----------

Juancarloss-Air:mtec1003 juancarlosospino$ pwd
/Users/juancarlosospino/mtec1003
Juancarloss-Air:mtec1003 juancarlosospino$ 


==========
10. Type:

$ cd -
$ pwd

Copy and paste the output below.
----------

Users/juancarlosospino
Juancarloss-Air:~ juancarlosospino$ 

 
==========
11. Type:

$ cd ../../../..
$ pwd

Copy and paste the output below.
----------

Juancarloss-Air:~ juancarlosospino$ cd ../../../..
Juancarloss-Air:/ juancarlosospino$ pwd
/

==========
12. Type:

$ ls -l
$ rmdir animals
$ ls -l

Copy and paste the first two lines from the output into the space below.
----------

total 53
drwxrwxr-x+ 82 root  admin  2788 Feb  7 16:15 Applications
drwxrwxr-x  11 root  admin   374 Jul 30  2014 Incompatible Software

==========
13. Type:

$ cd ~
$ pwd

Copy and paste the output into the space below.
----------



==========
14. Type:

$ cd /Volumes
$ pwd

Copy and paste the output into the space below.
----------



==========
15. Type:

$ cd /unknown_folder
$ pwd

Copy and paste the output into the space below.
----------

uancarloss-Air:~ juancarlosospino$ pwd
/Users/juancarlosospino

==========
16. Type:

$ cd ~/mtec1003
$ pwd

Copy and paste the output into the space below.
----------

/Users/juancarlosospino/mtec1003
Juancarloss-Air:mtec1003 juancarlosospino$ 


==========
17. Type:

$ hostname

Copy and paste the output into the space below.
----------
Juancarloss-Air:mtec1003 juancarlosospino$ hostname
Juancarloss-Air.home


==========
18a. Make sure you're back in your mtec1003, which should be in your home folder.  What command would you use to find out if you're in the right folder?  Write the command below, then run it.
----------

cd mtec1003
pwd

==========
18b. If you're not in the right directory, type the following command:

cd ~/mtec1003

Otherwise skip this question/step!
----------



==========
19. Create the following directories, with each one inside each other.  The first one, pineapple, is the inner most:

pineapple
orange
strawberry
lemon

Use only one command to make all of these new directories.  Write what command you used below:
----------

mkdir -p pineapple/orange/strawberry/lemon

==========
20. Make another directory called aardvark.  

Write the command you used to create the directory below:
----------

mkdir aardvarcdk

==========
21. List the files and directories in the current directory using the long format.  

What is the modified date of the aardvark directory?
----------

drwxr-xr-x   2 juancarlosospino  staff   68 Feb 12 21:19 .
drwxr-xr-x+ 27 juancarlosospino  staff  918 Feb 12 21:19 ..cd


==========
22. Make 3 directories nested within each other:

* foo should be the outermost directory
* bar should be the inside foo
* baz should be inside bar

What command did you use?
----------

mkdir -p foo/bar/baz

==========
23. Change your directory so that you're in the inner most directory (baz)

What command did you use?
----------
cd foo
cd bar
cd baz


==========
24. Change your directory so that you're two directories up (foo)

What command did you use?
----------
popd

==========
25. What command is used to delete empty directories?
----------

rmdir 

==========
26. What command is used to print out your current working directory?
----------

ls

==========
27. What flag do I pass to ls to print out all files?
----------

ls -a

==========
28. What's the shortcut for home directory?
----------

cd ~


==========
29. What's a pathname?
----------

is a list of all files and directories
==========
30. What's a directory?
----------

directories are folders 
==========
31. What's the *absolute* path (full path, starting at root) to your user's Downloads directory?
----------

