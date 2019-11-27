# Lab Linux
## Table of Contents
[Basic command](#basic_command)
[Working with files](#working_with_file)
<a id="basic_command"> </a> 
## Basic commands
### **pwd:** 
Print absolute path to current working directory 
### **echo:** 
Print whatever you provide (variable, string,...)
### **whoami:** 
Show the user who currently logged in
### **clear:** 
Clear the screen
### **cal/ date:** 
Display: calendar, current date and time
### **Locating applications:** 
Because of multiple types of Linux operating system distribution, application can be installed in various directory, such as: 
    /bin
    /usr/bin
    /sbin
    /usr/sbin
    /opt
To find out where the program is located, we use:  

    which: show the full path of (shell) commands.
    Eg: which git
    whereis: locate the binary, source, and manual page files for a command 
    Eg: whereis git
    find: search for files in a directory hierarchy
    Eg: find /home -iname git (find all file git in /home directory, ignore case) 
### **Accessing Directories**
| Syntax      | Result                              |
| :---------- | ----------                          |
| cd          | Change to your home directory       |
| cd ..       | Change to parent directory          |
| cd -        | Change to previous directory        |
| cd /        | Changes your current directory to the root (/) directory        |
### Exploring the filesystem
| Syntax      | Result                              |
| :---------- | :----------                         |
|ls           | list directory contents of current directory|
|ls -a        | List all files including hidden files and directories|
|ls -la| List all files including hidden files and directories by vertical (one file per line, long listing format) |
<a id='working_with_file'> </a>
## Working with files
## File permissions
## Package management
## System info
## Networking
## Iptables
## File System

