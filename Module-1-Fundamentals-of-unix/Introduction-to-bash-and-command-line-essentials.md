# 🐚 Linux Shell and Bash Training Report

## 📘 Introduction
This report provides a detailed explanation of essential Linux concepts:  
- Shell and Bash basics  
- Filesystem hierarchy  
- File and directory permissions  
- Basic file operations  
- Redirection and pipes  
- Wildcards, quoting, and escaping characters  

Prepared by: **Divyam Garg**  
URN: **2513993**  
Course Code: **TRCS‑201**

---

# 🔹 1. Shell and Bash

- **Shell**: A command-line interface to interact with the operating system.  
- **Bash (Bourne Again Shell)**: The most widely used Linux shell, offering scripting capabilities and advanced features.  

👉 Example:
```bash
echo "Hello, Linux!"


# 🔹 Filesystem Structure
# 📂 Linux Filesystem Structure

## 📘 Introduction
Linux uses a **hierarchical directory structure** starting from the root `/`.  
Every file and directory is organized under this tree.  
Understanding these directories is essential for system administration.

---

## 🔹 Key Directories

| Directory | Purpose |
|-----------|---------|
| `/`       | Root directory, base of the filesystem |
| `/home`   | User home directories (e.g., `/home/divyam`) |
| `/etc`    | System configuration files |
| `/var`    | Variable data (logs, spool files, cache) |
| `/boot`   | Kernel and bootloader files |

---

## 🔹 Examples

### Navigate to `/home`
```bash
cd /home
ls

# 🔐 File and Directory Permissions in Linux

## 📘 Introduction
Linux uses a permission system to control **who can read, write, or execute files and directories**.  
This ensures security and proper access management in multi‑user environments.

---

## 🔹 Permission Types

- **Read (r)** → View contents of a file or list a directory.  
- **Write (w)** → Modify contents of a file or add/remove files in a directory.  
- **Execute (x)** → Run a file as a program or enter a directory.  

---

## 🔹 Permission Representation

Permissions are shown in **symbolic** or **numeric (octal)** form.

### Symbolic Example:
```bash
-rwxr-xr--


# 📂 Basic File Operations in Linux

## 📘 Introduction
Linux provides powerful commands to manage files and directories.  
The most commonly used operations are **listing, copying, moving, renaming, and deleting files**.  

---

## 🔹 Common Commands

| Command | Purpose |
|---------|---------|
| `ls`    | List files and directories |
| `cp`    | Copy files or directories |
| `mv`    | Move or rename files/directories |
| `rm`    | Remove (delete) files or directories |
| `pwd`   | Show current working directory |

---

## 🔹 Examples

### 1. List Files
```bash
ls
ls -l        # Detailed list
ls -a        # Show hidden files


# 🔄 Redirection and Pipes | ✨ Wildcards, Quoting, Escaping

## 📘 Introduction
Linux provides powerful features for handling input/output and text processing.  
This section covers **redirection**, **pipes**, and **special character handling**.

---

# 🔹 1. Redirection

- `>` → Redirect output (overwrite existing file)  
- `>>` → Redirect output (append to file)  
- `<` → Redirect input from a file  

👉 Examples:
```bash
ls > files.txt        # Save output to files.txt (overwrite)
echo "New line" >> notes.txt   # Append text to notes.txt
sort < unsorted.txt   # Take input from unsorted.txt

# 📦 Pipes in Linux

## 📘 Introduction
A **pipe (`|`)** in Linux connects the output of one command to the input of another.  
This allows chaining commands together to process data efficiently without creating temporary files.

---

## 🔹 How Pipes Work
- **Command1 | Command2** → Output of Command1 becomes input for Command2.  
- Pipes can be chained multiple times to build powerful workflows.

---

## 🔹 Examples

### 1. Filter Files
```bash
ls | grep ".txt"


# ✨ Wildcards in Linux

## 📘 Introduction
Linux provides **wildcards** for flexible file matching and **quoting** methods to control how text and variables are interpreted.  
These are essential for working with files and writing shell scripts.

---

# 🔹 1. Wildcards

Wildcards allow pattern matching in filenames:

- `*` → Matches any number of characters  
- `?` → Matches a single character  
- `[ ]` → Matches any one character inside the brackets  

👉 Examples:
```bash
ls *.txt        # List all files ending with .txt
ls file?.txt    # Match file1.txt, file2.txt
ls [abc]*.log   # Match files starting with a, b, or c and ending with .log
