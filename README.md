# Linux Commands Practice – Kali Linux 🐉

![Platform](https://img.shields.io/badge/Platform-Kali%20Linux-blue)
![Category](https://img.shields.io/badge/Category-Linux%20Commands-green)
![Tool](https://img.shields.io/badge/Tool-VirtualBox-orange)
![Status](https://img.shields.io/badge/Project-Active-brightgreen)

---

# Overview

A beginner-friendly Linux commands practice repository created while learning Kali Linux using VirtualBox.

This repository contains Linux commands along with:
- meaning
- syntax
- examples
- outputs
- screenshots

The purpose of this repository is to document Linux command practice and improve terminal usage skills.

---

# Basic Navigation Commands

- `pwd`
- `ls`
- `ls -l`
- `ls -a`
- `ls -la`
- `cd`
- `cd ..`
- `clear`

---

# File Management Commands

- `mkdir`
- `touch`
- `cp`
- `mv`
- `rm`
- `rm -r`
- `cat`

---

# User Management Commands

- `whoami`
- `passwd`
- `sudo`
- `id`

---

# Networking Commands

- `ip a`
- `ping google.com`
- `ifconfig`
- `netstat -tulnp`
- `traceroute google.com`
- `nslookup google.com`

---

# Package Management Commands

- `sudo apt update`
- `sudo apt upgrade`
- `sudo apt install`
- `sudo apt remove`

---

# Permissions Commands

- `chmod +x`
- `chmod 777`
- `chown`

# Process Commands

- `top`
- `ps aux`
- `kill`
---

# Cybersecurity Tools Commands

- `whois domain.com`
- `nmap target_ip`
- `wireshark`

---

# 1. pwd

## Meaning

`pwd` stands for **Print Working Directory**.

It is used to display the current folder/location where the user is present.

---

## Syntax

```bash
pwd
```

---

## Example

```bash
pwd
```

### Output

```bash
/home/kali
```

---

## Screenshot

![pwd command](pwd-command.png)

---

# 2. ls

## Meaning

`ls` is used to list the files and folders present in the current directory.

---

## Syntax

```bash
ls
```

---

## Example

```bash
ls
```

### Output Example

```bash
Desktop Documents Downloads Pictures Videos
```

---

## Screenshot

![ls command](ls-command.png)

---

# 3. ls -l

## Meaning

`ls -l` displays files and folders in detailed list format.

It shows:
- file permissions
- owner
- file size
- timestamps

---

## Syntax

```bash
ls -l
```

---

## Example

```bash
ls -l
```

### Output Example

```bash
drwxr-xr-x 2 kali kali 4096 Desktop
-rw-r--r-- 1 kali kali 220 file.txt
```

---

## Screenshot

![ls -l command](ls-l-command.png)

---

# 4. ls -a

## Meaning

`ls -a` is used to display all files including hidden files and folders.

Hidden files usually start with a dot (`.`).

---

## Syntax

```bash
ls -a
```

---

## Example

```bash
ls -a
```

### Output Example

```bash
.  ..  .bashrc  .profile  Desktop
```

---

## Screenshot

![ls -a command](ls-a-command.png)

---

# 5. ls -la

## Meaning

`ls -la` combines:
- `ls -l` → detailed list format
- `ls -a` → hidden files

It displays:
- hidden files
- permissions
- owners
- timestamps
- detailed file information

---

## Syntax

```bash
ls -la
```

---

## Example

```bash
ls -la
```

### Output Example

```bash
drwxr-xr-x kali kali Desktop
-rw-r--r-- kali kali .bashrc
```

---

## Screenshot

![ls -la command 1](ls-la-command-1.png)

![ls -la command 2](ls-la-command-2.png)

---

# 6. cd foldername

## Meaning

`cd` stands for **Change Directory**.

It is used to move into a specific folder.

---

## Syntax

```bash
cd foldername
```

---

## Example

```bash
cd Documents
pwd
```

### Output

```bash
/home/kali/Documents
```

---

## Screenshot

![cd command](cd-documents-command.png)

---

# 7. cd ..

## Meaning

`cd ..` is used to move back one directory/folder.

---

## Syntax

```bash
cd ..
```

---

## Example

```bash
cd ..
pwd
```

### Output

```bash
/home/kali
```

---

## Screenshot

![cd back command](cd-back-command.png)

---

# 8. clear

## Meaning

`clear` is used to clear the terminal screen.

After executing the command, the terminal becomes empty and clean.

---

## Syntax

```bash
clear
```

---

## Example

```bash
clear
```

---

## Screenshot

![clear command 1](clear-command-1.png)

![clear command 2](clear-command-2.png)

---

# 9. mkdir

## Meaning

`mkdir` stands for **Make Directory**.

It is used to create a new folder/directory.

---

## Syntax

```bash
mkdir foldername
```

---

## Example

```bash
mkdir test
```

---

## Verification

```bash
ls
```

### Output Example

```bash
Desktop Documents Downloads test
```

---

## Screenshot

![mkdir command](mkdir-command.png)

---

# 10. touch

## Meaning

`touch` is used to create a new empty file.

---

## Syntax

```bash
touch filename
```

---

## Example

```bash
touch file.txt
```

---

## Verification

```bash
ls
```

### Output Example

```bash
file.txt
```

---

## Screenshot

![touch command](touch-command.png)

---

# 11. cp

## Meaning

`cp` stands for **Copy**.

It is used to copy files from one location to another.

---

## Syntax

```bash
cp sourcefile destinationfile
```

---

## Example

```bash
cp file.txt copy.txt
```

---

## Verification

```bash
ls
```

### Output Example

```bash
file.txt copy.txt
```

---

## Screenshot

![cp command](cp-command.png)

---

# 12. mv

## Meaning

`mv` stands for **Move**.

It is used to move or rename files and folders.

---

## Syntax

```bash
mv oldname newname
```

---

## Example

```bash
mv copy.txt newfile.txt
```

---

## Verification

```bash
ls
```

### Output Example

```bash
file.txt newfile.txt
```

---

## Screenshot

![mv command](mv-command.png)

---

# 13. rm

## Meaning

`rm` stands for **Remove**.

It is used to delete files.

---

## Syntax

```bash
rm filename
```

---

## Example

```bash
rm newfile.txt
```

---

## Verification

```bash
ls
```

### Output Example

```bash
file.txt
```

---

## Screenshot

![rm command](rm-command.png)

---

# 14. rm -r

## Meaning

`rm -r` is used to delete folders/directories recursively along with their contents.

---

## Syntax

```bash
rm -r foldername
```

---

## Example

```bash
rm -r test
```

---

## Verification

```bash
ls
```

### Output Example

```bash
Desktop Documents Downloads
```

---

## Screenshot

![rm -r command](rm-r-command.png)

---

# 15. cat

## Meaning

`cat` stands for **Concatenate**.

It is used to view the contents of a file.

---

## Syntax

```bash
cat filename
```

---

## Example

```bash
echo "Hello Linux" > file.txt
cat file.txt
```

### Output

```bash
Hello Linux
```

---

## Screenshot

![cat command](cat-command.png)

---

# 16. whoami

## Meaning

`whoami` is used to display the current logged-in username.

---

## Syntax

```bash
whoami
```

---

## Example

```bash
whoami
```

### Output

```bash
kali
```

---

## Screenshot

![whoami command](whoami-command.png)

---

# 17. passwd

## Meaning

`passwd` is used to change the password of the current user account.

---

## Syntax

```bash
passwd
```

---

## Example

```bash
passwd
```

### Output Example

```bash
Changing password for kali
Current password:
New password:
Retype new password:
```

## Screenshot

![passwd command](passwd-command.png)

---

# 18. sudo

## Meaning

`sudo` stands for **Super User Do**.

It is used to run commands with administrator/root privileges.

---

## Syntax

```bash
sudo command
```

---

## Example

```bash
sudo apt update
```

### Output Example

```bash
[sudo] password for kali:
```

---

## Screenshot

![sudo command](sudo-command.png)

---

# 19. id

## Meaning

`id` is used to display detailed information about the current user such as:
- User ID (UID)
- Group ID (GID)
- Groups

---

## Syntax

```bash
id
```

---

## Example

```bash
id
```

### Output Example

```bash
uid=1000(kali) gid=1000(kali) groups=1000(kali)
```

---

## Screenshot

![id command](id-command.png)

---

# 20. ip a

## Meaning

`ip a` is used to display IP addresses and network interface information.

---

## Syntax

```bash
ip a
```

---

## Example

```bash
ip a
```

### Output Example

```bash
inet 192.168.1.5/24
```

---

## Screenshot

![ip a command](ip-a-command.png)

---

# 21. ping google.com

## Meaning

`ping` is used to check internet connectivity and test communication with another server.

---

## Syntax

```bash
ping google.com
```

---

## Example

```bash
ping google.com
```

### Output Example

```bash
64 bytes from google.com
```

> Press `Ctrl + C` to stop the ping command.

---

## Screenshot

![ping command](ping-command.png)

---

# 22. ifconfig

## Meaning

`ifconfig` is used to display network interface configuration details.

---

## Syntax

```bash
ifconfig
```

---

## Example

```bash
ifconfig
```

### Output Example

```bash
eth0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>
```

---

## Screenshot

![ifconfig command](ifconfig-command.png)

---

# 23. netstat -tulnp

## Meaning

`netstat -tulnp` is used to display:
- open ports
- active services
- listening connections
- process IDs

---

## Syntax

```bash
netstat -tulnp
```

---

## Example

```bash
netstat -tulnp
```

### Output Example

```bash
tcp LISTEN 0 128 0.0.0.0:22
```

> Some details may require `sudo` privileges.

---

## Screenshot

![netstat command](netstat-command.png)

---

# 24. traceroute google.com

## Meaning

`traceroute` is used to display the path packets take from your system to a destination server.

---

## Syntax

```bash
traceroute google.com
```

---

## Example

```bash
traceroute google.com
```

### Output Example

```bash
1 192.168.1.1
2 * * *
```

---

## Screenshot

![traceroute command](traceroute-command.png)

---

# 25. nslookup google.com

## Meaning

`nslookup` is used for DNS lookup and finding the IP address of a domain.

---

## Syntax

```bash
nslookup google.com
```

---

## Example

```bash
nslookup google.com
```

### Output Example

```bash
Address: 142.250.xxx.xxx
```

---

## Screenshot

![nslookup command](nslookup-command.png)

---

# 26. sudo apt update

## Meaning

`sudo apt update` updates the package list from repositories.

It checks:
- newest package versions
- available updates
- security updates

This command does **not** install updates.

Think of it as:

> "Check what updates are available."

---

## Syntax

```bash
sudo apt update
```

---

## Example

```bash
sudo apt update
```

### Output Example

```bash
Fetched 5 MB in 3s
Reading package lists... Done
```

---

## Screenshot

![apt update command](apt-update-command.png)

---

# 27. sudo apt upgrade

## Meaning

`sudo apt upgrade` upgrades installed packages to their latest available versions.

---

## Syntax

```bash
sudo apt upgrade
```

---

## Example

```bash
sudo apt upgrade
```

### Output Example

```bash
Do you want to continue? [Y/n]
```

---

## Screenshot

![apt upgrade command](apt-upgrade-command.png)

---

# 28. sudo apt install nmap

## Meaning

`sudo apt install` is used to install software packages from repositories.

---

## Syntax

```bash
sudo apt install package-name
```

---

## Example

```bash
sudo apt install nmap
```

### Output Example

```bash
The following NEW packages will be installed:
nmap
```

---

## Screenshot

![apt install command](apt-install-command.png)

---

# 29. sudo apt remove nmap

## Meaning

`sudo apt remove` is used to uninstall software packages.

---

## Syntax

```bash
sudo apt remove package-name
```

---

## Example

```bash
sudo apt remove nmap
```

### Output Example

```bash
The following packages will be REMOVED:
nmap
```

---

## Screenshot

![apt remove command](apt-remove-command.png)

---

# 30. chmod +x file.sh

## Meaning

`chmod` stands for **Change Mode**.

It is used to change file permissions.

The `+x` option adds execute permission to a file.

---

## Syntax

```bash
chmod +x filename
```

---

## Example

Create a script:

```bash
touch script.sh
```

Make it executable:

```bash
chmod +x script.sh
```

Verify permissions:

```bash
ls -l script.sh
```

### Output Example

```bash
-rwxr-xr-x 1 kali kali 25 May 31 script.sh
```

---

## Screenshot

![chmod +x command](chmod-x-command.png)

---

# 31. chmod 777 file.txt

## Meaning

`chmod 777` gives full permissions to everyone.

* Owner: Read, Write, Execute
* Group: Read, Write, Execute
* Others: Read, Write, Execute

---

## Syntax

```bash
chmod 777 filename
```

---

## Example

```bash
chmod 777 file.txt
```

Check permissions:

```bash
ls -l file.txt
```

### Output Example

```bash
-rwxrwxrwx 1 kali kali 25 May 31 file.txt
```

---

## Permission Breakdown

| Number | Permission             |
| ------ | ---------------------- |
| 7      | Read + Write + Execute |
| 7      | Read + Write + Execute |
| 7      | Read + Write + Execute |

Result:

```text
Owner  = rwx
Group  = rwx
Others = rwx
```

---

## Important

⚠️ `777` is not recommended for sensitive files because everyone gets full access.

Use only for learning and testing purposes.

---

## Screenshot

![chmod 777 command](chmod-777-command.png)

---

# 32. chown user:group file

## Meaning

`chown` stands for **Change Owner**.

It is used to change the ownership of a file or directory.

---

## Syntax

```bash
sudo chown user:group filename
```

---

## Example

```bash
sudo chown kali:kali script.sh
```

Check ownership:

```bash
ls -l script.sh
```

### Output Example

```bash
-rwxr-xr-x 1 kali kali 25 May 31 script.sh
```

> Note: If the file already belongs to `kali:kali`, the ownership may appear unchanged.

---

## Screenshot

![chown command](chown-command.png)

---

# 33. top

## Meaning

`top` displays live system activity and running processes.

Think of it as:

> Linux Task Manager

---

## Syntax

```bash
top
```

---

## Example

```bash
top
```

### Output Example

```text
top - 03:14:53 up 41 min, 1 user, load average: 0.15, 0.19, 0.16

Tasks: 250 total, 1 running, 249 sleeping

%Cpu(s): 2.0 us, 1.0 sy, 97.0 id

PID USER      %CPU %MEM COMMAND
1234 kali      1.0  0.5 firefox
```

---

## Exit

Press:

```text
q
```

to quit the `top` screen.

---

## Screenshot

![top command](top-command.png)

---

# 34. ps aux

## Meaning

`ps aux` displays all currently running processes on the system.

It shows:

* Process owner
* Process ID (PID)
* CPU usage
* Memory usage
* Command name

---

## Syntax

```bash
ps aux
```

---

## Example

```bash
ps aux
```

### Output Example

```text
USER       PID %CPU %MEM COMMAND
root         1  0.0  0.7 /sbin/init
root         2  0.0  0.0 [kthreadd]
kali      2540  1.2  2.1 firefox
```

---

## Important Columns

| Column  | Meaning       |
| ------- | ------------- |
| USER    | Process Owner |
| PID     | Process ID    |
| %CPU    | CPU Usage     |
| %MEM    | Memory Usage  |
| COMMAND | Program Name  |

---

## Screenshot

![ps aux command](ps-aux-command.png)

---

# 35. kill PID

## Meaning

`kill` is used to stop a running process.

A process is identified using its Process ID (PID).

---

## Syntax

```bash
kill PID
```

---

## Example

Find a process:

```bash
ps aux | grep sleep
```

Output:

```bash
kali 2500 0.0 0.0 sleep 300
```

Kill the process:

```bash
kill 2500
```

---

## Verification

```bash
ps aux | grep sleep
```

The process should no longer appear in the process list.

---

## Note

PID stands for **Process ID**.

Every running process in Linux has a unique PID.

---

## Screenshot

![kill command](kill-command-1.png)

![kill command](kill-command-2.png)

```

 # 36. whois domain.com

## Meaning

`whois` is used to retrieve information about a domain name.

It can provide details such as:

* Registrar
* Creation date
* Expiry date
* Name servers

Think of it as:

> "Who owns this website?"

---

## Syntax

```bash
whois domain.com
```

---

## Example

```bash
whois google.com
```

### Output Example

```text
Domain Name: GOOGLE.COM
Registrar: MarkMonitor
Creation Date: 1997
```

---

## Screenshot

![whois command](whois-command.png)

---

# 37. nmap target_ip

## Meaning

`nmap` stands for **Network Mapper**.

It is used to discover:

* Open ports
* Running services
* Devices on a network

Think of it as:

> "Checking which doors are open."

---

## Syntax

```bash
nmap target_ip
```

---

## Example

```bash
nmap scanme.nmap.org
```

### Output Example

```text
PORT     STATE SERVICE
22/tcp   open  ssh
80/tcp   open  http
443/tcp  open  https
```

---

## Screenshot

![nmap command](nmap-command.png)

---

# 38. wireshark

## Meaning

Wireshark is a packet analysis tool used to capture and inspect network traffic.

Think of it as:

> "A microscope for network communication."

---

## Launch

```bash
wireshark
```

---

## What You Can See

* DNS requests
* HTTP traffic
* TCP packets
* IP addresses

### Output Example

```text
192.168.1.5 → google.com
DNS Query
```

---

## Screenshot

![wireshark command](wireshark-command.png)

---

# Quick Memory Table

| Tool        | Purpose                    |
| ----------- | -------------------------- |
| `whois`     | Domain information lookup  |
| `nmap`      | Network and port discovery |
| `wireshark` | Packet analysis            |

```
```


# Tools Used

- Kali Linux
- Oracle VirtualBox
- GitHub

---

# Skills Learned

- Linux terminal navigation
- File and directory management
- User management commands
- Linux networking basics
- Linux command usage
- Understanding hidden files and permissions
- Command-line interface practice
- Documentation using GitHub

---

Linux-Commands-Practice
│
├── Navigation Commands (1-8)
├── File Management Commands (9-15)
├── User Management Commands (16-19)
├── Networking Commands (20-25)
├── Package Management Commands (26-29)
├── Permissions Commands (30-32)
├── Process Management Commands (33-35)
├── Cybersecurity Tools Commands (36-38)
└── Git Commands (Future)```

---

# Future Improvements

- Add more Linux commands
- Practice file permissions
- Learn networking commands
- Explore shell scripting basics
- Document advanced Linux usage

---

# Author

**Tejaswani Animireddy**
