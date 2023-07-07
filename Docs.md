# Useful git commands

## git init
This command creates an empty Git repository on your local machine. So, basically a ```.git``` directory.

### Important Flags
- ```-q``` Stands for "quiet". Only print error and warning messages, nothing else.
- ```-b``` Use the specified name for the initial branch in the newly created repository. (e.g. "main" instead of the default "master")

## git stash 
git-stash - Stash the changes in a dirty working directory away

### Important Optionen
```pop``` Remove a single stashed state from the stash list and apply it on top of the current working tree state,
```apply``` Like ```pop```, but do not remove the state from the stash list. 
```clear``` Remove all the stash entries. 
```list``` List the stash entries that you currently have.