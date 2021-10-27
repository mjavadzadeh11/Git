# Git
in this reposetory Git and Git-hub basics has been written.

## clone: 
git clone + SSH link
for pulling reposetory from the github 
## push:
for pushing back a code back to the github reposetory: git push origin (name of branch example: main or dev)
*for modified file we can use ==> git commit -am "massage" for adding and commiting at the same time

## local-push:
if we have a folder which desire to send online on github: after creating that folder we go inside of that folder and initialize a git command: git init 
after that git add -A ==> git commit -m "massage"
git remote add + SSH link ==> git remote -v 
 
## adding branch:
for adding a branch : git checkout -b "name of new branch"
git checkout main ==> back to master branch
(this content produced in a branch called feature)
git diff : before merging to branch we can double check the differences which made ==> git diff + name of the branch
git merge

## deleting a branch: 
git branch -d "name of branch"