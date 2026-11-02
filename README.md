# Git Learning

## 1. Git Version and Configuration

| Command | Why |
|---|---|
| `git -v` | Check Git version. |
| `git config --get user.name` | Check Git username. |
| `git config --get user.email` | Check Git email. |
| `git init` | Initialize Git in a folder. |

## 2. File Management and Staging

| Command | Why |
|---|---|
| `vim test.txt` | Create or edit a file. |
| `cat test.txt` | View file content. |
| `git status` | Check repository status. |
| `git add test.txt` | Add a file to the staging area. |
| `git rm --cached new.txt` | Remove a file from Git tracking but keep it locally. |
| `git rm -f anny.txt` | Force-remove a file from Git and the computer. |

## 3. Commit and History

| Command | Why |
|---|---|
| `git commit -m "message"` | Save staged changes as a commit. |
| `git log` | View commit history. |
| `git log --oneline` | View commit history in short format. |
| `git reset --hard <commit-id>` | Reset the branch and tracked files to a specific commit. |
| `git reflog` | View recent HEAD movements and find previous commit positions. |

## 4. Git Ignore

| Command | Why |
|---|---|
| `vim .gitignore` | Create or edit `.gitignore`. |
| `git add .gitignore` | Stage the `.gitignore` file. |
| `git add -f new.txt` | Force-add an ignored file. |

## 5. Branch Management

| Command | Why |
|---|---|
| `git branch --list` | List local branches. |
| `git branch dev` | Create a new branch. |
| `git switch dev` | Switch to another branch. |
| `git branch -m developer` | Rename the current branch. |
| `git branch -d developer` | Delete a safely merged branch. |

## 6. Merge and Conflict Resolution

| Command | Why |
|---|---|
| `git merge test` | Merge the `test` branch into the current branch. |
| `git status` | Check merge conflicts. |
| `git add anny.txt` | Mark conflict resolution as complete. |
| `git commit` | Complete the merge. |

## 7. Git Stash

| Command | Why |
|---|---|
| `git stash` | Temporarily save tracked, uncommitted changes. |
| `git stash list` | View saved stashes. |
| `git stash pop` | Restore the latest stash and remove it if successful. |
| `git stash -p` | Selectively stash changes. |
