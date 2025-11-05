# 🐧 Linux Command Cheat Sheet

A concise and practical **Linux Command Cheat Sheet** — perfect for beginners, students, and developers to quickly recall essential commands.

---

## 🚀 Getting Started

| Command | Description |
|----------|--------------|
| `pwd` | Print current working directory |
| `whoami` | Display current username |
| `clear` | Clear the terminal screen |
| `history` | Show command history |
| `man [command]` | Display manual/help page of a command |
| `sudo [command]` | Run command with superuser privileges |

---

## 💻 System Information

| Command | Description |
|----------|--------------|
| `uname -a` | Show kernel and system information |
| `hostname` | Display system’s hostname |
| `uptime` | Show system uptime and load |
| `top` | Display running processes |
| `htop` | Interactive process viewer (needs installation) |
| `df -h` | Show disk space usage in human-readable format |
| `free -h` | Show memory usage |
| `lscpu` | Display CPU information |
| `lsusb` | List USB devices |
| `lspci` | List PCI devices |

---

## 📁 File & Directory Management

| Command | Description |
|----------|--------------|
| `ls` | List files in directory |
| `ls -l` | List with detailed info (permissions, size, owner) |
| `cd [dir]` | Change directory |
| `mkdir [dir]` | Create a new directory |
| `rmdir [dir]` | Remove empty directory |
| `rm -r [dir]` | Remove directory and contents |
| `cp [file1] [file2]` | Copy file |
| `mv [source] [dest]` | Move or rename file |
| `touch [file]` | Create empty file |
| `cat [file]` | Display contents of file |
| `tree` | Display directory structure (needs installation) |

---

## 📝 File Viewing & Editing

| Command | Description |
|----------|--------------|
| `cat [file]` | View file content |
| `less [file]` | View large files page by page |
| `head -n [x] [file]` | View first x lines |
| `tail -n [x] [file]` | View last x lines |
| `nano [file]` | Open file in Nano editor |
| `vim [file]` | Open file in Vim editor |

---

## 👤 User Management

| Command | Description |
|----------|--------------|
| `who` | List logged-in users |
| `id` | Display current user ID info |
| `sudo adduser [username]` | Create new user |
| `sudo deluser [username]` | Delete user |
| `passwd [username]` | Change user password |
| `su [username]` | Switch user |
| `groups [username]` | Show user groups |

---

## 🔒 File Permissions

| Command | Description |
|----------|--------------|
| `chmod [permissions] [file]` | Change file permissions |
| `chown [user:group] [file]` | Change file ownership |
| `ls -l` | View permissions |
| `chmod +x [file]` | Make file executable |

---

## ⚙️ Process Management

```
| Command          | Description                      |
| ---------------- | -------------------------------- |
| `ps`             | Display running processes        |
| `ps aux`         | Show all processes               |
| `kill [PID]`     | Kill a process by PID            |
| `killall [name]` | Kill all processes by name       |
| `bg` / `fg`      | Resume background/foreground job |
| `jobs`           | List background jobs             |
| `top`            | Monitor running processes        |

```

---
## 🌐 Networking

```
| Command                      | Description                    |
| ---------------------------- | ------------------------------ |
| `ping [host]`                | Check network connectivity     |
| `ifconfig`                   | Display network interfaces     |
| `ip a`                       | Display IP addresses           |
| `netstat -tuln`              | Show open ports                |
| `curl [url]`                 | Fetch content from a URL       |
| `wget [url]`                 | Download file from a URL       |
| `scp [file] user@host:/path` | Copy files over SSH            |
| `ssh user@host`              | Connect to remote host via SSH |


```
---
## 📦 Package Management

### 🧩 Ubuntu / Debian

```
| Command                      | Description              |
| ---------------------------- | ------------------------ |
| `sudo apt update`            | Update package index     |
| `sudo apt upgrade`           | Upgrade all packages     |
| `sudo apt install [package]` | Install a package        |
| `sudo apt remove [package]`  | Remove a package         |
| `sudo apt autoremove`        | Clean up unused packages |

```
---
## 🎯 Red Hat / CentOS

```
| Command                      | Description     |
| ---------------------------- | --------------- |
| `sudo yum update`            | Update packages |
| `sudo yum install [package]` | Install package |

```

---
## 💽 Disk Management

```
| Command                | Description         |
| ---------------------- | ------------------- |
| `lsblk`                | List block devices  |
| `df -h`                | Show disk usage     |
| `du -sh [dir]`         | Show directory size |
| `mount [device] [dir]` | Mount disk          |
| `umount [dir]`         | Unmount disk        |

```
---
## 📦 Compression & Archiving

```
| Command                        | Description         |
| ------------------------------ | ------------------- |
| `tar -cvf archive.tar [files]` | Create tar archive  |
| `tar -xvf archive.tar`         | Extract tar archive |
| `gzip [file]`                  | Compress file       |
| `gunzip [file.gz]`             | Decompress file     |
| `zip [file.zip] [files]`       | Create zip file     |
| `unzip [file.zip]`             | Extract zip file    |

```

---
## 🔍 Search & Filters

```
| Command                       | Description                |
| ----------------------------- | -------------------------- |
| `grep [pattern] [file]`       | Search for pattern in file |
| `find [dir] -name [filename]` | Find files by name         |
| `locate [filename]`           | Locate file quickly        |
| `sort [file]`                 | Sort lines of text         |
| `uniq`                        | Remove duplicate lines     |
| `wc -l [file]`                | Count lines in file        |

```

---
## 📊 System Monitoring

```
| Command  | Description                 |
| -------- | --------------------------- |
| `top`    | View running processes      |
| `htop`   | Interactive process monitor |
| `iostat` | CPU/disk stats              |
| `vmstat` | System performance stats    |
| `dmesg`  | Kernel ring buffer messages |

```

---
## ⚡ Shell Shortcuts

```
| Shortcut       | Description               |                        |
| -------------- | ------------------------- | ---------------------- |
| `Ctrl + C`     | Kill current process      |                        |
| `Ctrl + Z`     | Suspend current process   |                        |
| `Ctrl + D`     | Logout / End input        |                        |
| `!!`           | Run last command          |                        |
| `history       | grep [command]`           | Search command history |
| `Ctrl + A / E` | Move to start/end of line |                        |

```

---
## 💡 Bonus: Useful One-Liners

```
`# Find top 10 largest files
du -ah / | sort -rh | head -n 10

# Check open ports
sudo netstat -tulpn

# Show system info summary
neofetch

# Monitor real-time disk usage
watch -n 1 df -h
```
---

## 📚 References

⭐ GNU Core Utilities

⭐ Linux Command Library

⭐ Cheat.sh

⭐ The Linux Documentation Project
