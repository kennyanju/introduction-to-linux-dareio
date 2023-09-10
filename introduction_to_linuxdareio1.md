### Command: `sudo apt upgrade`
```bash
$ sudo apt upgrade
[sudo] password for ubuntu:
Hit:1 http://us.archive.ubuntu.com/ubuntu focal-updates/main amd64 libapt-pkg5.0 (2.0.1ubuntu0.22.04.1) amd64 [121 kB]
Get:2 http://us.archive.ubuntu.com/ubuntu focal-updates/main amd64 libsystemd0 (245.4-4ubuntu3.11) amd64 [224 kB]
Get:3 http://us.archive.ubuntu.com/ubuntu focal-updates/main amd64 libpam-systemd0 (245.4-4ubuntu3.11) amd64 [201 kB]
Fetched 546 kB in 1s (380 kB/s)
Preconfiguring packages ...
Selecting previously unselected package libapt-pkg5.0.
(Reading database ... 186812 files and directories currently installed.)
Preparing to unpack .../libapt-pkg5.0_2.0.1ubuntu0.22.04.1_amd64.deb ...
Unpacking libapt-pkg5.0 (2.0.1ubuntu0.22.04.1) ...
Selecting previously unselected package libsystemd0.
Preparing to unpack .../libsystemd0_245.4-4ubuntu3.11_amd64.deb ...
Unpacking libsystemd0 (245.4-4ubuntu3.11) ...
Selecting previously unselected package libpam-systemd0.
Preparing to unpack .../libpam-systemd0_245.4-4ubuntu3.11_amd64.deb ...
Unpacking libpam-systemd0 (245.4-4ubuntu3.11) ...
Setting up libapt-pkg5.0 (2.0.1ubuntu0.22.04.1) ...
Setting up libsystemd0 (245.4-4ubuntu3.11) ...
Setting up libpam-systemd0 (245.4-4ubuntu3.11) ...
Processing triggers for systemd (245.4-4ubuntu3.11) ...
Processing triggers for man-db (2.9.1-1) ...
Processing triggers for ureadahead (0.100.0-21) ...
```
### Command: `pwd`
```bash
$ pwd
/home/ubuntu
```
### Command: `cd CommandsLinux`
```bash
$ cd CommandsLinux
```
### Command: `ls /home/ubuntu`
```bash
$ ls /home/ubuntu
CommandsLinux
```
### Command: `ls -R`
```bash
$ ls -R
.
├── CommandsLinux
└── Documents
```
### Command: `ls -a`
```bash
$ ls -a
.  ..  CommandsLinux
```
### Command: `ls -lh`
```bash
$ ls -lh
total 0
```
### Command: `cat sqlite_commands.sh`
```bash
$ cat sqlite_commands.sh
#!/bin/bash
echo "This is a script for sqlite commands"
```
### Command: `cat filename1.txt filename2.txt > filename3.txt`
```bash
$ cat filename1.txt filename2.txt > filename3.txt
```
### Command: `tac filename.txt`
```bash
$ tac filename.txt
This is filename.txt
```
### Command: `cp sqlite_commands.sh /home/ubuntu/unixcommands`
```bash
$ cp sqlite_commands.sh /home/ubuntu/unixcommands
```
### Command: `cp filename1.txt filename2.txt filename3.txt /home/username/Documents`
```bash
$ cp filename1.txt filename2.txt filename3.txt /home/username/Documents
```
### Command: `cp filename1.txt filename2.txt`
```bash
$ cp filename1.txt filename2.txt
```
### Command: `cp -R /home/username/Documents /home/username/Documents_backup`
```bash
$ cp -R /home/username/Documents /home/username/Documents_backup
```
### Command: `mv sqlite_commands1.sh /home/ubuntu/CommandsLinux`
```bash
$ mv sqlite_commands1.sh /home/ubuntu/CommandsLinux
```
### Command: `mv sqlite_commands.sh sql_commands.sh`
```bash
$ mv sqlite_commands.sh sql_commands.sh
```
### Command: `mkdir Music`
```bash
$ mkdir Music
```
### Command: `mkdir Music/Songs`
```bash
$ mkdir Music/Songs
```
### Command: `rmdir -p Music/Songs`
```bash
$ rmdir -p Music/Songs
```
### Command: `rm filename`
```bash
$ rm filename
```
### Command: `rm filename1 filename2 filename3`
```bash
$ rm filename1 filename2 filename3
```
### Command: `locate -i school*note`
```bash
$ locate -i school*note
/home/ubuntu/Documents/school_note.txt
```
### Command: `find /home -name sql_commands.sh`
```bash
$ find /home -name sql_commands.sh
/home/ubuntu/CommandsLinux/sql_commands.sh
```
### Command: `grep values sql_commands.sh`
```bash
$ grep values sql_commands.sh
values="value1 value2 value3"
```
### Command: `df -h`
```bash
$ df -h
Filesystem      Size   Used Avail Use% Mounted on
udev            1.9G     0   1.9G   0% /dev
tmpfs           791M   30M   761M   4% /run
/dev/sda1       30G   18G
```