Q.What is the difference between git add and git commit?
The main differnce betwwen the git add and git commit, git add is used to stage file from untracked file and modified file whereas git commit is used cimmit the chnages from staging area.
Command : git add And git Commit

Q.What does the staging area do? Why doesn't Git just commit directly?
The Staging Area also Called as the Staging Environment, aslo referred to as inde, a place where we make changes before commiting them.
Because, For Preparing changes before commit staging is used, commit is used for finalizing these changes.

Git Stage Commands:
1) git add
2) git add .
3) git status
4) git restore --staged filename
5) git rm --cached filename

Q.What information does git log show you?
It Show you Commit History,Commit Message,  Who made the changes, time when change made, author name, commit id.

Q.What is the .git/ folder and what happens if you delete it?
.git folder is a hidden folder in git system, which indicates that current directory is git repository, and git is watching it , and tracking the code changes, if we delete it, the repository will not be treated as git repository, also commit history will be lost, files will remain there, but without version control system.

Q.What is the difference between a working directory, staging area, and repository?
A) Working Directory is normal folder, staging area, where we prepare changes before commiting them, repository stores all versions of your project.
