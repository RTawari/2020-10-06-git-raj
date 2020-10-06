# 2020-10-06-git-raj
## local from github to local
- 'git init' : create got repository in current folder
- 'git status' : to get the status of files
- 'git add' : to add a file to get repository and in staging area
- 'git commit' : to commit the file in repository


git restore <file>  ## To revert the changes on the file before commitng to statging/index area
git log   ## to view the history of changes
git log --oneline   ## gives the log information in 1 line of the commit msgs
git diff  ## to check the diff in the file from last commit
git diff --staged  ## to check teh changes in stagging area
git commit -m "<shortcut for committing the file with adding the comments>"
git diff <hash> <file>  ## from the git log --online will show all the diff for the file
git checkout <hash> <file>  ## to checkout any previous version of the file
git restore --staged README.md  ## In case we need to restore the file from staging area
git switch -  ## for undo to the master in case the checkout was done to previous version history
git switch -c <branch-name>  ## to create a new branch 
history  ##to see the history of commands typed in git bash

## Create the repository in Github and copy the https url form github in remote cmd
git remote add origin <github https url>  ##https://github.com/RTawari/2020-10-06-git-raj.git
git remote -v  ## displays teh details of origin defined in the previous cmd
git push origin master  ## to 
