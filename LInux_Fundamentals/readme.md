# Linux Fundamentals Part 1 - TryHackMe

## Overview

This repository contains my notes and completed tasks from the **Linux Fundamentals Part 1** room on TryHackMe.

The room introduces the basics of Linux, including navigating the terminal, working with files and directories, searching for files, reading file contents, and using shell operators. These are fundamental skills for anyone interested in cybersecurity, ethical hacking, or system administration.

**Platform:** TryHackMe  
**Room:** Linux Fundamentals Part 1

---

## Objectives

During this room, I learned how to:

- Navigate the Linux terminal
- Identify the current user
- Display text in the terminal
- List files and directories
- Change directories
- Read file contents
- Search for files and text
- Combine commands using shell operators
- Redirect command output into files

---

# Task 1 – Introduction

The virtual machine was successfully started, and the Linux environment was prepared for the exercises.

---

# Task 2 – Basic Linux Commands

## Commands Practiced

### Identify the current user

```bash
whoami
```

Output:

```
tryhackme
```

---

### Print text to the terminal

```bash
echo Cyber Talent
```

Output:

```
Cyber Talent
```

---

# Task 3 – Interacting with the File System

## List files

```bash
ls
```

Output:

```
access.log
folder1
folder2
folder3
folder4
```

---

## Display detailed information

```bash
ls -l
```

This command displays:

- File permissions
- Owner
- Group
- File size
- Last modified date

---

## Change directory

```bash
cd folder1
```

---

## List files inside a directory

```bash
ls
```

Output:

```
access.log
passwords.txt
```

---

## Read file contents

```bash
cat passwords.txt
```

Output:

```
password123
```

---

# Task 4 – Searching

## Find a file

```bash
find -name passwords.txt
```

Output:

```
./passwords.txt
```

---

## Search for text inside a file

```bash
grep "THM" access.log
```

Output:

```
THM{ACCESS}
```

This command searches the log file and returns any line containing the keyword **THM**.

---

# Task 5 – Shell Operators

## Run multiple commands

```bash
mkdir new_task && cd new_task
```

The `&&` operator executes the second command only if the first command succeeds.

---

## Redirect output to a file

```bash
echo "Hello there" > Greetings.txt
```

View the file:

```bash
cat Greetings.txt
```

Output:

```
Hello there
```

---

## Overwrite file contents

```bash
echo "Hello cyber" > Greetings.txt
```

The `>` operator replaces the previous contents of the file.

---

## Append to a file

```bash
echo "welcome to INSA" >> Greetings.txt
```

View the file:

```bash
cat Greetings.txt
```

Output:

```
Hello cyber
welcome to INSA
```

The `>>` operator appends new content without deleting the existing content.

---

# Commands Learned

| Command | Description |
|----------|-------------|
| `whoami` | Shows the current user |
| `echo` | Prints text |
| `ls` | Lists files and folders |
| `ls -l` | Lists files with detailed information |
| `cd` | Changes directory |
| `cat` | Displays file contents |
| `find` | Searches for files |
| `grep` | Searches for specific text |
| `mkdir` | Creates a directory |
| `>` | Redirects and overwrites output |
| `>>` | Redirects and appends output |
| `&&` | Runs the next command if the previous command succeeds |

---

# Flags Found

| Task | Flag |
|------|------|
| Search Task | `THM{ACCESS}` |

---

# Skills Gained

- Linux terminal navigation
- Basic filesystem management
- Reading and searching files
- Understanding Linux commands
- Working with shell operators
- Redirecting command output
- Using Linux for cybersecurity tasks

---
---
# Screenshots 


---
---
## Conclusion

Linux Fundamentals Part 1 provided a solid introduction to the Linux command line. The exercises strengthened my understanding of basic commands that are frequently used in penetration testing, cybersecurity, and system administration. These skills form the foundation for more advanced Linux and ethical hacking topics.

---

**Completed by:** Nahusenai Minalu  
**Platform:** TryHackMe  
**Status:** ✅ Completed
