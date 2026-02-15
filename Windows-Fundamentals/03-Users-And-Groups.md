# Windows Users & Groups

## What it is

Windows uses user accounts and security groups to manage access control and system permissions.

Users represent individual accounts, while groups simplify permission management by assigning rights to multiple users at once.

## Types of Accounts

- Local Users
- Domain Users
- Built-in Accounts (Administrator, Guest)

## Important Groups

- Administrators – Full system control
- Users – Standard access
- Remote Desktop Users – Can access system via RDP
- Backup Operators – Can back up and restore files

## Common Commands Practiced

```powershell
whoami
whoami /groups
net user
net localgroup

## Why it matters in cybersecurity

Attackers often target misconfigured user privileges.  
Understanding user roles and group memberships helps identify privilege escalation paths and weak access controls.

## Key takeaway

Proper user and group management is critical for maintaining secure Windows environments.
