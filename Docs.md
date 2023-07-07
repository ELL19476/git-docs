# Useful git commands

## git init
This command creates an empty Git repository on your local machine. So, basically a ```.git``` directory.

### Important Flags
- ```-q``` Stands for "quiet". Only print error and warning messages, nothing else.
- ```-b``` Use the specified name for the initial branch in the newly created repository. (e.g. "main" instead of the default "master")

<<<<<<< HEAD
<<<<<<< HEAD
## git push
The git push command is used to upload local repository content to a remote repository.

### Important Flags
- ```-u``` or ```--set-upstream``` Set the upstream.

=======
<<<<<<< HEAD
=======

## git clone
This command is used to create a copy of a Git repository  on your local machine, including all its files, commit history, and branches. It allows you to download and have a complete, editable version of the repository that you can work with and contribute to.

### Important Flags
- ```--depth``` This flag allows you to specify the number of commits to include in the cloned repository, which can make the cloning process faster and use less disk space. 
- ```--branch``` This flag lets you specify a particular branch to clone instead of the default branch.


>>>>>>> ee1fc3865f92e97ac33fa138bb55cd22d9b328a5
## git stash 
git-stash - Stash the changes in a dirty working directory away

### Important Optionen
```pop``` Remove a single stashed state from the stash list and apply it on top of the current working tree state,
```apply``` Like ```pop```, but do not remove the state from the stash list. 
```clear``` Remove all the stash entries. 
```list``` List the stash entries that you currently have.

## Make git add, git commit, git push --> Automatic in one command
### touch .bashrc
### nano .bashrc
###
### function doit() {
### 	git add .
### 	git commit -a -m "$1"
###	    git push
### }
###
### (type Strg + x)
### (type y)
### (hit enter)
### type in source .bashrc
### now you can do ...  doit "a new message"
### when you start your bash again you must do the ```source .bashrc``` again!

>>>>>>> refs/remotes/origin/main
=======

### Usage: git reset [file]  

This command unstages the file, but it preserves the file contents.
>>>>>>> ee1fc3865f92e97ac33fa138bb55cd22d9b328a5
>>>>>>> c6148d1096c94bf9b42a7f59350c6df818fe2fd7
