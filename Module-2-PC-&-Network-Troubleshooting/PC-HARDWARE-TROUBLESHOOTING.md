# 🖥️ PC Hardware Troubleshooting & Boot Issues

## 📘 Introduction
This section explains how to troubleshoot **PC hardware problems** and resolve **common boot issues**.  
It provides practical steps and solutions for diagnosing failures and ensuring smooth system startup.

Prepared by: **Divyam Garg**  
URN: **2513993**  
Course Code: **TRCS‑201**

---

# 🔹 1. PC Hardware Troubleshooting

Hardware troubleshooting involves systematic checks of components such as **RAM, HDD/SSD, GPU, and PSU**.  
The goal is to identify faulty parts and apply corrective measures.

### General Steps:
1. Check cables and connections.  
2. Inspect for physical damage (burn marks, loose parts).  
3. Run diagnostic tools (MemTest86, CHKDSK, SMART).  
4. Swap with known good components if available.  

---

# 🔹 2. Common PC Boot Issues and Solutions

| Issue | Possible Cause | Solution |
|-------|----------------|----------|
| **No Power** | Faulty PSU, loose cable | Check power cable, replace PSU |
| **No Display** | GPU/Monitor issue | Reseat GPU, check monitor cable |
| **Boot Loop** | Corrupt OS, bad RAM | Boot in Safe Mode, test RAM |
| **Missing Boot Device** | HDD/SSD not detected | Check BIOS settings, reseat drive |
| **Blue Screen (BSOD)** | Driver or hardware failure | Update drivers, run diagnostics |

---

## 🔹 Practical Examples

### BIOS Error: "No Boot Device Found"
```text
- Enter BIOS → Check boot order
- Ensure HDD/SSD is connected properly
- Enable UEFI/Legacy mode if required


# Hardware Diagnosis Guide

This guide covers basic troubleshooting for common component failures.

### 1. RAM (Memory)
*   **Symptoms**: Blue screens (BSOD), system random freezes, or failure to boot.
*   **Diagnosis**: Run a memory diagnostic tool (like MemTest86) to identify faulty sticks.

### 2. HDD/SSD (Storage)
*   **Symptoms**: Slow file access, disk read/write errors, or clicking noises (mechanical drives).
*   **Diagnosis**: Use S.M.A.R.T. monitoring software to check drive health and identify bad sectors.

### 3. GPU (Graphics Card)
*   **Symptoms**: Visual artifacts (lines/flickering on screen), driver crashes, or games closing unexpectedly.
*   **Diagnosis**: Update drivers first, then monitor temperatures under load and check for loose physical connections.

### 4. PSU (Power Supply Unit)
*   **Symptoms**: Sudden system shutdowns, failure to turn on, or electrical buzzing sounds.
*   **Diagnosis**: Use a multimeter to test voltage output or swap in a known-good power supply to confirm failure.
*