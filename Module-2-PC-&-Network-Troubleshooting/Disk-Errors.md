# 💽 Disk Errors and Formatting Utilities

## 📘 Introduction
Disk errors can cause data loss, slow performance, or prevent the system from booting.  
Formatting utilities help prepare storage devices for use by creating or resetting file systems.  
This section covers **common disk error checks** and **formatting tools** in Windows and Linux.

Prepared by: **Divyam Garg**  
URN: **2513993**  
Course Code: **TRCS‑201**

---

# 🔹 1. Common Disk Errors

### Symptoms
- Slow read/write performance  
- "Disk read error" messages  
- Clicking or grinding noises (HDD)  
- Bad sectors detected  

### Causes
- Physical damage  
- Corrupted file system  
- Improper shutdowns  
- Malware infections  

---

# 🔹 2. Disk Error Checking (Windows)

### CHKDSK Utility
```bash
chkdsk C: /f /r


# 💽 Formatting Utilities

## 📘 Introduction
Formatting utilities are tools used to prepare storage devices (HDD, SSD, USB drives) by creating or resetting a **file system**.  
They are essential for initializing new drives, repairing corrupted partitions, or changing file system types.


---

# 🔹 1. Windows Formatting Utilities

### Format Command (Command Prompt)
```bash
format D: /FS:NTFS /Q
