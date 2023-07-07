# git init

This command creates an empty Git repository on your local machine. So, basically a ```.git``` directory.

---
## git commit
This command performs a commit, it's used to save changes to the local repository.

### Important Flags
- ```-m``` Stands for "message". Is used to add a commit message to a commit.
- ```-a``` Tells Git to add all files that have been modified and then commit them. 



=======
<<<<<<< HEAD
<<<<<<< HEAD
=======
>>>>>>> bfbf5a2dfbde65b9f8c7308f976b18ffbebf411b
## Important Flags

- ```--bare``` Create a bare repository. If GIT_DIR environment is not set, it is set to the current working directory.

---

- ```--shared[=(false|true|umask|group|all|world|everybody|<perm>)]``` Specify that the Git repository is to be shared amongst several users. This allows users belonging to the same group to push into that repository. When specified, the config variable "core.sharedRepository" is set so that files and directories under $GIT_DIR are created with the requested permissions. When not specified, Git will use permissions reported by umask(2).

<<<<<<< HEAD
---
=======
<<<<<<< HEAD
>>>>>>> e691af77b4fd6c7012e254eb7315e3c7a142764f
=======

>>>>>>> bfbf5a2dfbde65b9f8c7308f976b18ffbebf411b
## git push
The git push command is used to upload local repository content to a remote repository.

### Important Flags
- ```-u``` or ```--set-upstream``` Set the upstream.

<<<<<<< HEAD
<<<<<<< HEAD
## git ls-tree -r main
The command ```git ls-tree -r main``` is used to list the contents of the specified branch (main in this case) recursively. It displays the tree objects and file names in the repository.

### Important Flags
- ```-r``` Recurse into sub-trees.
- ```-l```  Show object size of blob (file) entries.

=======
=======
<<<<<<< HEAD
>>>>>>> 4c204217c461ba83d1195c26e726da70225bba78
=======
>>>>>>> e691af77b4fd6c7012e254eb7315e3c7a142764f
=======
>>>>>>> bfbf5a2dfbde65b9f8c7308f976b18ffbebf411b

## git clone
This command is used to create a copy of a Git repository  on your local machine, including all its files, commit history, and branches. It allows you to download and have a complete, editable version of the repository that you can work with and contribute to.

### Important Flags
- ```--depth``` This flag allows you to specify the number of commits to include in the cloned repository, which can make the cloning process faster and use less disk space. 
- ```--branch``` This flag lets you specify a particular branch to clone instead of the default branch.

<<<<<<< HEAD
=======

>>>>>>> bfbf5a2dfbde65b9f8c7308f976b18ffbebf411b
## git stash 
git-stash - Stash the changes in a dirty working directory away

### Important Optionen
```pop``` Remove a single stashed state from the stash list and apply it on top of the current working tree state,
```apply``` Like ```pop```, but do not remove the state from the stash list. 
```clear``` Remove all the stash entries. 
```list``` List the stash entries that you currently have.

## Make git add, git commit, git push --> Automatic in one command
<<<<<<< HEAD
### touch .bashrc
### nano .bashrc
###
### function doit() {
### 	git add .
### 	git commit -a -m "$1"
###	    git push
### }
###
<<<<<<< HEAD
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
=======
### (type Strg + x)
### (type y)
### (hit enter)
### type in source .bashrc
### now you can do ...  doit "a new message"
### when you start your bash again you must do the ```source .bashrc``` again!

>>>>>>> refs/remotes/origin/main
=======
>>>>>>> e691af77b4fd6c7012e254eb7315e3c7a142764f
=======
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


>>>>>>> bfbf5a2dfbde65b9f8c7308f976b18ffbebf411b

### Usage: git reset [file]  

This command unstages the file, but it preserves the file contents.
<<<<<<< HEAD
<<<<<<< HEAD


=======
>>>>>>> ee1fc3865f92e97ac33fa138bb55cd22d9b328a5
<<<<<<< HEAD
=======
>>>>>>> c6148d1096c94bf9b42a7f59350c6df818fe2fd7
>>>>>>> 4c204217c461ba83d1195c26e726da70225bba78
>>>>>>> e691af77b4fd6c7012e254eb7315e3c7a142764f
=======

>>>>>>> bfbf5a2dfbde65b9f8c7308f976b18ffbebf411b
