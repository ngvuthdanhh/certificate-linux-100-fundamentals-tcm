# Users & Permissions Cheatsheet

## User Management
- `adduser <user>` → add user
- `passwd <user>` → change password
- `usermod -aG <group> <user>` → add user to group
- `deluser <user>` → delete user

## File Permissions
- `ls -l` → show permissions
- `chmod 644 file` → set read/write owner, read others
- `chmod +x script.sh` → make file executable
- `chown user:group file` → change owner
