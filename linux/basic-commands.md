1. FILE & DIRECTORY COMMANDS
📁 Navigation
pwd        # Show current directory
ls         # List files
ls -la     # List all (hidden + details)
cd dir     # Change directory
cd ..      # Move back
📁 File Operations
touch file.txt      # Create file
mkdir folder        # Create directory
cp file1 file2      # Copy file
mv file1 file2      # Move/rename
rm file.txt         # Delete file
rm -rf folder       # Delete folder forcefully
🔹 2. FILE VIEWING & EDITING
cat file.txt        # View file content
less file.txt       # Scroll view
head file.txt       # First 10 lines
tail file.txt       # Last 10 lines
tail -f file.txt    # Live logs (VERY IMPORTANT 🔥)
nano file.txt       # Edit file
vi file.txt         # Advanced editor
tail -f is used for monitoring logs in real-time
🔹 3. FILE PERMISSIONS & OWNERSHIP
chmod 777 file      # Full permission
chmod 755 file      # Standard permission
chown user file     # Change owner
chgrp group file    # Change group
Permission Meaning
7 = rwx
6 = rw-
5 = r-x
🔹 4. USER MANAGEMENT
useradd name        # Add user
passwd name         # Set password
userdel name        # Delete user
id                  # Show user info
whoami              # Current user
PROCESS MANAGEMENT
ps aux              # Show processes
top                 # Live process monitor
htop                # Better version of top
kill PID            # Kill process
kill -9 PID         # Force kill
👉 Interview Tip:
Used to troubleshoot high CPU usage
🔹 6. SYSTEM & RESOURCE MONITORING
df -h               # Disk usage
du -sh folder       # Folder size
free -m             # Memory usage
uptime              # System running time