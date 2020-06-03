###Activity 4

##Objectives
*	to understand the concept of a remote repository
*	be able to create a GitHub account
*	be able to upload files to a remote repository
*	to understand a multi-user workflow, including pull and merge concepts

Prerequisite: must have completed creating a GitHub account and have created an online repository 

1. 	Check that local repository files have been committed and are ready to be pushed

`git status`

2. 	Push existing files to the repository

`git push`

3.	Check the contents of the GitHub repository - the commits should have appeared

4.	Select the header.html file in the GitHub repository

5.  Click the pencil icon in the top right of the section to put the file in edit mode

6. 	Copy and paste, or type in:  <html><head></head><body>Header contents</body></html>

7. 	Add a description in the commit changes box below if desired, then click the green 'Commit changes' button

8. 	Open the index.html locally and make a small change.

9. 	Add, then commit index.html

`git add index.html`
`git commit -m "Making a change"`

10. Attempt to push  - this should fail as we haven't got the changes from GitHub to header.html

`git push`

11.	Update the header.html file locally by using git pull - the Shell may bring up a file window type :qa to exit

`git pull`

12. Merge completed, attempt another push - should show message that your branch is now up to date with origin/master

`git push`
`git status`
