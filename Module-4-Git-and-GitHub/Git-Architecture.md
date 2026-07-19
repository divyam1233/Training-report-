# 📂 Git Repository

## 📘 Introduction
A **Git repository (repo)** is a storage space where your project files and their entire version history are kept.  
It allows developers to track changes, collaborate, and roll back to previous versions when needed.

Prepared by: **Divyam Garg**  
URN: **2513993**  
Course Code: **TRCS‑201**

---

# 🔹 1. Types of Git Repositories
- **Local Repository** → Stored on your computer.  
- **Remote Repository** → Hosted on platforms like GitHub, GitLab, or Bitbucket.  

---

# 🔹 2. Creating a Repository

### Initialize a new repo
```bash
git init


# 🌳 Git Working Tree

## 📘 Introduction
The **Git Working Tree** (also called the **Working Directory**) is the area where you actively edit files.  
It contains the actual project files that you see and modify on your computer.  
Changes made here are not yet tracked by Git until they are staged and committed.


---

# 🔹 1. Git Areas Overview

Git manages files in three main areas:

| Area | Description |
|------|-------------|
| **Working Tree** | Your local files that you edit (untracked or modified). |
| **Staging Area (Index)** | Files marked to be included in the next commit. |
| **Repository (.git)** | Permanent history of commits stored in Git. |

---

# 🔹 2. Workflow with Working Tree

1. **Edit files** → Changes happen in the **Working Tree**.  
2. **Stage changes** → Move files to the **Staging Area**.  
   ```bash
   git add filename
