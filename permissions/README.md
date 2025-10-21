# Shell Permissions Project

This project is about understanding and managing **Linux file permissions**.

## 📘 Description
The goal of this project is to practice basic Linux commands that control users, groups, and file permissions.

## 🧠 Learning Objectives
- What `chmod`, `sudo`, `su`, `chown`, `chgrp` do
- Linux file permissions
- How to represent permissions as digits
- How to change a file’s owner, group, and permissions
- How to become the superuser

## 📂 Scripts

| File | Description |
|------|--------------|
| `0-iam_betty` | Switches the current user to the user `betty`. |
| `1-who_am_i` | Prints the effective username of the current user. |
| `2-groups` | Prints all the groups the current user is part of. |
| `3-new_owner` | Changes the owner of the file `hello` to the user `betty`. |
| `4-empty` | Creates an empty file called `hello`. |
| `5-execute` | Adds execute permission to the owner of the file `hello`. |
| `6-multiple_permissions` | Adds execute permission to owner and group owner, and read permission to others for the file `hello`. |
| `7-everybody` | Adds execution permission to everyone for the file `hello`. |
| `8-James_Bond` | Sets permissions of `hello` to `007`. |
| `9-John_Doe` | Sets the mode of `hello` to `-rwxr-x-wx`. |
| `10-mirror_permissions` | Sets the mode of `hello` same as another file `olleh`. |
| `11-directories_permissions` | Adds execute permission to all subdirectories of the current directory for all users. |
| `12-directory_permissions` | Creates a directory called `my_dir` with permissions 751. |
| `13-change_group` | Changes the group owner to `school` for the file `hello`. |

---

## ⚙️ Usage
Make all scripts executable:
```bash
chmod +x *
