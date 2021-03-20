# git_cheatsheet
Git cheatsheet based on the "Introduction to Git and GitHub" course offered by Google on Coursera.


## Advanced Git Cheat Sheet

`git commit -a`: stages files automatically  
`git log -p`: produces patch text  
`git show`:	shows various objects  
`git diff`:	is similar to the Linux `diff` command, and can show the differences in various commits  
`git diff --staged`: an alias to `--cached`, this will show all staged files compared to the named commit  
`git add -p`: allows a user to interactively review patches to add to the current commit  
`git mv`: similar to the Linux `mv` command, this moves a file  
`git rm`: similar to the Linux `rm` command, this deletes, or removes a file  

## Git Revert Cheat Sheet

`git checkout`: is effectively used to switch branches  
`git reset`: basically resets the repo, throwing away some changes. It’s somewhat difficult to understand, so reading the examples in the documentation may be a bit more useful  
`git commit --amend`: is used to make changes to commits after-the-fact, which can be useful for making notes about a given commit  
`git revert`: makes a new commit which effectively rolls back a previous commit. It’s a bit like an undo command  

## Git Branches and Merging Cheat Sheet

`git branch`: used to manage branches  
`git branch <name>`: creates the branch  
`git branch -d <name>`: deletes the branch  
`git branch -D <name>`: forcibly deletes the branch  
`git checkout <branch>`: switches to a branch  
`git checkout -b <branch>`: creates a new branch and switches to it  
`git merge <branch>`: merge joins branches together  
`git merge --abort`: if there are merge conflicts (meaning files are incompatible), `--abort` can be used to abort the merge action  
`git log --graph --oneline`: this shows a summarized view of the commit history for a repo  