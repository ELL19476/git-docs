# Useful git commands

## git init
This command creates an empty Git repository on your local machine. So, basically a ```.git``` directory.

### Important Flags
- ```-q``` Stands for "quiet". Only print error and warning messages, nothing else.
- ```-b``` Use the specified name for the initial branch in the newly created repository. (e.g. "main" instead of the default "master")

## git add
The "add" command marks changes to be included in the next commit.
It adds changes to Git's "Staging Area", the contents of which can then be wrapped up in a new revision with the "git commit" command.

### Important Flags for git add

```--all``` Adds all modifications to the Staging Area. This includes changed files, deleted files, and new files - anywhere inside the project directory.

```-u``` Adds all changes to existing files to the Staging Area. This includes changed files and deleted files - but not new files that aren't currently tracked by Git.  