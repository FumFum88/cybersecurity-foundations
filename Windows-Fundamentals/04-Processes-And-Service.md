# Windows Processes & Services

## What it is

A process is a running instance of a program.  
A service is a background process that runs automatically to support system or application functions.

## Processes

Processes:
- Run in the foreground or background
- Have a Process ID (PID)
- Consume CPU and memory

Windows uses Task Manager and PowerShell to monitor processes.

## Services

Services:
- Start automatically or manually
- Run in the background
- Often run with elevated privileges

Some services are critical for system operation.

## Common Commands Practiced

```powershell
tasklist
Get-Process
Get-Service
Stop-Process -Id <PID>
## Why it matters in cybersecurity

Malicious software often runs as hidden processes or disguised services.  
Security professionals analyze running processes and services to detect suspicious activity and persistence mechanisms.

## Key takeaway

Understanding Windows processes and services is essential for system monitoring and threat detection.
