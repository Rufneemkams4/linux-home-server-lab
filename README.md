# linux-home-server-lab
Linux system administration practice lab using Linux Lite.

# Linux Home Server Lab

## Overview
This project documents my hands-on Linux system administration practice using Linux Lite. The objective of this lab was to develop practical skills used by Systems Administrators such as user management, service monitoring, file permissions, and troubleshooting.

## Environment

Operating System:
Linux Lite

Tools:
Bash
SSH
Linux command line utilities

## Skills Practiced

- Linux user and group management
- File permissions and ownership
- Package management
- Service monitoring
- Process monitoring
- Basic troubleshooting
- System resource monitoring

## User Management

Created users:

sudo adduser testuser

Added users to groups:

sudo usermod -aG developers testuser

Verified group membership:

groups testuser

## File Permissions

Modified permissions:

chmod 750 projectfolder

Changed ownership:

chown testuser:developers projectfolder

## Service Monitoring

Checked service status:

systemctl status apache2

Started services:

systemctl start apache2

## Process Monitoring

Used monitoring tools:

top

ps aux

## Package Management

Installed packages:

sudo apt update

sudo apt install apache2

## Lessons Learned

This project helped me understand how Linux administrators manage systems, monitor services, and troubleshoot configuration issues.

## Career Relevance

This lab demonstrates foundational skills required for:

- Systems Administrator roles
- IT Infrastructure support
- Linux administration
- Cloud operations support
