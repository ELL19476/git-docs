# Useful git commands

## git init
This command creates an empty Git repository on your local machine. So, basically a ```.git``` directory.

### Important Flags
- ```-q``` Stands for "quiet". Only print error and warning messages, nothing else.
- ```-b``` Use the specified name for the initial branch in the newly created repository. (e.g. "main" instead of the default "master")

## git ls-tree -r main
The command ```git ls-tree -r main``` is used to list the contents of the specified branch (main in this case) recursively. It displays the tree objects and file names in the repository.

### Important Flags
- ```-r``` Recurse into sub-trees.
- ```-l```  Show object size of blob (file) entries.

## Make git add, git commit, git push --> Automatic in one command
touch .bashrc
nano .bashrc

function doit() {
	git add .
	git commit -a -m "$1"
	git push
}

(type Strg + x)
(type y)
(hit enter)
type in source .bashrc
now you can do ...  doit "a new message"
### when you start your bash again you must do the ```source .bashrc``` again!

