
### Git Status
```git status --short``` - Short status of files.

### Git Add
```git add .``` Add all files to stage.

### Git diff
```git diff``` - Show differences between the staged file and the untracked ones.
```git diff --stage``` - Show differences between files that are in stage.

### Git Commit 
```git commit -m "[message]"``` - Commit your changes to the current branch. 
```git commit -am "[message]"``` - Add and Commit your changes to the current branch. 
```git commit -amend -m "[new-message]"``` - Fix message of last commit.

### Git Reset 
```git reset --soft HEAD^[number] ``` - Moves the HEAD to a specific previous commit and delete the other ones
```git reset --soft [commit-id] ``` - Moves HEAD to a specific commit
```git reset --mixed [commit-id]``` 
```git reset --hard [commit-id]```  - Moves to a specific commit and delete changes/files made after that commit. 

### Logs
```git log --oneline``` - Oneline logs.
```git reflog``` - Reference logs of all the ocurrences 
```git log -all``` - To show log of all branches

### Git Checkout
```git checkout -- .``` - Rebuild the project to the previous commit. 
```git checkout -b [branch-name]``` - Create a new branch and move us there.
```git checkout [branch-name]``` - Move to a specific branch

### Git Branch 
```git branch``` - List all branches
```git branch [branch-name]``` - Create new branch
```git branch -d [branch-name] -f``` - Delete a branch

### Git Merge
```git merge [branch-with-changes]``` - Merge a branch with other, you need to be in the branch without changes, master

### Git Stash
- Is a place where we can isolate our information and then recover it later. 
```git stash``` - Isolate our work in stash.
```git stash pop``` - Recover our changes and delete the stash