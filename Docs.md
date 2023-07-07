# Useful git commands

## git init
This command creates an empty Git repository on your local machine. So, basically a ```.git``` directory.

### Important Flags
- ```-q``` Stands for "quiet". Only print error and warning messages, nothing else.
- ```-b``` Use the specified name for the initial branch in the newly created repository. (e.g. "main" instead of the default "master")

<<<<<<< HEAD
## git stash 
git-stash - Stash the changes in a dirty working directory away

### Important Optionen
```pop``` Remove a single stashed state from the stash list and apply it on top of the current working tree state,
```apply``` Like ```pop```, but do not remove the state from the stash list. 
```clear``` Remove all the stash entries. 
```list``` List the stash entries that you currently have.
=======
# Make git add, git commit, git push --> Automatic in one command
### touch .bashrc
### nano .bashrc
###
### function doit() {
### 	git add .
###	git commit -a -m "$1"
###	git push
### }
###
###(type Strg + x)
###(type y)
###(hit enter)
###type in source .bashrc
##now you can do ...  doit "a new message"
##when you start your bash again you must do the ```source .bashrc``` again!

