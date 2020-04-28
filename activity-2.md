###Activity 2

##Objectives
*	be able to add files to a repository
*	to understand the concept of the staging area
*	be able to commit files to a repository
*	to understand the concept of pushing to a remote repository

1.	Create a text file called mars.txt
vi mars.txt
or
nano mars.txt

2.	Enter the following text in the file:
Cold and dry, but everything is my favourite colour

3.	Check the directory
ls -la

4.	Check the repository status
git status

5.	Start tracking the file
git add mars.txt

6.	Check the status
git status

7.	Commit the file to the repository
git commit -m "Start notes on Mars as a base"

8.	Check the status
git status

9.	Add another line to mars.txt
vi mars.txt
The two moons may be a problem for Wolfman

10.	Check the status again
git status

11.	Commit the file
git add mars.txt
git commit -m "Add concerns about effects of Mars' moons on Wolfman"

12.	Check status
git status

13.	Check the log
git log

14.	Create a new directory
mkdir spaceships

15.	Check status
git log
NOTE: Git does not track directories, it tracks files. So you won’t see the newly created directory. It will only appear after you added some files to the directories.

16.	Create two files, apollo-11 and sputnik-1 in the spaceships directory

touch spaceships/apollo-11
touch spaceships/sputnik-1

17.	Check status
git status

You should now be able to see the  spaceships directory as being untracked
18.	You can add all the files in a directory at once by adding the directory
git add spaceships

19.	Check the status
git status
You should now see the that two files in the directory, spaceships, are staged.

20.	Commit the files
git commit -m "Add some initial thoughts on spaceships"