# Lab 02 – Package & Process Management

## Package Management (Ubuntu/Debian)
```bash
# Update system
sudo apt update && sudo apt upgrade -y

# Install a package
sudo apt install curl -y

# Remove a package
sudo apt remove curl -y

# Search for a package
apt search nginx
```

## Process Management

```bash
# List processes
ps aux | head

# Find a process by name
ps aux | grep ssh

# View processes with top/htop
top
htop

# Kill process by PID
kill -9 <PID>
```
