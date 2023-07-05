# Introduction to Linux


## Table of Contents
1. [Basic Linux Commands](#basic-linux-commands)
2. [File Operations](#file-operations)
3. [Text Editing](#text-editing)
4. [Process Management](#process-management)
5. [User and Group Management](#user-and-group-management)
6. [Package Management](#package-management)
7. [Networking](#networking)
8. [System Information](#system-information)
9. [File Permissions](#file-permissions)
10. [Compression and Archiving](#compression-and-archiving)

## Basic Linux Commands

```bash
# Change directory
cd <directory>

# List files and directories
ls

# Present working directory
pwd

# Make a new directory
mkdir <directory>

# Remove a directory
rmdir <directory>
```

## File Operations

```bash
# Create a new file
touch <filename>

# Copy a file
cp <source> <destination>

# Move a file
mv <source> <destination>

# Rename a file
mv <oldname> <newname>

# Remove a file
rm <filename>
```

## Text Editing

```bash
# Edit a file using nano
nano <filename>

# Edit a file using vim
vim <filename>

# Edit a file using emacs
emacs <filename>
```

## Process Management

```bash
# View running processes
ps

# Terminate a process
kill <process_id>

# View process status
top

# Background a process
<command> &
```

## User and Group Management

```bash
# Create a new user
sudo adduser <username>

# Change user password
sudo passwd <username>

# Add a user to a group
sudo usermod -aG <group> <username>

# Remove a user
sudo userdel <username>

# Add a group
sudo groupadd <groupname>

# Remove a group
sudo groupdel <groupname>
```

## Package Management

### apt package manager (Debian/Ubuntu)

```bash
# Update package lists
sudo apt update

# Upgrade installed packages
sudo apt upgrade

# Install a package
sudo apt install <package>

# Remove a package
sudo apt remove <package>

# Search for a package
apt search <package>
```

### yum package manager (Red Hat/CentOS)

```bash
# Update package lists
sudo yum update

# Install a package
sudo yum install <package>

# Remove a package
sudo yum remove <package>

# Search for a package
yum search <package>
```

### dnf package manager (Fedora)

```bash
# Update package lists
sudo dnf update

# Install a package
sudo dnf install <package>

# Remove a package
sudo dnf remove <package>

# Search for a package
dnf search <package>
```

## Networking

```bash
# Check network configuration
ifconfig

# Check IP address
ip address show

# Test network connectivity
ping <hostname/IP>

# Display open ports
netstat -tuln
```

## System Information

```bash
# Display system information
uname -a

# Check disk usage
df -h

# Monitor system resources
top

# View running processes
ps -aux
```

## File Permissions

```bash
# Change ownership of a file/directory
sudo chown <user> <file/directory>

# Change permissions of a file/directory
sudo chmod <permissions> <file/directory>

# Change permissions recursively
sudo chmod -R <permissions> <file/directory>

# Set read, write, and execute permissions for user, group, and others
sudo chmod u=rwx, g=rw, o=r <file/directory>
```

## Compression and Archiving

```bash
# Create a tar archive
tar -cvf <archive.tar> <file/directory>

# Extract files from a tar archive
tar -xvf <archive.tar>

# Create a compressed tar archive
tar -czvf <archive.tar.gz> <file/directory>

# Extract files from a compressed tar archive
tar -xzvf <archive.tar.gz>

# Create a zip archive
zip <archive.zip> <file/directory>

# Extract files from a zip archive
unzip <archive.zip>
```

