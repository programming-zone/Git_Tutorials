# BRANCH & MERGE

Isolating work in branches, changing context, and integrating changes

`git branch`

list your branches. a * will appear next to the currently active branch

`git branch [branch-name]`

create a new branch at the current commit

`git checkout`

Example, `git checkout [branch]`

switch to another branch and check it out into your working directory

`git branch -d [branch]`

delete a branch from your repository

`git merge --no-ff [branch]`

merge the specified branch's history into remote repository (without fast forword)

`git merge [branch]`

merge the specified branch’s history into the current one

`git log`

show all commits in the current branch’s history
