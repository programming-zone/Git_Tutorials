# TAGS

Like most VCSs, Git has the ability to tag specific points in a repository’s history as being important.
Typically, people use this functionality to mark release points (v1.0, v2.0 and so on). In this section,
you’ll learn how to list existing tags, how to create and delete tags, and what the different types of
tags are.

`git tag` (with optional `-l` or `--list`)

List the existing tags in Git

`git tag -l "v1.8.5*"`

search for tags that match a particular pattern

`git tag -a [version] -m "Message"`

Creates an annotated tag in Git

`git show`

Example, `git show v1.4`

You can see the tag data along with the commit that was tagged

`git tag [version]`

Example, `git tag v1.4-lw`

Creates a lightweight tag in Git

`git tag -a [version] [commit hash]`

Example, `git tag -a v1.2 9fceb02`

creates tag for specified commit

`git push origin <tagname>`

transfer a single tag to remote repository

`git push origin --tags`

transfer all tags to remote repository

`git tag -d <tagname>`

delete a tag on your local repository

`git push <remote> :refs/tags/<tagname>` or `git push origin --delete <tagname>`

delete a tag from remote repository

You can also checkout to any tags
