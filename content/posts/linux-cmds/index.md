---
title: "Linux commands"
description: "a list of popular and frequently used linux commands."
summary: "basic and advanced Linux commands for efficient command-line usage, covering file management and system tasks"
tags: [ "linux", "cli", "commands", "os" ]
darft: false
---

## Basic

### Navigating the filesystem

Basic commands for navigating the linux filesystem:

- [pwd](/posts/pwd) - Print Working Directory
- [ls](/posts/ls)  - list current directory (folder) content
- [cd](/posts/cd)  - Change Directory 
- [whoami](/posts/whoami) - print effective user name


### Searching

Commands for finding files, directories, commands (binary files), ... that matche
a specific pattern:

- [locate](/posts/locate) - search for files and directories
- [whereis](/posts/whereis) - locate the binary, source, and manual page files for a command 
- [find](/posts/find) - search for files in a directory hierarchy
- [grep](/posts/grep)* - print lines that match patterns


### Files Manipualtion

Commands for creating, removing, editing, ... files:

- [touch](/posts/touch) - creating files, but its primarly use is changing file timestamps
- [cat](/posts/cat) - concatenate and print files
- [mkdir](/posts/mkdir) - create a directory
- [cp](/posts/cp) - copy files and directories
- [mv](/posts/mv) - move (rename) files
- [rm](/posts/rm) - remove files or directories
- [rmdir](/posts/rmdir) - remove empty directories


### Text manipulation

Commands for manipulating text files:

- [head](/posts/head) - output the first part of files
- [tail](/posts/tail) - output the last part of file
- [nl](/posts/nl) - number lines of files
- [sed](/posts/sed) - stream editor for filtering and transforming text
- [awk](/posts/awk) - pattern scanning and processing language
- [more](/posts/more) - display files on a page-by-page basis
- [less](/posts/less) - opposite of [more](/posts/more)
- [nano](/posts/nano) - Nano's ANOther editor, inspired by Pico
- [vim](/posts/vim) - Vi IMproved, a programmer's text editor


### Managing networks

Commands for managing networks:

- [ifconfig](/posts/ifconfig) - network interface configurator
- [iwconfig](/posts/iwconfig) - wireless network interface configurator
<!-- - [iwlist](/posts/) - -->
- [nmcli](/posts/) - command-line tool for controlling NetworkManager
- [ping](/posts/) - send [ICMP](#) ECHO_REQUEST to network hosts
- [dhclient](/posts/dhclient) - Dynamic Host Configuration Protocol Client
- [dig](/posts/dig) - DNS lookup utility


### Software manipulation

Commands for installing and uninstalling software:

- [apt](/posts/apt) - [Debian](https://en.wikipedia.org/wiki/Debian)-based package manager
- [dnf](/posts/dnf) - package manager for [Fedora](en.wikipedia.org/wiki/Fedora_Linux) and [RedHat](en.wikipedia.org/wiki/Red_Hat) operating systems
- [pacman](/posts/pacman) - package manager for "I use [Arch](en.wikipedia.org/wiki/Arch_Linux) btw" people
<!-- - [git](/posts/) - ** -->


### Getting HELP

how to get help:

- [man](/posts/man) - an interface to the system reference manuals
- [tldr](/posts/tldr) - Simplified and community-driven man pages
- [apropos](/posts/apropos) - search the manual page names and descriptions


## Advanced

### Controlling permissions

Commands form controlling and managing files and directories permissions:

- [chown](/posts/) - change file owner and group
- [chgrp](/posts/chgrp) - change group ownership
- [chmod](/posts/chmod) - change permissions of a file


### Process management

Commands for managing [processes](#):

- [ps](/posts/ps) - report a snapshot of the current processes
- [top](/posts/top) - display Linux processes
- [nice](/posts/nice) - change process priority
- [renice](/posts/renice) - alter priority of running processes
- [kill](/posts/kill) - terminate or send a signal to a process
- [fg](/posts/fg) - run jobs in the foreground
- [bg](/posts/bg) - run jobs in the background
- [at](/posts/at)* - execute commands at a later time
<!-- - *[crond](/posts/) - -->


### Compressing and archiving

Commands and utilities for compression and manipulating archives:

- [tar](/posts/tar) - format of tape archive files
- [7z](/posts/7z) - A file archiver with highest compression ratio
- [gzip](/posts/gzip) - compress and expand files
- [bzip2](/posts/bzip2) - a block-sorting file compressor
- [compress](/posts/compress) - compress data
- [dd](/posts/dd) - makes Bit-by-Bit copy of a file


### Filesystem and storage device management

Commands for managing storage devices:

- [fdisk](/posts/fdisk) - manipulate disk partition table
- [lsblk](/posts/lsblk) - list block devices
- [mount](/posts/mount) - mount a filesystem
- [umount](/posts/umount) - unmount filesystems
- [df](/posts/df) - report file system space usage
- [fsck](/posts/fsck) - check and repair a Linux filesystem


### Linux kernel management

managing linux kernel:

- [uname](/posts/uname) - get name and information about current kernel
- [sysctl](/posts/sysctl) - configure kernel parameters at runtime
- [lsmod](/posts/lsmod) - Show the status of modules in the Linux Kernel
- [modinfo](/posts/modinfo) - Show information about a Linux Kernel module
- [modprobe](/posts/modprobe) - Add and remove modules from the Linux Kernel
- [dmesg](/posts/dmesg) - print or control the kernel ring buffer


### Automating tasks


### Fun commands

fun linux commands to play with: (but they can be usefull sometimes)

- [figlet](/posts/figlet) - display large characters made up of ordinary screen characters
- [cowsay](/posts/cowsay) - configurable speaking/thinking cow (and a bit more)
- [neofetch](/posts/neofetch) - A fast, highly customizable system info script
- [exa](/posts/eza) - a modern replacement for [ls](/posts/ls)
- [tree](/posts/tree) - list contents of directories in a tree-like format
- [](/posts/) - 
- [](/posts/) - 



<!--
### More Commands

- type
- which
- whatis
- who
- alias / unalias
- ssh
- file
- cmp
- diff
- tput
- acpi
- xprep
- ...
-->
