≠# Command Line Definitions

## cd - change directory/folder

## ls - list directory contents/shows everything inside current folder

## ls -a - shows visible and hidden files/directories

## man <command> - displays manual for given command

## mkdir <foldername> - make directory with given name (folder)

## pwd - print working directory/shows you where you currently are

## touch <filename> - create file with given name

## cd .. - move up one directory

## cd ~ - home

# Git Definitions

## git init - initialize an empty repository/makes a directory a repository by putting a .git folder into it
 
## git add <filename> - moves a modified file to the staging area

## git commit -m "<message" -moves staged files to the Git Directory and labels the commit with a message for other developers

## git config --global user.name - changes or sets your global username

## git config --global user.email - change or set global email address

## git config --global --list - displays your global settings

## git config --global core.editor <editor of choice> - set your global editor 

## git commit --amend -m "<new message>" - changes the commit message of the last commit to the new message 

## git commit --amend - if you forgot to add a file or you have a misspelling in your commit message.
## Overwrites the previous commit with new files and message.

## git reset HEAD <filename> - moves the staged file from the Staging Area to the Working Directory

## git checkout -- <filename> - removes any changes made to the file and reverts it's status back to unmodified

## git branch <branchname> - create a new branch with the given name

## git checkout <branchname> - switch to a new branch

## git checkout -b <branchname> - create new branch and switch to it

## git branch -d <branchname> - delete existing branch with given name

## git branch - shows all current branches and what branch you're currently on

## git merge <branchname> - merges the histories of two branches into a single branch
## Merge Steps
1. checkout the branch you want to merge changes into.
2. git merge branch you want to merge into current branch

