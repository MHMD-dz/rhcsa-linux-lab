#  RHCSA 2026 - Managing Files From the Command Line  
Linux File Management Lab

---

##  Overview

This lab is part of my RHCSA learning path. It covers managing files and directories from the Linux command line using a RHEL-10 system.

The focus is on building practical skills for listing, navigating, creating, copying, moving, renaming, removing, linking, and identifying files and directories.

---

##  Objectives

- List files and directories using `ls`
- Understand common command options
- Navigate the filesystem using `cd`
- Create files and directories
- Copy files and directories
- Move and rename files and directories
- Remove files and directories
- Create hard and symbolic links
- Identify file types

---

## 📂 Listing Files and Directories

🟦 COMMAND: ls  
🟩 NOTE: Lists files and directories in the current working directory

🟦 COMMAND: ls -l  
🟩 NOTE: Lists files in long format, showing permissions, owner, group, size, and modification date

🟦 COMMAND: ls -a  
🟩 NOTE: Lists all files, including hidden files that start with a dot (.)

🟦 COMMAND: ls -i  
🟩 NOTE: Lists files with their inode numbers

---

## 🧭 Navigating the Filesystem

🟦 COMMAND: cd directory  
🟩 NOTE: Changes the current working directory

🟦 COMMAND: cd .  
🟩 NOTE: Refers to the current directory

🟦 COMMAND: cd ..  
🟩 NOTE: Moves to the parent directory, one level above the current directory

🟦 COMMAND: cd -  
🟩 NOTE: Returns to the previous working directory

---

## 📄 Creating Files

🟦 COMMAND: touch file.txt  
🟩 NOTE: Creates an empty file if it does not already exist. If the file already exists, it updates its timestamps

---

## 📁 Creating Directories

🟦 COMMAND: mkdir directory  
🟩 NOTE: Creates a new directory

🟦 COMMAND: mkdir -p parent/child  
🟩 NOTE: Creates the parent and child directories if they do not already exist

🟦 COMMAND: mkdir {1..5}  
🟩 NOTE: Uses brace expansion to create multiple directories in a sequence

---

## 📋 Copying Files and Directories

🟦 COMMAND: cp source destination  
🟩 NOTE: Copies a file from one location to another

🟦 COMMAND: cp -r directory destination  
🟩 NOTE: Recursively copies a directory and its contents

🟦 COMMAND: cp -f source destination  
🟩 NOTE: Forces the copy operation and can overwrite the destination when necessary

🟦 COMMAND: cp -p source destination  
🟩 NOTE: Preserves file attributes such as permissions, ownership, and timestamps when copying

🟦 COMMAND: cp source new_name  
🟩 NOTE: Copies a file to a new destination with a different name

---

## 🔄 Moving and Renaming Files

🟦 COMMAND: mv source destination  
🟩 NOTE: Moves a file or directory to another location

🟦 COMMAND: mv old_name new_name  
🟩 NOTE: Renames a file or directory

---

## 🗑️ Removing Files and Directories

🟦 COMMAND: rm file  
🟩 NOTE: Removes a file

🟦 COMMAND: rm -f file  
🟩 NOTE: Forces the removal of a file without asking for confirmation

🟦 COMMAND: rm -r directory  
🟩 NOTE: Recursively removes a directory and its contents

⚠️ WARNING: Be careful when using recursive deletion because removed files and directories are generally not sent to a recycle bin

---

## 🔗 Creating Links

Linux supports different types of links, including hard links and symbolic links.

🟦 COMMAND: ln original hard_link  
🟩 NOTE: Creates a hard link to a file. The hard link refers to the same underlying data as the original file

🟦 COMMAND: ln -s original symbolic_link  
🟩 NOTE: Creates a symbolic link that points to the path of another file or directory

---

## 🔍 Identifying File Types

🟦 COMMAND: file filename  
🟩 NOTE: Identifies the type of a file based on its contents and structure

---

## 🧪 Lab Summary

- Practiced listing files and directories using `ls`
- Learned how to navigate the filesystem using `cd`
- Created files using `touch`
- Created directories using `mkdir`
- Used brace expansion to create multiple directories
- Copied files and directories using `cp`
- Moved and renamed files using `mv`
- Removed files and directories using `rm`
- Created hard and symbolic links using `ln`
- Identified file types using `file`

---

## 🧠 Key Takeaways

- `ls` is used to inspect files and directories
- `cd` is used to navigate the Linux filesystem
- `.` represents the current directory
- `..` represents the parent directory
- `-` with `cd` returns to the previous directory
- `touch` creates files
- `mkdir` creates directories
- `cp` copies files and directories
- `mv` moves and renames files and directories
- `rm` removes files and directories
- `ln` creates hard links
- `ln -s` creates symbolic links
- `file` identifies file types

---

## 📌 Notes

Practiced inside vmWare using a RHEL-10 Linux system.  
This lab is part of RHCSA preparation and Linux system administration fundamentals.