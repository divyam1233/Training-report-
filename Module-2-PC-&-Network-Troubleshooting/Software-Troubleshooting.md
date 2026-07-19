# 🖥️ Software Troubleshooting: Safe Mode

## 📘 Introduction
**Safe Mode** is a diagnostic startup mode in Windows that loads only essential drivers and services.  
It helps identify and fix problems caused by faulty drivers, software conflicts, or malware.

Prepared by: **Divyam Garg**  
URN: **2513993**  
Course Code: **TRCS‑201**

---

# 🔹 1. When to Use Safe Mode
- System crashes or freezes frequently  
- Blue Screen of Death (BSOD) errors  
- Malware infections preventing normal boot  
- Driver conflicts or faulty updates  
- Troubleshooting startup programs  

---

# 🔹 2. How to Boot into Safe Mode

### Windows 10 / 11
1. Press **Shift + Restart** → Advanced Startup.  
2. Navigate: **Troubleshoot → Advanced Options → Startup Settings → Restart**.  
3. Press **F4** → Safe Mode.  
4. Press **F5** → Safe Mode with Networking.  
5. Press **F6** → Safe Mode with Command Prompt.  

👉 Example Command (force Safe Mode via msconfig):
```bash
msconfig
# Select Boot tab → Safe Boot → Minimal


# 🔹# ⚙️ Operating System Repair (Windows Basics)

## 📘 Introduction
Operating system repair involves diagnosing and fixing issues that prevent Windows or Linux from booting or functioning correctly.  
This section covers **basic repair techniques** for both platforms.

Prepared by: **Divyam Garg**  
URN: **2513993**  
Course Code: **TRCS‑201**

---

# 🔹 1. Windows OS Repair Basics

### Common Issues
- Boot errors (e.g., "Operating System Not Found")  
- Blue Screen of Death (BSOD)  
- Corrupted system files  
- Failed updates  

### Repair Methods

#### a) Safe Mode
```text
- Boot into Safe Mode (F8 or Shift + Restart → Advanced Options).
- Uninstall faulty drivers or updates.
