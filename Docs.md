# Useful git commands

## git init
This command creates an empty Git repository on your local machine. So, basically a ```.git``` directory.

### Important Flags
- ```-q``` Stands for "quiet". Only print error and warning messages, nothing else.
- ```-b``` Use the specified name for the initial branch in the newly created repository. (e.g. "main" instead of the default "master")

## git rm [file]
delete the file from project and stage the remowal for commit

### Important Flags
- ```--cached``` Removes the file only from the Git repository, but not from the filesystem.
