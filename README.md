# Linux Security Lab 1 - Least Privilege & Access Control

## Objective

Build a Linux security lab demonstrating least privilege, user management, file permissions, access control, and authentication logging.

## Environment

- Host Machine: MacBook Air M5
- Virtualization: UTM
- Operating System: Ubuntu Server 26.04 LTS

## Skills Demonstrated

- Linux Administration
- User Management
- Group Management
- File Permissions
- Ownership Management
- Least Privilege
- Access Control
- Privilege Escalation
- Authentication Logging
- Security Auditing

## Tasks Completed

### User Management
- Created users John and Sarah
- Verified user identities
- Tested account access

### File Security
- Created sensitive HR records
- Restricted access using Linux permissions
- Verified unauthorized users could not access protected data

### Group Administration
- Created department groups
- Added users to appropriate groups
- Verified memberships

### Privilege Escalation
- Added John to the sudo group
- Verified administrative access

### Department Security
- Created HR, Finance, and IT departments
- Assigned ownership and permissions
- Protected HR records from unauthorized access

### Logging and Auditing
- Reviewed authentication logs
- Examined password policy settings

## Security Concepts Demonstrated

- Principle of Least Privilege (PoLP)
- Role-Based Access Control (RBAC)
- Authentication
- Authorization
- File System Security
- User and Group Administration
- Security Auditing
- Access Restriction Testing
- Privilege Management

## Results

Successfully implemented a least privilege security model where users only had access to resources required for their role.

## Key Commands Used

```bash
mkdir
groupadd
adduser
usermod
groups
chown
chmod
cat
grep
su
whoami
sudo
ls -R
ls -ld
```

## Lessons Learned

This lab demonstrated how Linux uses users, groups, ownership, and permissions to enforce access control. By creating department-specific resources and restricting access through group memberships and permissions, I gained hands-on experience implementing least privilege and validating security controls.
