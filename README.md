# Git-Branching
---
### To list all the available branches
<hr>
``` git branch ```
### To create new branch 
``` git branch <branchName> ```

### To switch branch from current to (branchName)
``` git checkout <branchName> ```

### To create a bew branch and switch init the new branch
``` git checkout -b "<branchName>" ```

### To update a branch from main or master branch
1. update the main or master branch ( git pull (switch into the main branch if not onto it -git checkout <main>) )
2. merge with the main or master branch
3. ```
   git checkout <main/master>
   git pull
   git checkout <intendedBranch>
   git merge <main/master>
   ```
