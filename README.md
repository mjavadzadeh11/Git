# Git
in this reposetory Git and Git-hub basics has been written.

## Clone: 
git clone + SSH link
for pulling reposetory from the github 
## Push:
for pushing back a code back to the github reposetory: git push origin (name of branch example: main or dev)
*for modified file we can use ==> git commit -am "massage" for adding and commiting at the same time

## Local-push:
if we have a folder which desire to send online on github: after creating that folder we go inside of that folder and initialize a git command: git init 
after that git add -A ==> git commit -m "massage"
git remote add origin + SSH link ==> git remote -v 
 
## Adding branch:
for adding a branch : git checkout -b "name of new branch"
git checkout main ==> back to master branch
<<<<<<< HEAD
<<<<<<< HEAD
(this content produced in a branch called feature)
git diff : before merging to branch we can double check the differences which made ==> git diff + name of the branch
on the branch : git merge main

## deleting a branch: 
git branch -d "name of branch"


=======
(this content produced in a branch called feature)

## Unstage a file:
git reset (optional:name of file)

## Undoing commits:
unstaged and uncommit file: git reset HEAD~1
for selective undo a commit we can use: git log
git reset --hard (commit hash)

complete video :https://www.youtube.com/watch?v=RGOj5yH7evk&ab_channel=freeCodeCamp.org
>>>>>>> 7a06e68e749efa7752bb5324dab6c03a4d0654d7
