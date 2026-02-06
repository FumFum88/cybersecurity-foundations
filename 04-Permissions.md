# Linux Permissions

## What it is
Linux controls access to files and directories using permissions that define who can read, write, or execute them.

## Permission types
- **r (read)** – view file contents
- **w (write)** – modify file contents
- **x (execute)** – run a file or access a directory

## Permission groups
- **User (u)** – owner of the file
- **Group (g)** – users in the file’s group
- **Others (o)** – all other users

## Common commands practiced
```bash
ls -l
chmod
chown

## Symbolic and numeric permissions
- Symbolic: `rwx`
- Numeric values:
  - r = 4
  - w = 2
  - x = 1
- Example: `755` → owner has full access, others can read and execute

## Why it matters in cybersecurity
Incorrect permissions can expose sensitive files or allow unauthorized execution, leading to privilege escalation or data leaks.

## Key takeaway
Understanding permissions is essential to securing Linux systems.
