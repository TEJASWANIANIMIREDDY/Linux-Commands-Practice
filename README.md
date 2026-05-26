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

![pwd command](images/pwd-command.png)

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

![ls command](images/ls-command.png)

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

![ls -l command](images/ls-l-command.png)

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

![ls -a command](images/ls-a-command.png)

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

![ls -la command 1](images/ls-la-command-1.png)

![ls -la command 2](images/ls-la-command-2.png)

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

![cd command](images/cd-documents-command.png)

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

![cd back command](images/cd-back-command.png)

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

![clear command 1](images/clear-command-1.png)

![clear command 2](images/clear-command-2.png)

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

![mkdir command](images/mkdir-command.png)

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

![touch command](images/touch-command.png)

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

![cp command](images/cp-command.png)

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

![mv command](images/mv-command.png)

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

![rm command](images/rm-command.png)

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

![rm -r command](images/rm-r-command.png)

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

![cat command](images/cat-command.png)

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

![whoami command](images/whoami-command.png)

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

> ⚠️ Do not show your actual password in screenshots.

---

## Screenshot

![passwd command](images/passwd-command.png)

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

![sudo command](images/sudo-command.png)

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

![id command](images/id-command.png)

---

# Tools Used

- Kali Linux
- Oracle VirtualBox
- GitHub

---

# Skills Learned

- Linux terminal navigation
- File and directory management
- User management commands
- Linux command usage
- Understanding hidden files and permissions
- Command-line interface practice
- Documentation using GitHub

---

# Project Structure

```text
Linux-Commands-Practice/
│
├── README.md
│
└── images/
    ├── pwd-command.png
    ├── ls-command.png
    ├── ls-l-command.png
    ├── ls-a-command.png
    ├── ls-la-command-1.png
    ├── ls-la-command-2.png
    ├── cd-documents-command.png
    ├── cd-back-command.png
    ├── clear-command-1.png
    ├── clear-command-2.png
    ├── mkdir-command.png
    ├── touch-command.png
    ├── cp-command.png
    ├── mv-command.png
    ├── rm-command.png
    ├── rm-r-command.png
    ├── cat-command.png
    ├── whoami-command.png
    ├── passwd-command.png
    ├── sudo-command.png
    └── id-command.png
```

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
