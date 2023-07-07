# Useful git commands

## git init
This command creates an empty Git repository on your local machine. So, basically a ```.git``` directory.

### Important Flags
- ```-q``` Stands for "quiet". Only print error and warning messages, nothing else.
- ```-b``` Use the specified name for the initial branch in the newly created repository. (e.g. "main" instead of the default "master")

## git clone
This command is used to create a copy of a Git repository  on your local machine, including all its files, commit history, and branches. It allows you to download and have a complete, editable version of the repository that you can work with and contribute to.

### Important Flags
- ```--depth``` This flag allows you to specify the number of commits to include in the cloned repository, which can make the cloning process faster and use less disk space. 
- ```--branch``` This flag lets you specify a particular branch to clone instead of the default branch.

## git stash 
git-stash - Stash the changes in a dirty working directory away

### Important Optionen
```pop``` Remove a single stashed state from the stash list and apply it on top of the current working tree state,
```apply``` Like ```pop```, but do not remove the state from the stash list. 
```clear``` Remove all the stash entries. 
```list``` List the stash entries that you currently have.

## Make git add, git commit, git push --> Automatic in one command
# touch .bashrc
# nano .bashrc

# function doit() {
# 	git add .
#	git commit -a -m "$1"
#	git push
# }
#
#(type Strg + x)
#(type y)
#(hit enter)
#type in source .bashrc
#now you can do ...  doit "a new message"
### when you start your bash again you must do the ```source .bashrc``` again!

## git restore --staged <filename>
This command removes the file from the tracked status
