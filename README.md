# count-demo
# count-demo
count repositoryhhhhhh


use ls -la to list out the files in repository

use clear keyword to clear the commands before

git status keyword is used to check the updates or changes we done in repository

after adding a new file to project folder and now use git status then it shows files which are done before as modified file name and newly added files as untracked files

to track the untracked files use add .(period) to track all the files or use add filename to track  parrticular file
then after use git status
then commit the changes 
pwd is used to check where is our project working directory

git remote add origin http link for new ones

git push -u origin master(or) main depends


//branches
git branch it shows the names of branches

if you want to switch between two branches use
git checkout -b newbranch name

in command if you type the some part of commands or files name use tab button    

git checkout branchnames is used to switch between branches

the changes you did in children branch wont appear in parent branch  try by using main branch and anybranch

suppose if you are in master branch and you want to know the difference between master branch and its child branch use 
git diff childbranchname

enter q button to quit of particular command

just added few words to observe the branches

git commit -am(add and message) ----doing committing and adding at a time and this works only for modified files not for newly created files

if you merge one branch into another branch it better to accept merge conflict at coding place and then you have to commit changes

if you want to reset stagedfiles into unstaged (before adding them means unmodified stage and then into modified stage)
then we have to use the command git reset (or) git reset filename (or) git reset HEAD~1 (it means the last commit we did)
