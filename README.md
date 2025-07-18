# Intro_to_Linux

## 📁 Working with Directories (Linux)

This repository documents common **Linux directory commands** used in the terminal. It's a helpful reference for beginners learning how to navigate and manipulate the filesystem using the command line.

---

## 📂 Working with Directories

| Command | Description |
|---------|-------------|
| `pwd` | Print the current working directory |
| `ls` | List contents of the current directory |
| `ls -l` | List contents in long format (permissions, size, modified date) |
| `ls -a` | List all files, including hidden ones |
| `ls -R` | List files recursively and lists its contents |
| `ls -l` | Long listing format |
| `ls -t` | Sorts by time, most recently modified files show first |
| `cd <directory>` | Change into specified directory |
| `cd ..` | Go up one level (to parent directory) |
| `cd ~` | Go to the home directory |
| `cd -` | Switch to the previous directory |
| `mkdir <dir>` | Create a new directory |
| `mkdir -p <dir1>/<dir2>` | Create nested directories (if parent doesn't exist) |
| `rmdir <dir>` | Remove an empty directory |
| `rm -rf <dir>` | Force delete a directory and its contents (use with caution!) |

---

## 📂 Basic Linux Commands - Used frequently 

| Command | Description |
|---------|-------------|
| `ls` | List contents of the current directory |
| `cd <directory>` | Change into specified directory |
| `pwd` | Print the current working directory |
| `cat <file>` | View contents of the file |
| `echo <argument>` | Display arguments to terminal screen |
| `man <command>` | Displays the online manual for command help. Learn more about commands  |
| `exit` | Exits the shell or current shell session |
| `clear` | Clear shell contents |
| `exit` | Exits the shell or current shell session |
| `touch <file_name>` | Create a new file or updates existing file with supplied name |

---

## 📂 File & Directory Permissions 

| Command              | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| `chmod 755 <file>`   | Owner: all permissions; Group/Others: read & execute. For public scripts.   |
| `chmod 644 <file>`   | Owner: read/write; Group/Others: read. For public-readable config/files.    |
| `chmod 700 <file>`   | Owner: all permissions; Group/Others: none. For private executables.        |
| `chmod 600 <file>`   | Owner: read/write; Group/Others: none. For secure private files (e.g. SSH). |
| `chmod 777 <file>`   | Everyone: all permissions. For temporary use; avoid in production.          |

---
