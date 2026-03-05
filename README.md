# Git Practice Lab - CodeTest.py

This repository is created for **hands-on Git practice** with a single Python file, `CodeTest.py`.  
It demonstrates creating commits, deleting commits, amending commits, and reverting changes while learning Git workflows.

---

## 🗂 Repository Overview

| File Name      | Purpose |
|----------------|---------|
| `CodeTest.py`  | A Python file used to practice Git commands including commit, reset, amend, and revert. |

---

## Lab Exercises Completed

1. Make **4 commits** in the repository.  
2. **Delete the last 2 commits** using `git reset`.  
3. Add a **new commit** after deletion with the message `"commit after deletion"`.  
4. Amend the last commit by adding `"lab Done"` at the end of the file.  
5. Update the amended commit message to `"finish"`.  
6. Revert the last 3 commits using `git revert`.  

---

## 💻 Git Commands Used

```bash id="r4heaw"
# Initialize a repository
git init

# Check status
git status

# Add a file
git add CodeTest.py

# Commit changes
git commit -m "commit 1"
git commit -m "commit 2"
git commit -m "commit 3"
git commit -m "commit 4"

# View commit history
git log --oneline

# Delete last 2 commits
git reset --hard HEAD~2

# Add a new commit after deletion
git add CodeTest.py
git commit -m "commit after deletion"

# Amend last commit by adding changes
git add CodeTest.py
git commit --amend -m "finish"

# Revert a specific commit
git revert HEAD~2

# Connect to remote repository using SSH
git remote add origin git@github.com:YasmeenMohamed322/GitHub-Tasks.git

# Push commits to remote
git push -u origin main

---

