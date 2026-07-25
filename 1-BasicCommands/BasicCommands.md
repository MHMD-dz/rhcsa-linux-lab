#  RHCSA 2026 - Intro to RHEL & Linux Command Line Basics  
Linux Fundamentals Lab

---

##  Overview

This lab is part of my RHCSA learning path. It covers basic Linux command line usage inside a virtual machine using a RHEL-10 system.

The focus is on building real system administration skills through hands-on practice.

---

##  Objectives

- Understand Linux shell environment  
- Learn basic navigation commands  
- Manage files and directories  
- Work with file creation and editing  
- Understand file ownership basics  
- Control system services using systemd  

---

## 💻 System & Environment Commands

🟦 COMMAND: echo $SHELL  
🟩 NOTE: Shows the current shell being used ( bash)

🟦 COMMAND: gnome-shell --version  
🟩 NOTE: Displays the GNOME desktop environment version

🟦 COMMAND: cd  
🟩 NOTE: Changes directory. Moves to home directory if used alone

🟦 COMMAND: pwd  
🟩 NOTE: Displays the current working directory path

---

## 📂 File Listing Commands

🟦 COMMAND: ls -l  
🟩 NOTE: Lists files in long format showing permissions, owner, size, and modification date

🟦 COMMAND: ls -a  
🟩 NOTE: Lists all files including hidden files starting with dot (.)

---

## 📁 Directory Operations

🟦 COMMAND: mkdir test  
🟩 NOTE: Creates a directory named "test"

🟦 COMMAND: mkdir -p test1/test  
🟩 NOTE: Creates nested directories including parent directories if they do not exist

---

## 📄 File Operations

🟦 COMMAND: touch test.txt  
🟩 NOTE: Creates an empty file or updates its timestamp

🟦 COMMAND: echo "hi there"  
🟩 NOTE: Prints text to the terminal output

🟦 COMMAND: cat > test.txt  
🟩 NOTE: Creates or overwrites a file and allows writing input from terminal until CTRL + D

🟦 COMMAND: vim test.txt  
🟩 NOTE: Opens the file in Vim editor for manual editing

---

## 🔄 Move & Rename Commands

🟦 COMMAND: mv test.txt hello.txt  
🟩 NOTE: Renames file from test.txt to hello.txt

🟦 COMMAND: mv hello.txt ../test1  
🟩 NOTE: Moves file to parent directory inside folder test1

---

## 🔐 Ownership & Permissions

🟦 COMMAND: chown user:group file.txt  
🟩 NOTE: Changes ownership of a file or directory. Used for access control

---

## ⚙️ System Services (systemd)

🟦 COMMAND: systemctl status httpd  
🟩 NOTE: Checks status of Apache web server service

🟦 COMMAND: systemctl start httpd  
🟩 NOTE: Starts the Apache web server service

---

## 🧪 Lab Summary

- Practiced Linux CLI basics  
- Learned file and directory management  
- Practiced file editing methods  
- Understood ownership basics  
- Controlled system services using systemd  

---

## 📌 Notes

Practiced inside vmWare using a RHEL-10 Linux system.  
This lab is part of RHCSA preparation and Linux system administration fundamentals.