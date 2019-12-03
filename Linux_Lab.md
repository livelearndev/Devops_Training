# Lab Linux
## Table of Contents
[Basic command](#basic_command)  
[Working with files](#working_with_file)

<a id="basic_command"> </a> 

## Basic commands
#### **pwd:** 
Print absolute path to current working directory 
#### **echo:** 
Print whatever you provide (variable, string,...)
#### **whoami:** 
Show the user who currently logged in
#### **clear:** 
Clear the screen
#### **cal/ date:** 
Display: calendar, current date and time
#### **Locating applications:** 
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
#### **Accessing Directories**
| Syntax      | Result                              |
| :---------- | ----------                          |
| cd          | Change to your home directory       |
| cd ..       | Change to parent directory          |
| cd -        | Change to previous directory        |
| cd /        | Changes your current directory to the root (/) directory        |
#### Exploring the filesystem
| Syntax      | Result                              |
| :---------- | :----------                         |
|ls           | list directory contents of current directory|
|ls -a        | List all files including hidden files and directories|
|ls -la       | List all files including hidden files and directories by vertical (one file per line, long listing format) |
#### **Hard and Symbolic Links**
**Hard links:**  many file can point to an i-node. If one file has been modify, all file of that inode has been changed; the capacity of each file is equal  
**Symbolic links:** look like a shortcut in Windows OS, refer to a direct file. If on symbolic links is modify, the original file no change; the capacity of symbolic is very little  
To view hard/ symbolic links, we use **ln** command   
   
    ln file1.txt file2.txt  
    ls -li file*  
    ln -s file1.txt file4.txt  
    ls -li file*  
<!-- <a id='working_with_file'> </a> -->
## Working with files
#### Standard streams
These are three standard streams that are established when a Linux command is executed: **stdin, stdout, stderr**. In computing, a stream is something that can transfer data. In the case of these streams, that data is text.
    
    stdin: accept often text as input (from keyboard, files, output of previous command)
    Eg: from keyboard             : echo test
        do_something < input_file : sh < test.sh
        output of previous command: command1 | command2 
                                    ps -xau | grep java
                                    ls | cat
                                    echo "hello there" | sed "s/hello/hi/" | sed "s/there/robots/"
    stdout: 
## File permissions
## Package management
## System info
## Networking
## Iptables
## File System

