# WSL-Ubuntu-GUI-setup

### 🚀 Overview
A comprehensive, step-by-step guide to setting up a native Ubuntu GUI on WSL2 using XRDP. This project includes automated scripts for one-click startup and session cleanup.

### ❓ The Problem
Setting up a Graphical User Interface (GUI) in WSL2 is often a frustrating experience for beginners. Common issues include:
* **The "Blank Screen" Bug**: Persistent black or blue screens caused by ghost sessions that fail to terminate.
* **Syntax Errors**: Small spacing mistakes in manual script creation leading to "command not found" errors.
* **Complexity**: Confusing multi-step processes that require switching between different guides and apps.

### ✅ The Solution
This repository provides a verified, "copy-paste" path to success:
* **Native Focus**: Uses `apt` instead of `snap` to ensure stability within the WSL kernel.
* **Self-Cleaning Scripts**: Automated logic that kills "zombie" processes before launching the GUI.
* **Verified Logic**: Every command is tested to ensure proper formatting and execution.

---

## 🛠️ Get Started
Follow the guide in order to ensure a smooth setup:

1. [Step 1: Windows Prerequisites](PREREQUISITES.md)
2. [Step 2: Ubuntu Installation & GUI Setup](INSTALLATION.md)
3. [Step 3: Automated Scripts & Usage](USAGE.md)
