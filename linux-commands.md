# Basic Linux Commands

## List Directory Contents
```sh
ls
```
Options:

-l: Long format

-a: Show hidden files

-h: Human-readable file sizes

## Change Directory
```sh
cd <directory>
```
Examples:

``` cd .. ```: Go up one directory

``` cd ~ ```: Go to the home directory

## File Operations

### Create a New File
```sh
touch <file-name>
```
### Display File Contents
```sh
cat <file-name>
```
### Copy file
```sh
cp <source> <destination>
```

### Move or Rename a File
```sh
mv <source> <destination>
```

### Remove a File
```sh
rm <file-name>
```
Option:

-r: Recursive, required to delete directories

### Create a New Directory
```sh
mkdir <directory-name>
```

### Remove a Directory
```sh
rmdir <directory-name>
```
## Permissions

### Change File Permissions
```sh
chmod <permissions> <file-name>
```
Examples:

``` chmod 644 <file-name> ```: Set read/write for owner, read-only for group and others

``` chmod +x <file-name> ```: Make a file executable

### Change File Owner
```sh
chown <owner>:<group> <file-name>
```

## System Information

### Show Disk Usage
```sh
df -h
```
### Show Free and Used Memory
```sh
free -h
```
### Display System Uptime
```sh
uptime
```
### Show Running Processes
```sh
top
```
or

```sh
htop
```
## Networking

### Display IP Address
```sh
ip a
```
### Check Connectivity
```sh
ping <host>
```

### Download Files
```sh
wget <url>
```
or
```sh
curl -O <url>
```

## Package Management (Debian-based systems)
### Update Package List
```sh
sudo apt update
```

### Upgrade All Packages
```sh
sudo apt upgrade
```

### Install a Package
```sh
sudo apt install <package-name>
```

### Remove a Package
```sh
sudo apt remove <package-name>
```

## Searching

### Find Files and Directories

```sh
find <path> -name <search-term>
```
### Search Inside Files
```sh
grep <search-term> <file>
```

## Miscellaneous
### Clear the Terminal Screen
```sh
clear
```
### View Command History
```sh
history
```

### Echo a Message
```sh
echo "Your message here"
```
