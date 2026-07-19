# 🦊 GitLab Basics

## 📘 Introduction
**GitLab** is a web-based DevOps platform that provides a complete **CI/CD pipeline** along with Git repository hosting.  
It is similar to GitHub but focuses heavily on **automation, DevOps lifecycle management, and self-hosting options**.

Prepared by: **Divyam Garg**  
URN: **2513993**  
Course Code: **TRCS‑201**

---

# 🔹 1. Key Features of GitLab
- **Repository Hosting** → Store and manage Git repositories.  
- **CI/CD Pipelines** → Automate build, test, and deployment.  
- **Issue Tracking** → Manage bugs, tasks, and features.  
- **Merge Requests (MRs)** → Review and merge code changes.  
- **Self-Hosting** → Install GitLab on your own server.  
- **Project Management** → Boards, milestones, and epics for agile workflows.  

---

# 🔹 2. Creating a Repository on GitLab
1. Log in to [GitLab](https://gitlab.com).  
2. Click **New Project**.  
3. Enter project name (e.g., `my-project`).  
4. Choose visibility → Public, Internal, or Private.  
5. Initialize with a README (optional).  
6. Click **Create Project**.

---

# 🔹 3. Connecting Local Repo to GitLab
```bash
# Step 1: Initialize local repo
git init

# Step 2: Add remote link
git remote