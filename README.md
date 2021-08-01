# GIT
<img src="images/git.jpg" alt="logo">

## Configuration
```bash
> git config --global user.name "name"
> git config --global user.email "example@gmail.com"
> git config --global color.ui true
```

## Create Project
```bash
> mkdir project-name
> cd project-name
> git init
```

## Create file
```bash
# created file - status "untrfcked"
> git add file # status "staged"
> git commit # status "committed"
```
## Change file
```bash
# changed file - status "modified"
> git add # status "staged"
> git commit # ststus "commited"
```
## Basic commands
```bash
> git status # current status of the repository
> git add # add files
> git commit -m "message" # make a commit
> git log # history of commits
```
### Different ways to do git add
```bash
> git add file1 file2
> git add .
> git add *.js # all files in the current folder with the extension .js
> git add dir/*.js
> git add dir/
> git add ".js" # all files in the project with the extension .js
```