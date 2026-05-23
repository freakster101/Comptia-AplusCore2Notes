# 1.9 Identify common features and tools of the Linux client/desktop operating system

# File Management

## ls
Lists files and directories in the current location.  
Example: `ls` displays all files in the home folder.

## pwd
Shows the current working directory path.  
Example: `pwd` returns `/home/jagdish`.

## mv
Moves or renames files and directories.  
Example: `mv file.txt Documents/` moves a file to Documents.

## cp
Copies files and directories to another location.  
Example: `cp notes.txt Backup/` copies a file to Backup folder.

## rm
Deletes files or directories.  
Example: `rm oldfile.txt` removes a file.

## chmod
Changes file or directory permissions.  
Example: `chmod +x script.sh` makes a script executable.

## chown
Changes file ownership to another user or group.  
Example: `chown jagdish file.txt` changes file owner.

## grep
Searches text for specific words or patterns.  
Example: `grep error log.txt` finds lines containing “error”.

## find
Searches for files and directories by name or condition.  
Example: `find /home -name notes.txt` searches for a file.

# Package Management

## apt
Package manager used in Debian-based Linux distributions.  
Example: `sudo apt install nginx` installs NGINX.

## dnf
Package manager used in Red Hat-based Linux distributions.  
Example: `sudo dnf update` updates installed packages.

# Filesystem Management

## fsck
Checks and repairs Linux filesystem errors.  
Example: `fsck /dev/sda1` repairs filesystem corruption.

## mount
Attaches a storage device or filesystem to the Linux directory tree.  
Example: `mount /dev/sdb1 /mnt/usb` mounts a USB drive.

# Informational

## man
Displays the manual page for Linux commands.  
Example: `man ls` shows help for the ls command.

## cat
Displays file contents directly in the terminal.  
Example: `cat notes.txt` prints file contents.

## top
Shows real-time system resource and process usage.  
Example: `top` displays CPU and RAM usage.

## ps
Displays currently running processes.  
Example: `ps aux` lists all running processes.

## du
Shows disk usage for files and directories.  
Example: `du -h Documents/` shows folder size.

## df
Displays available and used disk space on filesystems.  
Example: `df -h` shows free disk space in readable format.

# Administrative

## su
Switches to another user account, usually root.  
Example: `su root` switches to root user.

## sudo
Runs commands with administrative privileges temporarily.  
Example: `sudo reboot` restarts the system.

# 1.10 Common Linux Configuration Files and Components

# Common Configuration Files

## /etc/passwd
Stores user account information and account settings.  
Example: Viewing usernames stored in `/etc/passwd`.

## /etc/shadow
Stores encrypted user passwords and password policies.  
Example: Password hashes saved inside `/etc/shadow`.

## /etc/hosts
Maps hostnames to IP addresses locally.  
Example: Linking `server.local` to `192.168.1.10`.

## /etc/fstab
Defines storage devices and partitions mounted during boot.  
Example: Automatically mounting a second hard drive at startup.

## /etc/resolv.conf
Stores DNS server configuration settings.  
Example: Adding Google DNS `8.8.8.8`.

# OS Components

## systemd
Linux service manager responsible for boot and background services.  
Example: `systemctl start apache2` starts a service.

## kernel
Core part of Linux that manages hardware and system resources.  
Example: Linux kernel handling CPU and memory operations.

## bootloader
Program that loads the operating system during startup.  
Example: GRUB bootloader loading Ubuntu.

# Root Account

## Root Account
The highest-privileged Linux account with full system control.  
Example: Root user installing or deleting system files.
