# Linux Commands – Basics

Linux is the core operating system used in cybersecurity. Kali Linux is a Debian-based Linux distribution designed for penetration testing.

---

## 1. File and Directory Commands

### ls
Lists files and directories.
```bash
ls
ls -la


cd

Changes directory.

cd Documents
cd ..

pwd

Shows the current directory path.

pwd

mkdir

Creates a new directory.

mkdir test_folder

rm

Deletes files or directories.

rm file.txt
rm -r folder_name

2. File Viewing Commands
cat

Displays file content.

cat file.txt

less

Reads file page by page.

less file.txt

3. File Permissions & Ownership
chmod

Changes file permissions.

chmod 755 script.sh
chmod +x script.sh

chown

Changes file owner.

sudo chown user:user file.txt

4. Package Management (APT)
apt update

Updates package list.

sudo apt update

apt install

Installs packages.

sudo apt install nmap

5. Networking Commands
ifconfig

Displays network interfaces.

ifconfig

ip a

Modern alternative to ifconfig.

ip a

ping

Checks connectivity.

ping google.com

netstat

Displays network connections.

netstat -tulnp

traceroute

Shows path taken by packets.

traceroute google.com