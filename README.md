# Auto-Remove-VmWare-Tools-Linux
A simple Bash script to completely uninstall VMware Tools from Linux systems, with root check, countdown, and automatic reboot.
# Auto Remove VMware Tools (Linux)

A Bash script to completely **uninstall VMware Tools** from Linux systems.

This script automatically:
- Checks if it is run with **root** privileges
- Executes the VMware Tools uninstaller
- Displays a **countdown** after completion
- Reboots the system automatically

---

## ⚙️ Prerequisites
- Linux operating system
- VMware Tools installed (native installer, **not** open-vm-tools)
- Root access or execution via `sudo`

---

## 🚀 Usage

1. Make the script executable:
```bash
chmod +x Auto-Remove-VMware-Tools-Linux.sh
```
2.Run the script:
```bash
sudo ./Auto-Remove-VMware-Tools-Linux.sh
Type yes to confirm and start the uninstall process.
```
⚠️ Warning
This script will reboot your system after uninstalling VMware Tools.

![Language](https://img.shields.io/badge/language-Bash-4EAA25)


Not suitable if you are using open-vm-tools.


