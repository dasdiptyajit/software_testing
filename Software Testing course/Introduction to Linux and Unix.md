---
title: Introduction to Linux and Unix
updated: 2024-01-09 12:49:26Z
created: 2024-01-09 09:20:02Z
latitude: 49.39875240
longitude: 8.67243350
altitude: 0.0000
---

# What is an operating system?
- Software that manages handware and allows interaction with hardware 
- **Unix** (1960s): a family of operating systems. E.g., Oracle Solaris, FreeBSD, HP-UX, **Apple maxOS**
- **Linux** (1980s): Family of Unix-like OSs (originally developed as an effort to create a free, open-source Unix OS)

**why Linux is popular?**
- [ ] Free and open source
- [ ] Secure
- [ ] Multi-user, Multitasking
- [ ] Protability 
- [ ] Uses: Android, supercomputers, data centers and cloud services  
#
## Linux distributions (cated towards it's specific audience)
- also refers as Distro, must have a linux kernel as the core component, 100s of linux distros are avilable. 
- Differences in Linux distro: different user interface (GUI), shell comands, system utilities, support types. 
- examples: Debian (1993), largest community
- Ubuntu (debian-based)
- Red hat linux 
- Fedora(sponsored by red hat)
- SUSE Enterprise
- Arch Linux (do it yourself approach) 
#

## Overview of linux architecture

**layers of Linux**
1. UI (user interface): allows users to interact with the macine. e.g., using a music player to listen to a song. 
2. Application (to perform a task: shells): System daemons, shells, User apps, Tools
3. Operating system: controls the jobs and programs. Assigns software to user and detect errors.  
4. Kernel: Os is build on top of kernel. Performs vital operations (lowest level software). Starts on boot.
- Memory management
- Process management
- Device drivers
- Security 
5. Hardware: Consists of all pysical or electronic devices on your PC 
- CPU (central processing Unit)
- RAM (Random acess memory) (temporary memory)
- Storage (for data)
- Screen
- USB devices
#

## Linux filesystem
- Tree structure starts with /root >>>> /bin(binary code that machine reads) >>> /usr >>>>/home >>>>/boot >>>/media

#

## Linux terminal overview

**Shell**: is an OS-level appication to interact with OS/interprets commands
Use: 
- Move and copy files
- write and read from files
- Extract and filter data
- Search for data

**Shell versions:**
1. Bash
2. Zsh

#

## Communication with linux system
Use >> Terminal (enter the command to send it to) >>Shell   OS  Kernel >> Hardware
**Special paths**
~ Home directory
/ Root directory
.. Parent of the current directory
. current directory

#
## Deb and RPM packages

- .deb files: for debian-based distributors
- .rpm files: Red Hat package manager

**convert one package to another (RPM to deb)**
`alien <package-`
`name> .rpm`

**convert one package to another (deb to RPM)**
`alien -r <package-`
`name> .deb`

#

## What is shell?

- User interface for running commands 
- Interactive language 
- Scripting language 
- Default shell in Linux is : Bash (bourne again shell)
- other shells: sh, ksh, tcsh, zsh and fish


# Bash: getting information

- `whoami` : username
- `id` : user ID and Group ID
- `uname` : operating system name
- `ps` : running processes
- `top`: resource usage
- `df` : mounted file system
- `date`: date in the system
- `man`: reference manual
#
## Woking with files
- `cp`: copy file 
- `mv` : move file
- `rm`: remove file
- `touch`: create empty file, update file timestamp
- `chmod`: change/modify file permissions
- `wc`: get count of lines, words, characters in file
#

## Navigating and workign with directories
- `ls`: list of files and directories
- `find`: find files in directory tree
- `pwd`: get present working directory
- `mkdir`: make directory
- `cd`: change directory
- `rmdir`: remove directory
#

## Printing file and string contects
- `cat`: print file content
- `more`: print file contents page by page
- `head`: print first N lines of the file
- `tail`: print last  N lines of file
-  `echo`: print string or variable value
- `curl`: display contents of file at a URL
- `wget`: download file from URL
#

## Counting lines
-  `wc`- count character
#

## Sorting your views line by line
- `sort`: sort lines in a file
- `uniq`: filter out repeated lines
- `grep`(global regular expression input): returns lines in the matching pattern
- `cut`:  extract a field from each line
- `paste`: merge lines from different files 