# BRG-ISEA-Lab#
## Session 1a: Linux Setup
### Objective
Install Ubuntu and practice basic Linux commands.
---
### Ubuntu Installation

I installed Ubuntu using VirtualBox and successfully booted into the system.

### Screenshot
![Virtual box settings](screenshots/session1/Virtual box settings.png)
![Ubuntu desktop](screenshots/session1/Ubuntu desktop.png)

---

### Linux Commands

Commands used:

* pwd
* ls
* mkdir labtest
* touch file1.txt

### Screenshot
![Linux Commands](screenshots/session1/Terminal with commands+output2.png)
![Linux Commands](screenshots/session1/Terminal with commands+output1.png)

---

### Reflection

In this lab, I learned how to install Ubuntu and use basic Linux commands. It was my first time using a virtual machine, and I understood how file creation and navigation works in Linux.

---
s
# Session 1b: Exploring Linux

## Services

I used systemctl to view and check system services.

### Commands

systemctl list-units --type=service
sudo systemctl status ssh

### Screenshot

![Services](screenshots/session1/services.png)

---

## Permissions

I explored file permissions using ls -l and changed permissions using chmod.

### Commands

ls -l
chmod 755 file1.txt

### Screenshot

![Permissions](screenshots/session1/permissions.png)

---

## Searching Files

I used find and grep to search for files and content.

### Commands

find /home -name file1.txt
grep -r "test" /home

### Screenshot

![Search](screenshots/session1/search.png)

---

## Reflection

In this session, I learned how Linux manages services, file permissions, and file searching. These are important for system administration and security.

---
