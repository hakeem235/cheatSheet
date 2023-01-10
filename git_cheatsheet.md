# Git Cheat Sheet 

___

## GIT BASICS

### Create empty Git repo in specified directory. Run with no arguments to initialize the current directory as a git repository.

` git init <directory> `

### Clone repo located at <repo> onto local machine. Original repo can be located on the local filesystem or on a remote machine via HTTP or SSH.
  
  ` git clone <repo> `
### Define author name to be used for all commits in current repo. Devs commonly use --global flag to set config options for current user.
  
  `git config user.name <name>`
  
### Stage all changes in <directory> for the next commit. Replace <directory> with a <file> to change a specific file.

` git add <directory>`
  
### Commit the staged snapshot, but instead of launching a text editor, use <message> as the commit message.
  
  `git commit -m "<message>"`
  
### List which files are staged, unstaged, and untracked.

  `git status`

### Display the entire commit history using the default format. For customization see additional options.

`git log`

### Show unstaged changes between your index and working directory.

`git diff`

___
## UNDOING CHANGES

### Create new commit that undoes all of the changes made in <commit>, then apply it to the current branch.

`git revert <commit>`
### Remove <file> from the staging area, but leave the working directory unchanged. This unstages a file without overwriting any changes.

`git reset <file>`

### Shows which files would be removed from working directory. Use the -f flag in place of the -n flag to execute the clean.
` git clean -n `

___

## GIT BRANCHES

### List all of the branches in your repo. Add a <branch> argument to create a new branch with the name <branch>.

`git branch`

### Create and check out a new branch named <branch>.Drop the -b flag to checkout an existing branch.
`git checkout -b <branch>`
### Merge <branch> into the current branch.
`git merge <branch>`
____

## REMOTE REPOSITORIES
----

Resources: [ATLASSIAN](https://www.atlassian.com/git)
