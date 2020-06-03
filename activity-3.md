###Activity 3

##Objectives
* 	to understand the concept of branches
*	be able to create a new branch
*	be able to view all branches/current branch
*	be able to switch branches
*	be able to merge a feature branch into master
*	be able to delete a branch



1.	View the current branch 

`git branch`

2.	Create a new branch

`git branch feature/header`

3. Check the branch is created successfully  - should show both branches. A star indicates the active branch.

`git branch`

4.	Switch to the new branch - should see a change in the shell output, the active branch is shown in brackets

`git checkout feature/header`

5. Create a new file on the feature/header branch

`touch header.html`
`git status`

6. Add the file to the staging area

`git add header.html`
`git status`

7. Commit the file - header.html should no longer show as a new file

`git commit -m "Adding header.html"`
`git status`

8. Switch back to the master branch and check the contents

`git checkout master`
`git status`

9.	Merge the feature/header branch into master, then list the files. Header.html now exits in the the master branch.

`git merge feature/header`
`ls`


10.	View your commit history 

`git log`

11. Delete the feature/header branch, then check the branch listing

`git branch -d feature/header`
`git branch`
 

