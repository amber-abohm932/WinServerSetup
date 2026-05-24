# ⚙️ WinServerSetup - Automated system setup for Windows machines

[![](https://img.shields.io/badge/Download-WinServerSetup-blue.svg)](https://github.com/amber-abohm932/WinServerSetup)

WinServerSetup prepares your computer by automating repetitive tasks. This tool configures settings for Windows Server, Windows 10, and Windows 11. It removes manual effort during the initial setup phase of a new operating system installation. Use this script to apply standard configurations to your system.

## 📋 System Requirements

Ensure your computer meets these conditions before you run the software:

* Operating System: Windows 10 (version 20H2 or later), Windows 11, or Windows Server 2019/2022.
* Permissions: You must have an Administrator account on the machine.
* Internet Connection: The tool needs a stable connection to download updates and software packages.
* PowerShell: Version 5.1 or later. Most modern Windows systems include this version by default.

## 🚀 Downloading the Software

Visit this page to download the script files: [https://github.com/amber-abohm932/WinServerSetup](https://github.com/amber-abohm932/WinServerSetup).

1. Open the link in your web browser.
2. Locate the green button labeled "Code".
3. Click "Download ZIP" from the menu.
4. Save the file to your computer.
5. Right-click the folder and select "Extract All" to reveal the files.

## 🖥️ Running the Setup Process

Follow these steps to start the automation:

1. Open the folder you extracted in the previous step.
2. Right-click the file named `Setup.ps1`.
3. Select "Run with PowerShell".
4. A window will appear. If Windows prompts you to confirm, select "Yes" or "Run Once".
5. Observe the text appearing in the window. The tool displays each step as it completes.
6. Do not close this window until the script finishes. The window closes on its own once the process concludes.

## 🛠️ Included Automations

This tool handles several specific tasks to save you time. 

### Windows Updates
The script checks for pending patches and critical updates. It installs these items in the background. This keeps your system secure and stable without requiring manual input.

### Winget Integration
The script uses the Windows Package Manager (Winget) to install core tools. It automates software deployment by pulling approved installers directly from software vendors. This ensures that you run the latest, clean versions of your required software.

### Scheduled Tasks
The software sets up daily maintenance routines. These tasks clear temporary files, clear system logs, and verify disk health during idle hours. This keeps your storage space clean and maintains system performance over time.

### RDP Configuration
The script enables Remote Desktop Protocol (RDP) access. It creates the necessary firewall exceptions so you can connect to your machine from another device on your local network. It also applies security hardening to protect the RDP port from common threats.

## 🛡️ Security Information

The scripts follow industry standards for system deployment. The code remains transparent for your review. You can open any file in the folder using Notepad to inspect the commands. 

The software does not store your passwords, personal files, or browsing history. It only modifies system settings, modifies registry keys related to performance, and installs software from official repositories.

## ❓ Frequently Asked Questions

### Does this tool erase my files?
No. This tool only adjusts settings, installs updates, and manages system tasks. It does not touch your Documents, Pictures, or other personal folders.

### Can I cancel the script while it runs?
You can close the PowerShell window to stop the script. The script stops running immediately. This does not damage your operating system, but some tasks may remain incomplete. You can simply run the script again to finish the remaining jobs.

### Why do I need Administrator rights?
The script modifies deep system settings and installs software for all users. These operations require elevated access to ensure the changes take effect across the entire machine.

### What if an error appears?
The window shows text in red if an error occurs. Most errors happen due to network interruptions or locked files. Restart your computer and run the script again. 

### Does it work on older versions of Windows?
The script optimizes specifically for Windows 10, Windows 11, and modern Windows Server versions. It may not function correctly on Windows 7 or Windows 8.

## 📝 Support and Feedback

If you encounter issues, check the issues tab on the repository page. You can read how other users solved similar problems. If your specific problem is not listed, open a new issue. Include a description of the error message and which version of Windows you use.

## ⚖️ License

The software is provided for use under the terms of the MIT license. You are free to use, modify, and distribute the code. See the LICENSE file in the repository for details.