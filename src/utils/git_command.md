# Basic Git Commands
| Purpose | Command |
|:--------|:--------|
| Initialize Git in a project | `git init` |
| Check Git status | `git status` |
| Add files to staging area | `git add filename` <br> or `git add .` (everything) |
| Commit changes | `git commit -m "your message"` |
| See commit history | `git log` |
| See a compact commit history | `git log --oneline` |
| Clone a remote repo | `git clone repo_url` |
| Push changes to remote | `git push origin branch_name` |
| Pull changes from remote | `git pull origin branch_name` |
| Create a new branch | `git branch branch_name` |
| Switch to another branch | `git checkout branch_name` |
| Create & switch to new branch | `git checkout -b branch_name` |
| Merge branch into current branch | `git merge branch_name` |


# Branch Management
| Purpose | Command |
|:--------|:--------|
| List all branches | `git branch` |
| Delete a local branch | `git branch -d branch_name` |
| Force delete a local branch | `git branch -D branch_name` |
| Delete a remote branch | `git push origin --delete branch_name` |
