# Module 4 – Users, Groups, and Permissions

## User Management
- `whoami` – show current user.
- `id` – show UID, GID.
- `adduser newuser` – add user.
- `passwd user` – change password.

## Groups
- `groups user` – list groups.
- `usermod -aG group user` – add to group.

## Permissions
- rwx = read, write, execute.
- Example: `-rw-r--r--`  
  - Owner: read/write  
  - Group: read  
  - Others: read  

## chmod
- `chmod 755 file` – rwx for owner, rx for group/others.
- Symbolic: `chmod u+x file`.
