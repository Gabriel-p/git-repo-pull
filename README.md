git-repo-tools
=============

Simple set of tools to manage a folder with several Git repos as sub-directories.


## `git-repo-pull`

Performs a pull from all the repos present as subdirectories.

Run in terminal with:

`.git-repo-pull.sh`

The script will go through all subdirectories
performing a `git pull` if any one has a `.git.`  folder present.

## `git-repo-status`

Tells you which repos have un-commited changes.

Run in terminal with:

`.git-repo-status.sh`

Same functioning than the one above except it runs a `git status`.



