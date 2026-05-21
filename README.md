# Linux Commands Practice – Kali Linux 🐉

![Platform](https://img.shields.io/badge/Platform-Kali%20Linux-blue)
![Category](https://img.shields.io/badge/Category-Linux%20Commands-green)
![Tool](https://img.shields.io/badge/Tool-VirtualBox-orange)
![Status](https://img.shields.io/badge/Project-Active-brightgreen)

---

# Overview

A beginner-friendly Linux commands practice repository created while learning Kali Linux using VirtualBox.

This repository contains basic Linux commands along with:
- meaning
- syntax
- examples
- outputs
- screenshots

The purpose of this repository is to document Linux command practice and improve terminal usage skills.

---

# Commands Covered

- `pwd`
- `ls`
- `ls -l`
- `ls -a`
- `ls -la`
- `cd`
- `cd ..`
- `clear`

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
-rw-r--r-- 1 kali kali  220 file.txt
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
drwxr-xr-x  kali kali Desktop
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

# Tools Used

- Kali Linux
- Oracle VirtualBox
- GitHub

---

# Skills Learned

- Linux terminal navigation
- File and directory management
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
    ├── ls-la-command.png
    ├── cd-documents-command.png
    ├── cd-back-command.png
    └── clear-command.png
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
