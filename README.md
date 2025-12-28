

Git&Github

1.Github is source code management tool.
2.Github is a place where we can store our source code and the all-necessary files. 

git commands:

git init:
It initialize the empty git repository in our local machine.

git status 
It will show the current status of the working area files and staging area files. Working area files, we can call it untracked files, and these files will be shown in red colour. Staging area files will be shown in green colour.
 
git add: 
This command will move files from working area to staging area.
git add filename
git add *.txt
git add *
git add .

git config --global --list
git config --globla user.name "name"
git config --global user.email "email" 

git commit
git commit -m "commit message"
 
git commit -am "commit message" for modified files
 
git log
git log will give commit history with commit id and commit message.
 
For recent 2 commits use the below command
 git log -2

git log –oneline it will show the commit history in one line.

git show
git show commit id
git show --pretty="" --name-only commitid
 
git push
git remote -v
git remote add dev https://github.com/ismaildevops0207/devops.git
 
git push aliasname branch 
 
