
# Linux Cheat Sheet

## 1. File System Navigation

### pwd
Shows the current working directory.

Example: `pwd`

### ls
Lists files and directories.

Example: `ls`

### cd
Changes the current directory.

Example: `cd Documents`

---

## 2. File and Directory Permissions

### chmod
Changes file or directory permissions.

Example: `chmod 755 filename`

### chown
Changes the owner of a file or directory.

Example: `sudo chown user:user filename`

---

## 3. Package Management

### apt
Manages software packages on Debian-based Linux systems.

Examples:
- `sudo apt update`
- `sudo apt install package-name`

### dpkg
Installs and manages Debian packages.

Example: `sudo dpkg -i package.deb`

---

## 4. Networking Commands

### ifconfig
Displays network interface information.

Example: `ifconfig`

### ping
Tests network connectivity.

Example: `ping 8.8.8.8`

### netstat
Displays network connections and statistics.

Example: `netstat -ano`

### traceroute
Shows the network path to a destination.

Example: `traceroute example.com`

---

## Summary

| Command | Purpose |
|---|---|
| `pwd` | Show current directory |
| `ls` | List files and directories |
| `cd` | Change directory |
| `chmod` | Change permissions |
| `chown` | Change ownership |
| `apt` | Manage packages |
| `dpkg` | Manage Debian packages |
| `ifconfig` | View network interfaces |
| `ping` | Test connectivity |
| `netstat` | View network connections |
| `traceroute` | Trace network path |
