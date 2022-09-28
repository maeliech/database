# database: 
this file contains the **basics** of github and markdown:

## Markdown

*italic* 

_italic_

**bold**

__bold__

> citation

- list

1. list with number

***bold and italic***

___bold and italic___

~~barré~~

`code`

## Github:

### Basics:

**git init** will create a new local GIT repository

**git clone** is used to copy a repository

**git add** add a file as it looks now to your next commit (stage)

**git commit** will create a snapshot of the changes and save it to the git directory

**git push** push local changes to the original

### git branching & merging 

**git branch** will your branches

**git checkout** switch to another branch and check it out into your working directory 

**git merge** will merge the specified branch's history into the current branch

**git log** show all commits in the current branch's history

### Change:

**git status** : list new or modified files not yet committed

**git diff** : lists down changes and conflicts

**git add [file]** : stages the file, ready for commit

**git reset [file]** : unstages file, keeping the file changes

**git commit -m "[descriptive message]"** : commit all stages files to versioned history

---------------------------------

### Syncrhonize:

**git remote add <name> <url>** : create a new connection to a remote repo

**git fetch** get all the changes from the origin (no merge)

**git pull** : get all the latest changes from the origin and merge

**git push** : is used to upload your local repository changes to the origin remote repo
