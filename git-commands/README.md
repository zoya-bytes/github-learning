| COMMANDS   | INFORMATION  |SYNTAX    |
| -------- | ------- |-------- |
| GIT CLONE | This command is used to copy an existing remote(hosted location) repository int to the local machine (in your computer).  |git clone  (Remote URL Path) eg: ssh://@github.com....  |
| GIT CHECKOUT| This command allows you to create and switch another new branch.   | git checkout -b (New Branch name) |
 FILE CHANGE |You can use either Visual Studio (VSC) Code or VIM (Vi IMproved) Editor to change or edit the file.|Visual Studio Code : code .
 GIT PULL ORIGIN |This command is used to pull the data from the remote repo named Origin to the local branch.|git pull origin 
 GIT STATUS |This command shows modified files on the working directory, staged, for the next commit.  It allows you to see staged changes and files that are not being tracked by git. If there is a conflict in the merge, git status will show which files are the source of conflicts.| git status
 GIT ADD |This command adds new or changed files in your working directory to your next commit stage. By this command you tell git that you want to add updates to a certain file in next commit.|git add (File name which you want to add)
 GIT COMMIT|This command commits your staged content as a new commit snapshot. In other words, this command is used to create a new commit in a repository. |git commit  -m  (message)
 Git commit and Add |This command is used to create a new commit in a GIT repository and add all staged changes to the commit.|git commit -am (message)
 GIT PUSH |This command is used to send changes from your local repository to a remote repository. Push a branch to your remote repository.|git push origin (branch name)     
 GIT PULL|This command is used to update your present working branch and all of the remote tracking branches. Without running the git pull command your local repository will never be updated with the changes from the remote. |git pull|