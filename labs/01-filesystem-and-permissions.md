# Lab 01 – File System & Permissions

## File System & Navigation
```bash
# Create and move into a directory
mkdir test_dir && cd test_dir

# Create files
touch file1.txt file2.txt

# List files
ls -l

# Copy and rename
cp file1.txt copy_file.txt
mv file2.txt moved_file.txt


# Remove file
rm copy_file.txt
```

## File Permissions
```bash
# View file permissions
ls -l file1.txt

# Change file permissions
chmod 644 file1.txt
chmod +x script.sh

# Change file owner
sudo chown $USER:$USER file1.txt
```
