GIT CHAPTER - 1

git status  -- check status

git add -A / git add .   ---to track the all files

git rm --cached <filename>   --- to remove a file from tracking

git commit -m "message"     --- to commit a changes with message

git log    --- to check the commit messages

git commit --amend   ----to change the commit message

git remote ---to check the remote repository

git remote add origin <repository http> ---the name of the repository is origin

git config -l ---gives more details about the repository, author, branches etc

git push origin master ---pushing the recent commit to remote repository


GIT CHAPTER - 2

git remote remove origin  --- to remove the origin repository
 
git pull = git fetch + git rebase

local            remote

commit 1         commit 1
commit 2         commit 3(some one changed)

git fetch + rebase

commit 1
commit 2
commit 3 (this is our latest commit now)

git pull

commit 1
commit 2
commit 3
commit 4 (it will create new commit which is a merged commit)


git branch --set-upstream-to=origin/<branch> master  ---to track 
                                                        information for the rebase branch
                                                        
                                                        
git fetch --- fetch the code

git rebase ---modifies the code and adds the latest commit

