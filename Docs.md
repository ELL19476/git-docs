# Useful git commands

## git init
This command creates an empty Git repository on your local machine. So, basically a ```.git``` directory.

### Important Flags
- ```-q``` Stands for "quiet". Only print error and warning messages, nothing else.
- ```-b``` Use the specified name for the initial branch in the newly created repository. (e.g. "main" instead of the default "master")

## git log
This command lists the history of git commits. The first one listed is the last commit

### Important Flags
- ```--oneline``` lists the whole log and each commit takes only one line
- ```--merges``` lists just the merge commits made
- ```--no-merges``` lists everything but the merges
- ```--stat``` lists everything and shows the files with the exact number of changes
- ```-n``` n stands for a number you choose. Then lists the recent n commits made
