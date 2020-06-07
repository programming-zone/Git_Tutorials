# STAGE & SNAPSHOT

Working with snapshots and the Git staging area

`git status` or `git status -s` (short version)

show modified files in working directory, staged for your next commit

`git add [file]`

add a file as it looks now to your next commit (stage)

`git add --all` or `git add -A`

add all files to your next commit(stage)

`git add .`

add current directory to stage

`git reset [file]`

unstage a file while retaining the changes in working directory

`git reset --hard`

clean up your working directory and set to last commit(HEAD)

`git diff`

diff of what is changed but not staged

`git diff --staged`

diff of what is staged but not yet committed

`git commit -m “[descriptive message]”`

commit your staged content as a new commit snapshot
