# ⚙️ Git Operations: commit, add, status, and log

## 📘 Introduction
Git provides essential operations to manage project history.  
The most commonly used commands are **`git add`**, **`git commit`**, **`git status`**, and **`git log`**.  
Together, they form the backbone of version control.

Prepared by: **Divyam Garg**  
URN: **2513993**  
Course Code: **TRCS‑201**

---

# 🔹 1. git add
Stages changes from the **Working Tree** to the **Staging Area**.

```bash
git add filename      # Stage a specific file
git add .             # Stage all changes in the directory

# 📝 Git Commit

## 📘 Introduction
The **`git commit`** command is used to save changes from the **Staging Area** into the repository history.  
Each commit creates a permanent snapshot of your project at a specific point in time.



---

# 🔹 1. Purpose of git commit
- Records changes permanently in the repository.  
- Creates a unique **commit ID (SHA‑1 hash)**.  
- Allows developers to roll back or review history.  
- Forms the backbone of version control in Git.

---

# 🔹 2. Basic Syntax
```bash
git commit -m "Commit message"


# 📊 Git Status

## 📘 Introduction
The **`git status`** command shows the current state of the **Working Tree** and **Staging Area**.  
It helps developers understand which files are **modified, staged, or untracked** before committing.



---

# 🔹 1. Purpose of git status
- Displays the branch you are working on.  
- Shows files that are **modified but not staged**.  
- Lists **untracked files** (new files not added to Git).  
- Confirms which files are staged and ready to commit.  

---

# 🔹 2. Basic Syntax
```bash
git status


# 📜 Git Log

## 📘 Introduction
The **`git log`** command displays the commit history of a repository.  
It shows details such as **commit ID, author, date, and commit message**, helping developers track changes over time.



---

# 🔹 1. Purpose of git log
- View the history of commits.  
- Identify who made changes and when.  
- Debug issues by reviewing past changes.  
- Understand the evolution of a project.  

---

# 🔹 2. Basic Syntax
```bash
git log
