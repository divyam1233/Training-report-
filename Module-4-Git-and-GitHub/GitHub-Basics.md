# 🐙 GitHub Basics

## 📘 Introduction
**GitHub** is a cloud-based platform built on top of Git.  
It provides hosting for Git repositories, along with collaboration tools such as **issues, pull requests, actions, and project boards**.  
It is widely used for **open-source projects, team collaboration, and version control**.

Prepared by: **Divyam Garg**  
URN: **2513993**  
Course Code: **TRCS‑201**

---

# 🔹 1. Key Features of GitHub
- **Repository Hosting** → Store and manage Git repositories online.  
- **Collaboration** → Multiple developers can contribute to the same project.  
- **Pull Requests (PRs)** → Propose changes and review code before merging.  
- **Issues** → Track bugs, tasks, and feature requests.  
- **GitHub Actions** → Automate workflows (CI/CD).  
- **Project Boards** → Organize tasks using Kanban-style boards.  

---

# 🔹 2. Creating a Repository on GitHub
1. Log in to [GitHub](https://github.com).  
2. Click **New Repository**.  
3. Enter repository name (e.g., `my-project`).  
4. Choose visibility → Public or Private.  
5. Initialize with a README (optional).  
6. Click **Create Repository**.

---

# 🔹 3. Connecting Local Repo to GitHub
```bash
# Step 1: Initialize local repo
git init

# Step 2: Add remote link
git remote add origin https://github.com/user/my-project.git

# Step 3: Push code to GitHub
git push -u origin main
