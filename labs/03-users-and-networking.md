# Lab 03 – Users & Networking

## User & Group Management
```bash
# Create a new user
sudo adduser testuser

# Set password for user
sudo passwd testuser

# Add user to group
sudo usermod -aG sudo testuser

# List user groups
groups testuser
```
## Networking Basics

```bash
# Check IP address
ip a

# Ping a server
ping -c 4 google.com

# Check open ports
sudo netstat -tulnp
ss -tulnp

# Download file with wget
wget http://example.com/file.txt
```
