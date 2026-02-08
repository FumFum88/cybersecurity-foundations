# Users and Groups

## What it is
Linux is a multi-user operating system where access to files and resources is controlled using users and groups.

## Users
Each user has:
- A unique username
- A user ID (UID)
- A home directory

## Groups
Groups are used to organize users and manage permissions collectively.

## Common commands practiced
```bash
whoami
id
groups

## Important files
- `/etc/passwd` – stores user account information
- `/etc/group` – stores group information

## Why it matters in cybersecurity
Understanding users and groups helps identify privilege levels, misconfigurations, and potential attack paths such as privilege escalation.

## Key takeaway
Proper user and group management is essential for securing Linux systems.
