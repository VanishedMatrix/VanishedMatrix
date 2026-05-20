# Kodaik 10 🚀

Kodaik 10 is a lightweight, heavily modified custom version of **Windows 10 LTSC** designed for stripped-down, high-performance environments. This repository hosts essential automation scripts and system tools to optimize and configure the OS installation.

---

## 🛠️ My Contributions

As a secondary developer alongside **missiletechradar**, my focus was on system deployment intelligence and automated post-installation configuration. 

### 1. `detect_drive` (Build 1051)
A specialized C++ / system utility engineered to scan hardware and identify drive environments dynamically.
* **Drive Type Detection:** Automatically determines whether connected storage devices are SSDs, NVMEs, or HDDs.
* **Windows Partition Locator:** Scans connected drives to find exactly which partition hosts the active Windows directory.
* **OS Version Identifier:** Parses system files on the target drive to extract and report the specific Windows version and build metadata.

### 2. MTR Settings (`MTR_settings.bat`)
A comprehensive automated Batch script built to fine-tune the Kodaik 10 environment post-install.
* **OS Customization:** Automatically adjusts registry tweaks, disables telemetry, and strips unnecessary background processes native to Windows 10 LTSC.
* **Performance Optimization:** Tweaks system policies to ensure Kodaik 10 maintains its lightweight footprint and maximum processing efficiency.

---
