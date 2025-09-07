# Module 8 – Shell Scripting

## Basics
- Start with shebang: `#!/bin/bash`.
- Make script executable: `chmod +x script.sh`.

## Variables

```bash
NAME="Danh"
echo "Hello $NAME"
```

## Conditionals

```bash
if [ $USER == "root" ]; then
  echo "Admin access"
else
  echo "Standard user"
fi
```

## Loops

```bash
for i in {1..5}; do
  echo "Number $i"
done
```
