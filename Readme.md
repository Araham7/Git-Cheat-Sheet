# 1. Set up Git user:
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

# 2. Check your current Git configuration:
```bash
git config --list
```

# 3. Set your default text editor for Git:
```bash
git config --global core.editor "nano"  # Replace with your editor (e.g., vim, code)
```



```
Git Setup
Set up Git user:
```
bash

git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Check your current Git configuration:
```
bash

git config --list
Set your default text editor for Git:
```
bash

git config --global core.editor "nano"  # Replace with your editor (e.g., vim, code)
Creating and Cloning Repositories
Initialize a new Git repository:
```
bash

git init
Clone an existing repository:
```
bash

git clone <repository_url>
Working with Files
Check the status of files in the repository:
```
bash

git status
Stage files for commit:

```ge specific file:
bash

git add <file_name>
```ge all changes:
bash

git add .
Commit changes with a message:
```
bash

git commit -m "Your commit message"
View changes before committing:
```
bash

git diff
Remove a file from staging (unstage it):
```
bash

git reset <file_name>
Remove a file from the repository and the working directory:
```
bash

git rm <file_name>
Branching and Merging
Create a new branch:
```
bash

git branch <branch_name>
Switch to a different branch:
```
bash

git checkout <branch_name>
Create and switch to a new branch in one command:
```
bash

git checkout -b <branch_name>
Merge another branch into the current branch:
```
bash

git merge <branch_name>
List all branches:
```
bash

git branch
Delete a branch:
```
bash

git branch -d <branch_name>
Remote Repositories
View remote repositories:
```
bash

git remote -v
Add a remote repository:
```
bash

git remote add origin <repository_url>
Push changes to a remote repository:
```
bash

git push origin <branch_name>
Pull changes from a remote repository:
```
bash

git pull origin <branch_name>
Fetch changes from a remote repository (without merging):
```
bash

git fetch origin
Remove a remote repository:
```
bash

git remote remove origin
Viewing History
View commit history:
```
bash

git log
View a summarized commit history:
```
bash

git log --oneline
View a specific commit:
```
bash

git show <commit_hash>
Undoing Changes
Undo the last commit (keep changes in the working directory):
```
bash

git reset --soft HEAD~1
Undo the last commit (discard changes in the working directory):
```
bash

git reset --hard HEAD~1
Unstage a file (undo git add):
```
bash

git reset <file_name>
Discard changes in a file (revert to the last committed version):
```
bash

git checkout -- <file_name>
Revert a commit (create a new commit that undoes a previous commit):
```
bash

git revert <commit_hash>
Advanced Commands
Stash changes (temporarily save changes):
```
bash

git stash
Apply the last stashed changes:
```
bash

git stash apply
Delete a stash:
```
bash

git stash drop
Show the current Git configuration:
```
bash

git config --list
Check which files are being tracked:
```
bash

git ls-files
```








# 1. To delete all previous Git tracking (i.e., remove the `.git` directory) in the current working directory (PWD), use the following command:
```bash
rm -rf .git
```




/* ------------------------------------------------------------------------------------------------ */

<!-- ![PDF Screenshot](path/to/image.png) -->
<iframe src="./git_cheat_sheet.pdf" height="600px"></iframe>

