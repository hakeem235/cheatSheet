# Git Cheat Sheet 

___

## GIT BASICS

### To create empty Git repo in specified directory. Run with no arguments to initialize the current directory as a git repository.

` git init <directory> `

### To clone repo located at <repo> onto local machine. Original repo can be located on the local filesystem or on a remote machine via HTTP or SSH.
  
  ` git clone <repo> `
### To define author name to be used for all commits in current repo. Devs commonly use --global flag to set config options for current user.
  
  `git config user.name <name>`
  
### To stage all changes in <directory> for the next commit. Replace <directory> with a <file> to change a specific file.

` git add <directory>`
  
### To commit the staged snapshot, but instead of launching a text editor, use <message> as the commit message.
  
  `git commit -m "<message>"`
  
### To list which files are staged, unstaged, and untracked.

  `git status`

### To display the entire commit history using the default format. For customization see additional options.

`git log`

### To Show unstaged changes between your index and working directory..

`git diff`


----

Resources: [ATLASSIAN](https://www.atlassian.com/git)
