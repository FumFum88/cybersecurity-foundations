## Windows File System & Permissions

## What it is
Windows primarily uses NTFS (New Technology File System) as its default file system.  
NTFS supports advanced security features such as Access Control Lists (ACLs), file encryption, auditing, and disk quotas.

## Important Directories
- C:\Windows – Contains core operating system files.
- C:\Users – Stores user profiles and personal data.
- C:\Program Files – Default location for installed applications.
- C:\ProgramData – Stores application data shared between users.

## NTFS Permissions
Common permission types:
- Full Control  
- Modify  
- Read & Execute  
- Read  
- Write  

Permissions can be assigned to:
- Users  
- Groups  
- Administrators  
- SYSTEM  
NTFS uses Access Control Lists (ACLs) to define who can access files and what actions they can perform.

## Common Commands Practiced
```powershell
icacls C:\Users
whoami /groups
net user

## Why it matters in cybersecurity
Misconfigured NTFS permissions can allow unauthorized access, privilege escalation, or exposure of sensitive data.  
Security professionals frequently analyze file permissions during system enumeration and security assessments.

## Key takeaway
Understanding NTFS permissions is essential for securing Windows systems and identifying potential security weaknesses.
