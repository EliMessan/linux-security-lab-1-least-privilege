{\rtf1\ansi\ansicpg1252\cocoartf2869
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\fmodern\fcharset0 Courier;\f2\froman\fcharset0 Times-Bold;
\f3\froman\fcharset0 Times-Roman;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;\red255\green255\blue255;\red0\green0\blue0;
\red255\green255\blue255;\red255\green255\blue255;\red255\green255\blue255;}
{\*\expandedcolortbl;;\cssrgb\c0\c1\c1;\cssrgb\c100000\c100000\c99941;\cssrgb\c0\c0\c0;
\cssrgb\c100000\c100000\c99985;\cssrgb\c100000\c100000\c100000;\cssrgb\c100000\c100000\c99971;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat0\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}}
\margl1440\margr1440\vieww11360\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Linux Security Lab 1 - Least Privilege & Access Control\
\
## Objective\
Build a Linux security lab demonstrating least privilege, user management, file permissions, access control, and authentication logging.\
\
## Environment\
- Host Machine: MacBook Air M5\
- Virtualization: UTM\
- Operating System: Ubuntu Server 26.04 LTS\
\
## Skills Demonstrated\
- Linux Administration\
- User Management\
- Group Management\
- File Permissions\
- Ownership Management\
- Least Privilege\
- Access Control\
- Privilege Escalation\
- Authentication Logging\
\
## Tasks Completed\
\
### User Management\
- Created users John and Sarah\
- Verified user identities\
- Tested account access\
\
### File Security\
- Created sensitive payroll file\
- Restricted access using Linux permissions\
- Verified unauthorized users could not access protected data\
\
### Group Administration\
- Created department groups\
- Added users to appropriate groups\
- Verified memberships\
\
### Privilege Escalation\
- Added John to sudo group\
- Verified administrative access\
\
### Department Security\
- Created HR, Finance, and IT departments\
- Assigned ownership and permissions\
- Protected HR records from unauthorized access\
\
### Logging and Auditing\
- Reviewed authentication logs\
- Examined password policy settings\
\
## Results\
Successfully implemented a least privilege security model where users only had access to resources required for their role.\
\
## Screenshots\
See Screenshots folder for evidence of configuration and testing.\
\
\
\pard\pardeftab720\sa298\partightenfactor0

\f1\fs36 \cf2 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec3 Key Commands Used\
\pard\pardeftab720\partightenfactor0

\fs26 \cf2 \strokec3 mkdir\
cd\
ls\
groupadd\
adduser\
usermod\
groups\
chown\
chmod\
cat\
grep\
su\
whoami\
sudo\
ls -R\
ls -ld\
\
\
\pard\pardeftab720\sa298\partightenfactor0

\f2\b\fs36 \cf4 \strokec5 Security Concepts Demonstrated\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa240\partightenfactor0
\ls1\ilvl0
\f3\b0\fs24 \cf4 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec5 Principle of Least Privilege (PoLP)\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec5 Role-Based Access Control (RBAC)\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec5 Separation of Duties\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec5 Authentication\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec5 Authorization\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec5 File System Security\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec5 User and Group Administration\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec5 Security Auditing\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec5 Access Restriction Testing\
\ls1\ilvl0\kerning1\expnd0\expndtw0 \outl0\strokewidth0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec5 Privilege Management\
\pard\tx720\pardeftab720\sa240\partightenfactor0
\cf4 \
\pard\pardeftab720\sa298\partightenfactor0

\f2\b\fs36 \cf4 \strokec5 Lessons Learned\
\pard\pardeftab720\sa240\partightenfactor0

\f3\b0\fs24 \cf4 \strokec5 This lab demonstrated how Linux uses users, groups, ownership, and permissions to enforce access control. By creating department-specific resources and restricting access through group memberships and permissions, I gained hands-on experience implementing least privilege and validating security controls. I also learned how authentication logs and password policies can be reviewed to support security auditing and system administration.\cf6 \strokec6 \
\pard\tx720\pardeftab720\sa240\partightenfactor0
\cf4 \strokec5 \
\pard\pardeftab720\partightenfactor0

\f1\fs26 \cf4 \strokec7 \
}