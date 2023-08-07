# Linux - Windows commands

## Content


[Command Line Basics](#command-line-basics)

[File and Directory Operations](#file-and-directory-operations)

[Disk and Volume Operations](#disk-and-volume-operations)

[System Management](#system-management)

[Users and Groups](#users-and-groups)

[Networking](#networking)

[Most Common Special Characters in CMD Windows and bash Linux](#most-common-special-characters-in-cmd-windows-and-bash-linux)


## Command Line Basics

| Description                              | CMD Windows Command        | Linux Command              |
|------------------------------------------|----------------------------|----------------------------|
| Call help system                         | HELP                       | apropos, man, whatis       |
| Call command interpreter (shell)         | CMD                        | bash, csh, sh              |
| Clear the screen                         | CLS                        | clear, reset               |
| Output message to the screen             | ECHO                       | echo                       |
| Pause execution                          | PAUSE                      | sleep                      |
| Terminal settings configuration          | MODE                       | stty                       |
| Set environment variables (path settings)| PATH, SET, SETx            | env, set                   |
| Change system date                       | DATE                       | date                       |
| Change system time                       | TIME                       | date                       |
| Exit the command prompt                  | EXIT                       | exit                       |

[Content](#content)

## File and Directory Operations

| Description                              | CMD Windows Command        | Linux Command              |
|------------------------------------------|----------------------------|----------------------------|
| List files and directories               | DIR                        | dir, ls                    |
| Create a directory                       | MKDIR                      | mkdir                      |
| Delete a directory                       | RMDIR                      | rmdir                      |
| Delete a file                            | DEL, ERASE                 | rm                         |
| Change to another directory              | CD                         | cd                         |
| Copy files or directories                | COPY, XCOPY                | cp                         |
| Rename a file                            | REN, RENAME                | mv                         |
| Move files                               | MOVE                       | mv                         |
| Find a file                              | WHERE                      | find, locate               |
| Display file contents on the screen      | TYPE, MORE                 | cat, less, more            |
| Compare contents of two files            | COMP, FC                   | cmp, diff, diff3, sdiff    |
| Sort lines in a text file                | SORT                       | sort                       |
| Change file attributes                   | ATTRIB                     | chmod                      |
| Create a symbolic link to a file or directory | MKLINK                 | ln                         |
| Backup data                              | ROBOCOPY                   | cpio, tar                  |
| Open a text editor (not available in Windows Vista and later) | EDIT    | vi                         |


[Content](#content)

## Disk and Volume Operations

| Description                              | CMD Windows Command        | Linux Command              |
|------------------------------------------|----------------------------|----------------------------|
| Create partitions                        | FDISK                      | fdisk                      |
| Manage partitions                        | DISKPART                   | parted, partx              |
| Format a disk, create a file system      | DISKPART, FORMAT           | mformat, mkfs              |
| Check the file system                    | CHKDSK                     | fsck                       |


[Content](#content)

## System Management

| Description                              | CMD Windows Command        | Linux Command              |
|------------------------------------------|----------------------------|----------------------------|
| Display a list of processes              | TASKLIST, QUERY PROCESS    | ps                         |
| Terminate a process                      | TASKKILL                   | kill, killall              |
| Reboot the computer                      | SHUTDOWN                   | shutdown, reboot           |
| Shutdown the computer                    | SHUTDOWN                   | shutdown, halt             |
| Execute a command as another user        | RUNAS                      | sudo                       |
| Display the computer name                | HOSTNAME                   | hostname                   |



[Content](#content)


## Users and Groups

| Description                              | CMD Windows Command        | Linux Command              |
|------------------------------------------|----------------------------|----------------------------|
| Create a new user                        | NET USER                   | useradd                    |
| Modify user settings                     | NET USER                   | usermod                    |
| Change user password                     | NET USER                   | passwd                     |
| Delete a user                            | NET USER                   | userdel                    |
| Create a new user group                  | NET GROUP                  | groupadd                   |
| Modify group settings                    | NET GROUP                  | groupmod                   |
| Delete a group                           | NET GROUP                  | groupdel                   |
| Display a list of active users           | QUERY USER                 | users                      |

[Content](#content)



## Networking

| Description                              | CMD Windows Command        | Linux Command              |
|------------------------------------------|----------------------------|----------------------------|
| ARP - working with IP and MAC address table | ARP                   | arp                        |
| IP configuration                         | IPCONFIG, NETSH            | ifconfig, ip               |
| Working with the routing table           | ROUTE                      | route                      |
| Ping a remote host using ICMP            | PING                       | ping                       |
| Telnet client                            | TELNET                     | telnet                     |
| Interactive DNS server management        | NSLOOKUP                   | dig, nslookup              |
| Trace the route to a remote host         | TRACERT                    | traceroute                 |
| Display network connection statistics    | NETSTAT                    | netstat                    |

[Content](#content)



# Most Common Special Characters in CMD Windows and bash Linux

Command combination | and & (|| and &&)  

| Description                                  | CMD Windows Special Character | bash Linux Special Character |
|----------------------------------------------|-------------------------------|------------------------------|
| Command combination                          | \| and & (|| and &&)         | \| and & (|| and &&)        |
| Execute a task in the background             |                               | &                            |
| Wildcards in strings                         | * and ?                       | * and ?                      |
| Character set                                |                               | [ ]                          |
| Escape special character                     | ^                             | \                            |
| Input redirection                            | <                             | <                            |
| Output redirection                           | > or >>                       | > or >>                      |
| Variable value                               | %variable%                    | $variable                    |
| Home directory                               |                               | ~                            |
| Current directory                            | .                             | .                            |
| Parent directory                             | ..                            | ..                           |
| Comment                                      |                               | #                            |

[Content](#content)

