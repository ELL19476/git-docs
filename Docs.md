# Useful git commands

## git init
This command creates an empty Git repository on your local machine. So, basically a ```.git``` directory.

### Important Flags
- ```-q``` Stands for "quiet". Only print error and warning messages, nothing else.
- ```-b``` Use the specified name for the initial branch in the newly created repository. (e.g. "main" instead of the default "master")

<<<<<<< HEAD
## git log
This command lists the history of git commits. The first one listed is the last commit

### Important Flags
- ```--oneline``` lists the whole log and each commit takes only one line
- ```--merges``` lists just the merge commits made
- ```--no-merges``` lists everything but the merges
- ```--stat``` lists everything and shows the files with the exact number of changes
- ```-n``` n stands for a number you choose. Then lists the recent n commits made
=======
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
>>>>>>> b457903d8eaeff53a5cc6273fe7379fadea00092
