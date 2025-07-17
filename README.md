# Intro_to_Linux

## 📁 Working with Directories (Linux)

This repository documents common **Linux directory commands** used in the terminal. It's a helpful reference for beginners learning how to navigate and manipulate the filesystem using the command line.

---

## 📂 Basic Navigation

| Command | Description |
|---------|-------------|
| `pwd` | Print the current working directory |
| `ls` | List contents of the current directory |
| `ls -l` | List contents in long format (permissions, size, modified date) |
| `ls -a` | Show hidden files (those starting with `.`) |
| `cd <directory>` | Change into specified directory |
| `cd ..` | Go up one level (to parent directory) |
| `cd ~` | Go to the home directory |
| `cd -` | Switch to the previous directory |

---

## 📁 Creating Directories

| Command | Description |
|---------|-------------|
| `mkdir <dir>` | Create a new directory |
| `mkdir -p <dir1>/<dir2>` | Create nested directories (if parent doesn't exist) |

---

## ❌ Removing Directories

| Command | Description |
|---------|-------------|
| `rmdir <dir>` | Remove an empty directory |
| `rm -rf <dir>` | Force delete a directory and its contents (use with caution!) |

---

## List Commands

| Command | Description |
|---------|-------------|
| `-a` | List all files, including hidden ones |
| `--color` | List files in colorised output |
| `-d | List directory path, but no contents |
| `-l` | Long listing format |
| `r` | Reverse order |
| `R` | List files recursively and lists its contents |
| `t` | Sorts by time, most recently modified files show first |

---
## 🛠️ Moving & Renaming

| Command | Description |
|---------|-------------|
| `mv <source> <destination>` | Move or rename a file or directory |
| `mv dir1/ dir2/` | Move `dir1` into `dir2` |

---

## 📋 Copying Directories

| Command | Description |
|---------|-------------|
| `cp -r <source> <destination>` | Copy directory and contents recursively |

---
