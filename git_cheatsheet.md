# Git Cheat Sheet 

___

## GIT BASICS

### To create empty Git repo in specified directory. Run with no arguments to initialize the current directory as a git repository.

` git init <directory> `

### To clone repo located at <repo> onto local machine. Original repo can be located on the local filesystem or on a remote machine via HTTP or SSH.
  
  ` git clone <repo> `
### To define the author email to be used for all commits by the current user
  
  `git config --global user.email <email>`
  
### To reate shortcut for a Git command. E.g. alias.glog “log --graph --oneline” will set ”git glog” equivalent to ”git log --graph--oneline.

` git config --global alias.<alias-name> <git-command>`
  
### To set text editor used by commands for all users on the machine. <editor> arg should be the command that launches the desired editor (e.g., vi).
  
  `git config --system core.editor <editor>`
  
### To open the global configuration file in a text editor for manual editing.
  
  `git config --global --edit`
