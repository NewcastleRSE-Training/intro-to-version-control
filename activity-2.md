###Activity 2

##Objectives
*	be able to add files to a repository
*	to understand the concept of the staging area
*	be able to commit files to a repository
*	to understand the concept of pushing to a remote repository

1.	Create a text file called index.html

nano index.html

2.	Enter the following text in the file:

<!DOCTYPE html>
<head>
</head>
<body>A simple web page</body>
</html>

3.	Check the directory
ls -la

4.	Check the repository status
git status

5.	Start tracking the file
git add index.html

6.	Check the status
git status

7.	Commit the file to the repository
git commit -m "Adding index.html"

8.	Check the status
git status

9.	Add another line to index.html between <head> and </head>
nano index.html
<title>A first web page</title>

10.	Check the status again
git status

11.	Commit the file
git add index.html
git commit -m "Added title"

12.	Check status
git status

13.	Check the log
git log

14.	Create a new directory
mkdir resources

15.	Check status
git log
NOTE: Git does not track directories, it tracks files. So you won’t see the newly created directory. It will only appear after you added some files to the directories.

16.	Create two files, text-1 and text-2 in the resources directory

touch resources/text-1
touch resources/text-2

17.	Check status
git status

You should now be able to see the  resources directory as being untracked
18.	You can add all the files in a directory at once by adding the directory
git add resources

19.	Check the status
git status
You should now see the that two files in the directory, resources, are staged.

20.	Commit the files
git commit -m "Adding some files to resources"

