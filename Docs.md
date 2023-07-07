# git init

This command creates an empty Git repository on your local machine. So, basically a ```.git``` directory.

---

## Important Flags

- ```--bare``` Create a bare repository. If GIT_DIR environment is not set, it is set to the current working directory.

---

- ```--shared[=(false|true|umask|group|all|world|everybody|<perm>)]``` Specify that the Git repository is to be shared amongst several users. This allows users belonging to the same group to push into that repository. When specified, the config variable "core.sharedRepository" is set so that files and directories under $GIT_DIR are created with the requested permissions. When not specified, Git will use permissions reported by umask(2).

---

## git checkout
Switch branches or restore working tree files


>>>>>>> 53bbe7c74217f9dbbaee91d3b7e271096a788a06
=======
>>>>>>> f7e5ba3b05ab5c67989568e78c79ca630b8c7cbb
---
## git commit
This command performs a commit, it's used to save changes to the local repository.

## git status
Shows the current state of the repository, including modified files and files in the staging area.

## git log
This command lists the history of git commits. The first one listed is the last commit

### Important Flags
- ```--oneline``` lists the whole log and each commit takes only one line
- ```--merges``` lists just the merge commits made
- ```--no-merges``` lists everything but the merges
- ```--stat``` lists everything and shows the files with the exact number of changes
- ```-n``` n stands for a number you choose. Then lists the recent n commits made


## git add
The "add" command marks changes to be included in the next commit.
It adds changes to Git's "Staging Area", the contents of which can then be wrapped up in a new revision with the "git commit" command.

### Important Flags for git add

```--all``` Adds all modifications to the Staging Area. This includes changed files, deleted files, and new files - anywhere inside the project directory.

```-u``` Adds all changes to existing files to the Staging Area. This includes changed files and deleted files - but not new files that aren't currently tracked by Git.  

### Important Flags
- ```-m``` Stands for "message". Is used to add a commit message to a commit.
- ```-a``` Tells Git to add all files that have been modified and then commit them. 


<<<<<<< HEAD
<<<<<<< HEAD

>>>>>>> bfbf5a2dfbde65b9f8c7308f976b18ffbebf411b
=======
>>>>>>> fdacb72e4b9f32000bd0f96f50bb8618c9da5eea
=======

>>>>>>> f7e5ba3b05ab5c67989568e78c79ca630b8c7cbb
## Important Flags

- ```--bare``` Create a bare repository. If GIT_DIR environment is not set, it is set to the current working directory.

---

- ```--shared[=(false|true|umask|group|all|world|everybody|<perm>)]``` Specify that the Git repository is to be shared amongst several users. This allows users belonging to the same group to push into that repository. When specified, the config variable "core.sharedRepository" is set so that files and directories under $GIT_DIR are created with the requested permissions. When not specified, Git will use permissions reported by umask(2).


## git push
The git push command is used to upload local repository content to a remote repository.


### Important Flags
- ```-u``` or ```--set-upstream``` Set the upstream.



## git merge
This command merges changes from one branch into another branch.


## git ls-tree -r main
The command ```git ls-tree -r main``` is used to list the contents of the specified branch (main in this case) recursively. It displays the tree objects and file names in the repository.

### Important Flags
- ```-r``` Recurse into sub-trees.
- ```-l```  Show object size of blob (file) entries.

<<<<<<< HEAD
<<<<<<< HEAD
=======
=======
<<<<<<< HEAD
>>>>>>> 4c204217c461ba83d1195c26e726da70225bba78
=======
>>>>>>> e691af77b4fd6c7012e254eb7315e3c7a142764f
=======
>>>>>>> bfbf5a2dfbde65b9f8c7308f976b18ffbebf411b

## git rm [file]
delete the file from project and stage the remowal for commit

### Important Flags
- ```--cached``` Removes the file only from the Git repository, but not from the filesystem.


=======
>>>>>>> fdacb72e4b9f32000bd0f96f50bb8618c9da5eea
=======

>>>>>>> f7e5ba3b05ab5c67989568e78c79ca630b8c7cbb
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

### touch .bashrc
### nano .bashrc
###
### function doit() {
### 	git add .
### 	git commit -a -m "$1"
###	    git push
### }
###
###(type Strg + x)
###(type y)
###(hit enter)
###type in source .bashrc
##now you can do ...  doit "a new message"
##when you start your bash again you must do the ```source .bashrc``` again!

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
<<<<<<< HEAD
### (type Strg + x)
### (type y)
### (hit enter)
### type in source .bashrc
### now you can do ...  doit "a new message"
### when you start your bash again you must do the ```source .bashrc``` again!




### (type Strg + x)
### (type y)
### (hit enter)
### type in source .bashrc
### now you can do ...  doit "a new message"
### when you start your bash again you must do the ```source .bashrc``` again!

``` touch .bashrc
``` nano .bashrc

``` function doit() {
``` 	git add .
``` 	git commit -a -m "$1"
```	    git push
``` }
```
``` (type Strg + x)
``` (type y)
``` (hit enter)
``` type in source .bashrc

## now you can do ...  doit "a new message"
## when you start your bash again you must do the ```source .bashrc``` again!


### Usage: git reset [file]  

<<<<<<< HEAD
<<<<<<< HEAD
This command unstages the file, but it preserves the file contents.
<<<<<<< HEAD
<<<<<<< HEAD


=======
>>>>>>> ee1fc3865f92e97ac33fa138bb55cd22d9b328a5
<<<<<<< HEAD
=======
<<<<<<< HEAD
=======
>>>>>>> c6148d1096c94bf9b42a7f59350c6df818fe2fd7
>>>>>>> 4c204217c461ba83d1195c26e726da70225bba78
>>>>>>> e691af77b4fd6c7012e254eb7315e3c7a142764f
<<<<<<< HEAD
=======
=======

>>>>>>> bfbf5a2dfbde65b9f8c7308f976b18ffbebf411b
>>>>>>> dd941d5e735d8f49c5371dbd0b7bc19934660814
=======
This command unstages the file, but it preserves the file contents.
>>>>>>> fdacb72e4b9f32000bd0f96f50bb8618c9da5eea
=======
This command unstages the file, but it preserves the file contents.


### Usage: git reset [file]  

This command unstages the file, but it preserves the file contents.

>>>>>>> f7e5ba3b05ab5c67989568e78c79ca630b8c7cbb
