> 📘 *Regularly updated as I learn more and dive deeper into Linux and system security.*

---

## 🧱 File System Navigation

```bash
pwd             # Show current directory
ls -la          # List all files including hidden, with details
cd /path/folder # Change directory
mkdir mydir     # Create a new directory
touch file.txt  # Create an empty file
rm file.txt     # Delete file
rmdir dir/      # Remove an empty directory


---

## 🔐 File Permissions & Ownership

chmod +x script.sh     # Make a script executable
chmod 755 file         # Set read/write/execute for owner, read/execute for group/others
chown user:group file  # Change file owner
ls -l                  # View permission details
umask                  # Show default permissions


---

## ⚙️ System Info & Monitoring

top             # Real-time system processes
htop            # Better version of top (if installed)
df -h           # Disk space usage
du -sh *        # Folder size
free -h         # RAM usage
uname -a        # Kernel and system info
whoami          # Show current user


---

## 🌐 Networking

ip a                  # Show IP addresses
ping google.com       # Test network connection
netstat -tuln         # Show open ports and services
ss -tulwn             # Replacement for netstat
curl ifconfig.me      # Public IP address
traceroute 8.8.8.8    # Trace network path (install if needed)


---

## 🧪 Useful for Cybersecurity

history                   # View previously run commands
alias ll='ls -la'         # Create a command shortcut
sudo !!                   # Repeat last command with sudo
grep 'word' file.txt      # Search inside files
find / -name file.txt     # Find file in entire system


---

## 📌 Coming Soon

Shell scripting examples

Bash aliases

Port scanning with nmap

Log analysis commands



---

🧑‍💻 Author

Loydben
Computer Science A.S. Student | Cybersecurity Learner
github.com/Loydben

---
