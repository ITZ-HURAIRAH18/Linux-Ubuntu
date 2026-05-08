Ubuntu Course
| Command                    | Description                                |
| -------------------------- | ------------------------------------------ |
| `pwd`                      | Show current directory path                |
| `ls`                       | List files and folders                     |
| `ls -la`                   | Show detailed files including hidden files |
| `cd foldername`            | Move into a folder                         |
| `cd ..`                    | Move one directory back                    |
| `cd /`                     | Go to root directory                       |
| `cd ~`                     | Go to home directory                       |
| `mkdir foldername`         | Create a new folder                        |
| `rmdir foldername`         | Remove an empty folder                     |
| `touch filename.txt`       | Create a new empty file                    |
| `nano filename.txt`        | Open file in Nano text editor              |
| `cat filename.txt`         | Display file content                       |
| `clear`                    | Clear terminal screen                      |
| `rm filename.txt`          | Delete a file                              |
| `rm -r foldername`         | Delete folder and contents                 |
| `cp file1 file2`           | Copy file                                  |
| `mv file1 file2`           | Move or rename file                        |
| `history`                  | Show previous commands                     |
| `whoami`                   | Show current username                      |
| `sudo command`             | Run command as administrator               |
| `apt update`               | Update package list                        |
| `apt upgrade`              | Upgrade installed packages                 |
| `sudo apt install package` | Install software package                   |
| `top`                      | Show running processes                     |
| `ps aux`                   | List all running processes                 |
| `kill PID`                 | Stop a process using PID                   |
| `df -h`                    | Show disk storage usage                    |
| `free -h`                  | Show RAM usage                             |
| `ip a`                     | Show IP/network details                    |
| `ping google.com`          | Test internet connection                   |
| `man command`              | Show manual/help for command               |
| `echo "text"`              | Print text in terminal                     |
| `find . -name file.txt`    | Search file in current directory           |
| `chmod +x file.sh`         | Make file executable                       |
| `./file.sh`                | Run executable script                      |
| `wget URL`                 | Download file from internet                |
| `unzip file.zip`           | Extract ZIP file                           |
----------------------------------------------------------------


File Editing in Nano


| Shortcut   | Description      |
| ---------- | ---------------- |
| `CTRL + O` | Save file        |
| `ENTER`    | Confirm save     |
| `CTRL + X` | Exit Nano editor |
| `CTRL + K` | Cut line         |
| `CTRL + U` | Paste line       |


Example Workflow

cd /
ls
mkdir myproject
cd myproject
touch app.py
nano app.py
ls -la
pwd
clear


Getting System Information in Ubuntu 

Here are some useful **system information commands** in Ubuntu/Linux with short descriptions:

```bash
df
```

Shows disk space usage of all mounted drives.

```bash
df -h
```

Shows disk space in human-readable format (GB, MB).

```bash
cat /proc/cpuinfo
```

Displays detailed CPU information.

```bash
lscpu
```

Shows CPU architecture and processor details in a clean format.

```bash
free -h
```

Displays RAM and swap memory usage in human-readable format.

```bash
uname -a
```

Shows system/kernel information.

```bash
hostnamectl
```

Displays hostname, OS version, kernel, and architecture.

```bash
top
```

Real-time system monitoring (CPU, RAM, processes).

```bash
htop
```

Advanced colorful version of `top` (may require install).

```bash
neofetch
```

Shows stylish system information summary (may require install).

```bash
lsblk
```

Lists storage devices and partitions.

```bash
du -sh foldername
```

Shows size of a specific folder.

```bash
uptime
```

Shows system running time and load.

```bash
whoami
```

Displays current logged-in user.

```bash
ip a
```

Shows IP address and network interfaces.

```bash
ifconfig
```

Older command to view network info (may require net-tools package).

```bash
ps aux
```

Lists all running processes.

```bash
sudo fdisk -l
```

Shows disk partitions and storage details.

```bash
vmstat
```

Displays system performance statistics.

```bash
dmesg
```

Shows kernel and boot logs.
