# Basic CLI Commands Cheat Sheet

This guide provides a list of essential Command-Line Interface (CLI) commands used for navigation, file manipulation, and system tasks.

---

## Navigation Commands

### 1. **`pwd`** – Print Working Directory
Displays the current directory you're in.

```bash
pwd
```

### 2. **`ls`** – List Directory Contents
Shows the files and folders in the current directory.

```bash
ls
```

Common options:
- `-l` : Lists in long format with file permissions, size, etc.
- `-a` : Shows hidden files (files starting with `.`).

```bash
ls -la
```

### 3. **`cd`** – Change Directory
Moves you to a different directory.

```bash
cd <directory-name>
```

Examples:
- Move to a specific folder: `cd Documents`
- Go up one directory level: `cd ..`
- Go to the home directory: `cd ~`

---

## File and Directory Manipulation

### 1. **`touch`** – Create a New File
Creates a new empty file.

```bash
touch <file-name>
```

Example:

```bash
touch notes.txt
```

### 2. **`mkdir`** – Make Directory
Creates a new directory (folder).

```bash
mkdir <directory-name>
```

Example:

```bash
mkdir projects
```

### 3. **`rm`** – Remove Files or Directories
Deletes a file or folder. Use with caution!

- To remove a file:

```bash
rm <file-name>
```

- To remove a directory and its contents recursively:

```bash
rm -r <directory-name>
```

### 4. **`cp`** – Copy Files or Directories
Copies files or directories.

- Copy a file:

```bash
cp <source-file> <destination-file>
```

- Copy a directory recursively:

```bash
cp -r <source-directory> <destination-directory>
```

### 5. **`mv`** – Move or Rename Files
Moves or renames files or directories.

- To move a file:

```bash
mv <source-file> <destination-directory>
```

- To rename a file:

```bash
mv <old-file-name> <new-file-name>
```

---

## Viewing and Editing Files

### 1. **`cat`** – Concatenate and Display File Content
Displays the content of a file.

```bash
cat <file-name>
```

### 2. **`head`** – Display the First Few Lines of a File
Shows the first 10 lines of a file by default.

```bash
head <file-name>
```

You can specify the number of lines to display:

```bash
head -n 5 <file-name>
```

### 3. **`tail`** – Display the Last Few Lines of a File
Shows the last 10 lines of a file by default.

```bash
tail <file-name>
```

You can specify the number of lines:

```bash
tail -n 5 <file-name>
```

### 4. **`nano`** – Simple Text Editor
Opens a file in the `nano` text editor.

```bash
nano <file-name>
```

- Save and exit: `CTRL + O` (Save), `CTRL + X` (Exit).
- To exit without saving: `CTRL + X`, then press `N`.

---

## Searching Files and Content

### 1. **`find`** – Search for Files
Searches for files or directories in a directory tree.

```bash
find <directory> -name "<file-name>"
```

Example:

```bash
find . -name "index.html"
```

### 2. **`grep`** – Search for Content in Files
Searches for a specific text pattern within files.

```bash
grep "<pattern>" <file-name>
```

Example:

```bash
grep "hello" notes.txt
```

You can also search recursively within all files in a directory:

```bash
grep -r "<pattern>" <directory>
```

---

## File Permissions and Ownership

### 1. **`chmod`** – Change File Permissions
Modifies the read, write, and execute permissions of files and directories.

```bash
chmod <permissions> <file-name>
```

- `755` gives full permissions to the owner and read/execute permissions to others.
- `777` gives full permissions to everyone.

Example:

```bash
chmod 755 script.sh
```

### 2. **`chown`** – Change File Owner
Changes the ownership of a file or directory.

```bash
chown <user>:<group> <file-name>
```

Example:

```bash
sudo chown user:group file.txt
```

---

## System Information and Processes

### 1. **`top`** – View Running Processes
Displays system tasks, CPU usage, memory usage, and more.

```bash
top
```

To exit `top`, press `q`.

### 2. **`ps`** – List Running Processes
Shows the processes running on the system.

```bash
ps
```

You can show all processes with `ps aux`:

```bash
ps aux
```

### 3. **`kill`** – Kill a Running Process
Terminates a process using its process ID (PID).

```bash
kill <pid>
```

To forcefully terminate a process:

```bash
kill -9 <pid>
```

---

## Networking Commands

### 1. **`ping`** – Test Network Connection
Sends ICMP requests to test the connection to a specific IP or domain.

```bash
ping <domain-or-ip>
```

Example:

```bash
ping google.com
```

### 2. **`ifconfig` / `ip`** – Show Network Configuration
Displays network interface configurations.

```bash
ifconfig
```

On newer systems, use:

```bash
ip a
```

### 3. **`curl`** – Transfer Data from a URL
Fetches data from a URL or performs HTTP requests.

```bash
curl <url>
```

---

## Disk Usage and Space

### 1. **`df`** – Show Disk Space Usage
Displays available disk space on mounted filesystems.

```bash
df -h
```

The `-h` flag shows the output in human-readable format (KB, MB, GB).

### 2. **`du`** – Show Disk Usage of Files/Directories
Shows the disk space used by files and directories.

```bash
du -h <directory>
```

---

## Package Management

### 1. **`apt-get`** (for Debian/Ubuntu systems) – Install, Update, and Remove Packages

- Update package list:

```bash
sudo apt-get update
```

- Install a package:

```bash
sudo apt-get install <package-name>
```

- Remove a package:

```bash
sudo apt-get remove <package-name>
```

---

## Miscellaneous Commands

### 1. **`clear`** – Clear the Terminal
Clears the terminal screen.

```bash
clear
```

### 2. **`history`** – Show Command History
Displays the list of previously executed commands.

```bash
history
```

---

This guide summarizes basic CLI commands that are essential for working with the terminal. Use these commands to navigate the file system, manage files, check system status, and more.
