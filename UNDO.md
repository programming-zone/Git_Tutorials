# Undoing Things

At any stage, you may want to undo something. Here, we’ll review a few basic tools for undoing
changes that you’ve made. Be careful, because you can’t always undo some of these undos. This is
one of the few areas in Git where you may lose some work if you do it wrong.

`git reset HEAD~`

undo last commit from local repository

`git commit --amend`

Example, `git commit -m 'Initial commit'`
`git add forgotten_file`
`git commit --amend`

add forgotten files and commit again

`git checkout -- <filename>`

Unmodifying a Modified File

`git reset <filename`

unstage the specified files
