# 🌿 Branching vs 🔗 Merging in Git

## 📘 Introduction
Git provides powerful features for managing parallel development.  
Two of the most important operations are **Branching** and **Merging**.  
Branching allows developers to work independently, while Merging combines those changes back into the main project.

Prepared by: **Divyam Garg**  
URN: **2513993**  
Course Code: **TRCS‑201**

---

# 🔹 1. Branching

- **Definition**: A branch is a separate line of development.  
- **Purpose**: Enables developers to work on new features, bug fixes, or experiments without affecting the main codebase.  
- **Default branch**: Usually `main` or `master`.  

👉 Commands:
```bash
git branch feature-xyz        # Create a new branch
git checkout feature-xyz      # Switch to the branch
git checkout -b feature-xyz   # Create and switch in one step


# 🔗 Git Merging

## 📘 Introduction
The **`git merge`** command is used to integrate changes from one branch into another.  
It combines independent lines of development into a unified project history.



---

# 🔹 1. Purpose of Merging
- Combines work from different branches.  
- Allows parallel development (features, bug fixes).  
- Maintains a unified project history.  
- Essential for collaboration in teams.

---

# 🔹 2. Basic Syntax
```bash
git checkout target-branch
git merge source-branch
