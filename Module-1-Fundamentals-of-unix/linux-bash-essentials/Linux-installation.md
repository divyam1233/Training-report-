# 🐧 Linux Installation Training Report

## 📘 Introduction
This training report provides a comprehensive guide to installing Linux using different approaches.  
We will cover **Virtual Machine installation**, **Bare-metal installation**, and **Partitioning schemes**.  
The goal is to help learners understand both practical steps and underlying concepts.

---

## 🔹 1. Installing Linux in a Virtual Machine (VirtualBox / VMware)

### ✅ Why Use a VM?
- Safe environment for experimentation  
- No risk to host OS  
- Easy to reset or clone  

### ⚙️ Steps:
1. **Download ISO**: Obtain a Linux distribution (Ubuntu, Fedora, Debian, etc.).
2. **Install VirtualBox/VMware**: Set up virtualization software.
3. **Create New VM**:
   - Allocate CPU cores and RAM (e.g., 2 cores, 4 GB RAM).
   - Create a virtual hard disk (20–40 GB recommended).
4. **Mount ISO**: Attach the Linux ISO to the VM’s optical drive.
5. **Boot & Install**: Follow the Linux installer prompts.
6. **Post‑Install Setup**:
   - Install Guest Additions/VMware Tools for better performance.
   - Configure shared folders and networking.

---

## 🔹 2. Bare-Metal Installation (Dual Boot / Full Disk)

### ✅ Options:
- **Dual Boot**: Linux alongside Windows, choose OS at startup.
- **Full Disk**: Linux takes over the entire drive.

### ⚙️ Steps:
1. **Backup Data**: Always secure important files.
2. **Create Bootable USB**: Use tools like Rufus or BalenaEtcher.
3. **BIOS/UEFI Settings**:
   - Enable USB boot.
   - Disable Secure Boot if required.
4. **Partitioning**:
   - Choose **Install alongside Windows** (dual boot) or **Erase disk** (full install).
   - Manual partitioning for advanced users.
5. **Installation**:
   - Select language, keyboard, and time zone.
   - Create user account and password.
6. **Bootloader (GRUB)**:
   - Installed automatically.
   - Allows OS selection at startup.

---

## 🔹 3. Partitioning Schemes: MBR vs GPT

### 🧩 MBR (Master Boot Record)
- Legacy partitioning system.
- Supports up to **4 primary partitions**.
- Maximum disk size: **2 TB**.

### 🧩 GPT (GUID Partition Table)
- Modern replacement for MBR.
- Supports **128 partitions**.
- Handles disks larger than **2 TB**.
- Required for UEFI systems.

---

## 🔹 4. Common Linux Partitions

- `/` → Root directory (system files).  
- `/home` → User files and settings.  
- `/swap` → Virtual memory (usually 1–2× RAM size).  
- `/boot` → Kernel and bootloader files.  

---

## 🎯 Conclusion
Linux installation can be done safely in a **Virtual Machine** for practice, or on **bare metal** for full performance.  
Understanding **partitioning schemes** (MBR vs GPT) and **essential partitions** ensures a smooth setup.  

> *Prepared by: **Divyam Garg** (URN: 2513993, TRCS‑201)*  
> *With dedication to clarity and practical learning ✨*
