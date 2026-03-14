# linux-home-server-lab
Linux system administration practice lab using Linux Lite.

# Linux Home Server Lab

## Overview

This project documents my Linux system administration practice using Linux Lite. The goal was to develop hands-on skills relevant to Systems Administrator roles.

## Skills Practiced

- User and group management
- File permissions
- Package installation
- Service monitoring
- Troubleshooting
- Process monitoring

## Environment

Operating System:
Linux Lite

Tools:
Bash
SSH
Linux command line

## User Management Tasks

Created users:

sudo adduser testuser

Added users to groups:

sudo usermod -aG developers testuser

Checked groups:

groups testuser

## Permission Management

Changed permissions:

chmod 750 projectfolder

Changed ownership:

chown testuser:developers projectfolder

## Service Monitoring

Checked services:

systemctl status apache2

Monitored processes:

top
ps aux

## Lessons Learned

This project helped me understand how Linux administrators manage users, services, and system resources.
