# Git commands

*This repo contains all the common and necessary git commands*

## Git set-up commands
> configuration of git to git-hub
```
git config --global user.email "someone@gmail.com"
git config --global user.name "zamani"
```
## checking status
```
git status
```
> the git status command is used to check if a directory is git enabled and also to check the status of our files whether staged ,committed or pushed


## initializing a repo
```
git-init
```
> git init is used to initialize a directory in a git repo

## staging changes
```
git add filename
git add . 
```
>the `git add filename` is used to stage a single file while` git add .` is used to add all file

## committing changes
```
git commit -m "commit message"
git commit -a -m "commit message"
```
>the first command in the code block above is used to commit a file that has been recently staged while the second command is used to add and commit a file that git is already tracking

## setting up a remote connection
- checking if a connection already exists
```
git remote -v
```
> this command is used to check if a remote command exists and is active
- adding a remote connection
```
git remote add connetcion-name connection-url
eg. git remote add origin http://github.com/username
```
> the above command is used to add a remote connection to your github 
- removing a remote connection
```
git remote remove connection-name 
eg. git remote remove origin 
```