# Ubuntu Course

This guide provides a comprehensive list of essential Ubuntu commands, organized into categories for easy reference. Use this as a quick guide to navigate and manage your Ubuntu system efficiently.

---

## Basic Navigation Commands

| **Command**               | **Description**                            |
|---------------------------|--------------------------------------------|
| `pwd`                     | Show current directory path                |
| `ls`                      | List files and folders                     |
| `ls -la`                  | Show detailed files including hidden files |
| `cd foldername`           | Move into a folder                         |
| `cd ..`                   | Move one directory back                    |
| `cd /`                    | Go to root directory                       |
| `cd ~`                    | Go to home directory                       |

---

## File and Folder Management

| **Command**               | **Description**                            |
|---------------------------|--------------------------------------------|
| `mkdir foldername`        | Create a new folder                        |
| `rmdir foldername`        | Remove an empty folder                     |
| `touch filename.txt`      | Create a new empty file                    |
| `nano filename.txt`       | Open file in Nano text editor              |
| `cat filename.txt`        | Display file content                       |
| `rm filename.txt`         | Delete a file                              |
| `rm -r foldername`        | Delete folder and contents                 |
| `cp file1 file2`          | Copy file                                  |
| `mv file1 file2`          | Move or rename file                        |

---

## System Information Commands

| **Command**               | **Description**                            |
|---------------------------|--------------------------------------------|
| `df -h`                   | Show disk storage usage in human-readable format |
| `free -h`                 | Show RAM usage                             |
| `uname -a`                | Show system/kernel information             |
| `hostnamectl`             | Display hostname, OS version, and architecture |
| `uptime`                  | Show system running time and load          |
| `whoami`                  | Display current logged-in user             |
| `ip a`                    | Show IP address and network interfaces     |
| `ps aux`                  | List all running processes                 |
| `top`                     | Show running processes in real-time        |
| `htop`                    | Advanced colorful version of `top` (may require install) |
| `lsblk`                   | List storage devices and partitions        |
| `du -sh foldername`       | Show size of a specific folder             |
| `sudo fdisk -l`           | Show disk partitions and storage details   |

---

## Package Management Commands

| **Command**               | **Description**                            |
|---------------------------|--------------------------------------------|
| `sudo apt update`         | Update package list                        |
| `sudo apt upgrade`        | Upgrade installed packages                 |
| `sudo apt install package`| Install software package                   |

---

## Networking Commands

| **Command**               | **Description**                            |
|---------------------------|--------------------------------------------|
| `ping google.com`         | Test internet connection                   |
| `wget URL`                | Download file from internet                |
| `ifconfig`                | View network info (may require net-tools package) |

---

## File Editing in Nano

| **Shortcut**              | **Description**                            |
|---------------------------|--------------------------------------------|
| `CTRL + O`                | Save file                                  |
| `ENTER`                   | Confirm save                               |
| `CTRL + X`                | Exit Nano editor                           |
| `CTRL + K`                | Cut line                                   |
| `CTRL + U`                | Paste line                                 |

---

## Example Workflow

Here is an example workflow to create and manage a project:

```bash
cd /
ls
mkdir myproject
cd myproject
touch app.py
nano app.py
ls -la
pwd
clear
```

---

## Advanced System Commands

| **Command**               | **Description**                            |
|---------------------------|--------------------------------------------|
| `cat /proc/cpuinfo`       | Display detailed CPU information           |
| `lscpu`                   | Show CPU architecture and processor details |
| `vmstat`                  | Display system performance statistics      |
| `dmesg`                   | Show kernel and boot logs                  |
| `neofetch`                | Show stylish system information summary (may require install) |

---

Feel free to explore these commands and practice them to become proficient in using Ubuntu.
