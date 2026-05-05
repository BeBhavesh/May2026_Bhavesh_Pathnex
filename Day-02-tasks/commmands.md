📁 File & Directory Management
pwd                     # Show current directory
ls                      # List files
ls -la                  # List all (including hidden) with details
cd folder_name          # Change directory
cd ..                   # Go up one level
mkdir new_folder        # Create directory
rmdir folder_name       # Remove empty directory
rm file.txt             # Delete file
rm -r folder_name       # Delete directory recursively
cp file.txt copy.txt    # Copy file
cp -r dir1 dir2         # Copy directory
mv file.txt newname.txt # Rename/move file

📄 File Viewing & Editing

cat file.txt            # Show file content
less file.txt           # Scroll through file
head file.txt           # First 10 lines
tail file.txt           # Last 10 lines
tail -f log.txt         # Live log view
nano file.txt           # Edit with nano
vim file.txt            # Edit with vim

🔍 Search & Find

find . -name "file.txt"           # Find file
grep "text" file.txt              # Search text in file
grep -r "text" .                  # Search recursively
which python                      # Show path of command

📦 Package Management (Ubuntu/Debian)

sudo apt update           # Update package list
sudo apt upgrade          # Upgrade packages
sudo apt install git      # Install package
sudo apt remove git       # Remove package

⚙️ Permissions

chmod +x script.sh        # Make file executable
chmod 755 file.txt        # Change permissions
chown user:user file.txt  # Change ownership

🔄 Process Management

ps aux                  # Show running processes
top                     # Live process monitor
htop                    # Better monitor (if installed)
kill PID                # Kill process
kill -9 PID             # Force kill

🌐 Network

ping google.com         # Check connectivity
curl https://example.com # Fetch URL
wget https://file.com   # Download file
ifconfig                # Network info (older)
ip a                    # Network info (modern)

🧰 Disk & System

df -h                   # Disk usage
du -sh folder_name      # Folder size
free -h                 # Memory usage
uname -a                # System info
uptime                  # System uptime

📦 Archive & Compression

tar -cvf file.tar folder/     # Create tar
tar -xvf file.tar             # Extract tar
tar -czvf file.tar.gz folder/ # Compress
tar -xzvf file.tar.gz         # Extract gz
zip file.zip file.txt         # Zip file
unzip file.zip                # Unzip

🔗 Git (basic workflow)

git clone <repo_url>        # Clone repo
git status                  # Check changes
git add .                   # Stage changes
git commit -m "message"     # Commit
git push                    # Push
git pull                    # Pull updates
git checkout -b branch      # New branch

⚡ Shortcuts

Ctrl + C      # Stop process
Ctrl + Z      # Pause process
Ctrl + L      # Clear screen
Ctrl + A      # Move to start of line
Ctrl + E      # Move to end of line
Tab           # Auto-complete
history       # Show command history