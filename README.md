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
- Permission hardening with 'chmod'
- Least-privilege security principles
- Technical documentation
- Git version control & GitHub workflow

---

## Why This Matters
File permission misconfigurations are a common cause of security vulnerabilities. This project demonstrates the ability to identify, analyze, and mitigate such risks using standard Linux security practices.

---

## Next Steps
- Audit additional system files ('/etc/shadow', '/var/log/*')
- Explore Linux users, groups, and sudo privilege boundaries
- Expand into basic system hardening and monitoring
