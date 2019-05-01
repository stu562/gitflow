# gitflow

contents
## Stash 

## Commands that are useful:
- git status : checks if there are newly created changes and commits ready to be staged for remote repository
- git add "name of file(withoutquotes)"
- git commit -m "my meaningful commit message"
    -m : is shortcut for message w/o it you will enter vim.
    -if you are in vim, press ':' key. Type 'wq!' and hit enter. which is write and quit.
- git push origin "name of my branch"


## Branches
- git checkout "name of branch"
- git branch -a 
- git checkout -b "yourbranchname" :creates a branch switch to that newly created branch 

## Rebase and merging 
what about fetching?
- git rebase
- git merge


## Stash 
- git stash : save your current changes and stows it off to the side temporary.
- git stash apply: apply stash to current branch 


## Remote 
- git remote -v: shows any origin and remote repos 


## Merge
- git checkout master
- git pull origin master 
- git merge newbranchname
- git push origin master

### documentation source 
https://git-scm.com/