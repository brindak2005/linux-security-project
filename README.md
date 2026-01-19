# Project 1: Linux Security Basics - File Permissions Audit
## Overview
This project demonstrates foundational Linux security skills through hands-on auditing and hardening of file permissions. The focus is on applying the principle of least privilege, understanding Linux ownership models, and documenting security-relevant findings in a clear, professional format.

---

## Objective
- Practice Linux command-line navigation
- Audit file permissions on sensitive system files
- Apply least-privilege access controls using 'chmod'
- Document security implications of permission configurations

---

## Environment
- OS: Ubuntu Linux (ARM64)
- Tools: Linux CLI ('ls', 'stat', 'chmod', 'nano', 'git')
- Version Control: Git & GitHub

---

## Tasks Performed
- Created and organized a Linux project workspace
- Audited permissions of sensitive system files (e.g., '/etc/passwd')
- Analyzed ownership, group access, and permission bits
- Applied restrictive permissions to project files
- Documented commands executed and security findings
- Published the project to GitHub with version control

---

## Key Findings
- Sensitive system files such as '/etc/passwd' are readable by all users but writable only by 'root'
- This configuration is required for system functionality while preventing unauthorized modification
- Misconfigured permissions could enable privilege escalation or system compromise

---

## Artifacts
- 'commands_used.txt' - Log of Linux commands executed during the audit
- 'permissions_audit.txt' - Permission analysis and security explanation
- 'README.md' - Project overview and documentation

---

## Skills Demonstrated
- Linux command-line proficiency
- File permission auditing ('ls -l', 'stat')
- Permission
Goal: Learn basic linux navigation and prepare the system for security-related tasks.

What i did today:
-Logged into Ubuntu
-Used terminal commands (pwd, ls, mkdir, cd)
-Created a project folder

Linux Security Project - File Permissions
Objective:
Practice Linux file permission hardening using chmod and ls

Steps Completed:
-Created project directory
-Created README file
-Audited file permissions using ls -l
-Applied least-privilege permissions using chmod 600

Result:
File permissions restricted to owner-only access (rw-------), preventing unauthorized access by group or other users.

Skills Demonstrated:
-Linux CLI
-File permission auditing
-Chmod
-Security hardening fundamentals

Why this matters:
Restricting file permissions reduces the attack surface by preventing unauthorized users from reading or modifying sensitive files.

Next Steps:
-Practice user and group management
-Explore sudo permissions
-Analyze system logs for security events 


