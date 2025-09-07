# Module 6 – Package Management

## Debian-based (Ubuntu, Kali)
- `apt update` – update package list.
- `apt upgrade` – upgrade packages.
- `apt install package` – install package.

## Red Hat-based
- `yum install package` or `dnf install package`.

## Other
- `which command` – find command location.
- `dpkg -l` – list installed packages (Debian).

Conditionals

```bash
if [ $USER == "root" ]; then
  echo "Admin access"
else
  echo "Standard user"
fi
```

Loops

```bash
for i in {1..5}; do
  echo "Number $i"
done
```
