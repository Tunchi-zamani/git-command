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