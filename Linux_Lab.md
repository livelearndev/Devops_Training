# Lab Linux
## Basic commands
### **pwd:** print absolute path to current working directory 
### **echo:** print whatever you provide (variable, string,...)
### **whoami:** show the user who currently logged in
### **clear:** clear the screen
### **cal/ date:** display: calendar, current date and time
### **Locating applications:** because of multiple types of Linux operating system distribution, application can be installed in various directory, such as: 
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
| :---------- | ----------:                         |
| cd          | Change to your home directory       |
| cd ..       | Change to parent directory          |
| cd -        | Change to previous directory        |
| cd /        | Changes your current directory to the root (/) directory        |
### Exploring the filesystem
ls
## Working with files
## File permissions
## Package management
## System info
## Networking
## Iptables
## File System