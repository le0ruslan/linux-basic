# Linux/UNIX Operating Systems Basics Project

## Overview

This project focuses on exploring the basics of Linux/UNIX operating systems and their administration. The tasks encompass installing a Linux system, managing users and network settings, working with key system utilities, and performing basic administrative operations. 

The work was carried out on a virtual machine running **Ubuntu 20.04 Server LTS** (without GUI) to ensure a controlled and practical learning environment. The file report.md includes detailed descriptions of the tasks completed, screenshots illustrating key outputs, and explanations where required.

---

## Project Tasks

### 1. Linux System Installation
- Installed **Ubuntu 20.04 Server LTS** using VirtualBox.
- Verified the installation by displaying the OS version.

### 2. User Management
- Created a new user and added them to the `adm` group.
- Verified the user's existence using `/etc/passwd`.

### 3. Network Configuration
- Configured the machine hostname and time zone.
- Set static network settings, including **IP**, **gateway**, and **DNS**.
- Verified network functionality using `ping`.

### 4. System Updates
- Updated all packages to the latest version.
- Verified the absence of pending updates.

### 5. Sudo Command
- Enabled `sudo` for the new user.
- Used `sudo` to modify the system hostname.

### 6. Time Synchronization
- Set up automatic time synchronization using `timedatectl`.
- Verified **NTP synchronization status**.

### 7. Text Editors
- Installed **VIM** and two additional text editors.
- Practiced file creation, editing, and search/replace operations.

### 8. SSHD Setup
- Installed and configured the **SSH service** on port 2022.
- Enabled SSH service on system boot.

### 9. System Monitoring Utilities
- Installed and used `top` and `htop` for system monitoring.
- Gathered system information, including **CPU** and **memory usage**.

### 10. Disk Utilities
- Used `fdisk` to retrieve disk information.
- Used `df` to analyze disk space usage.
- Used `du` and `ncdu` for detailed directory size analysis.

### 11. System Logs
- Reviewed logs in `/var/log`, such as `dmesg`, `syslog`, and `auth.log`.
- Extracted login details and verified service restarts through logs.

### 12. CRON Job Scheduler
- Scheduled periodic tasks using **CRON**.
- Verified task execution through system logs.

---

## Documentation
The detailed report includes:
- Task descriptions with step-by-step instructions.
- Screenshots illustrating key outputs.
- Explanations for configurations and observations.

For a complete breakdown, refer to the **project report** in the repository.

---
