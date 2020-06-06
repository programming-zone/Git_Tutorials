# Git_Tutorials
This Project for learning Git.

## Download Git VCS
Download git from its [website](https://git-scm.com/downloads).

For Windows, [Download](https://git-scm.com/download/win)

For Linux, [Download](https://git-scm.com/download/linux)
or
`sudo apt install git`

## Setting up git on local machine

Set a Git username:

`git config --global user.name "Full Name"`

Set an email address in Git:

`git config --global user.email "email@example.com"`

## Intializing Git repository

Go to your Working directory then,

`git init`

## Staging A single file

`git add <filename>`

## Staging All files

`git add --all` or `git add -A`

## Staging all files in current directory

`git add .`

## Committing to the repository

`git commit -m "<Messages>"`

## Adding remote to local repository

`git remote add origin https://github.com/user/repo.git`

and pushing for the First time,

`git push -u origin master`

## Show remote address
`git remote show origin`
or
`git remote -v`

## Remove remote from local repository

`git remote remove origin`

`git remote rm destination`

Verify it's gone, `git remote -v`

## Pushing to the remote repository

`git push origin master`

## Pulling from the remote repository

`git pull origin master`

## Check Status of repository

`git status`
or for quick check `git status -s`

## Check commit history

`git log` or inline check `git log --oneline`

## creating new branch

`git branch <branch_name>`

## Checkout to the branch

`git checkout <branch_name>`

## deleting branch

`git branch -d <branch_name>`

## merging branch to master

`git checkout master`

then,

`git merge --no-ff <branch_name>`

push to remote repository by running `git push origin master`

# End
