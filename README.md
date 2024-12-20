# biflo
## basic workflow 
- git clone (ssh)
- git pull
- git status 
- git add 
- git commit (commiting conventions)
- git push 
- git log (history other ext)

## branching 
- main / master || feature || bugfix || refractor

- git branch (list)
- git branch <branch_name> || git checkout -b <branch_name> (create)
- git checkout <branch_name> || git switch <branch_name>
- origin/main : brach on remote
- main: local copy
- git merge 
  
## MERGING 
https://lukemerrett.com/different-merge-types-in-git/

## REMOVING 
HEAD (pointer on current) (if detach git switch)
- git revert (logged)
- git reset --soft --mixed --hard
- 
## STASHING
git stash (auto)
git stash apply 
git stash pop 

git commit -a (if forgot to stage changes )