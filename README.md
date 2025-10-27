# -Basic-Network-Scanning-with-Nmap
We have Used the Nmap tool, which scan's for the open port and the services, to find the vulnerablity of the system.

Installation step:
 1. Windows: 
Go to the Nmap download page at nmap.org and download the latest Windows installer.
Double-click the downloaded .exe file to start the installation.
Follow the on-screen prompts, agreeing to the license and accepting the default components, which include the GUI tool Zenmap.
Complete the installation process. You may also need to install Npcap if prompted, which is required for packet capture. 
 2. Linux: 
Using a package manager (recommended):
Debian/Ubuntu: Open a terminal and run sudo apt update && sudo apt install nmap.
Fedora/CentOS: Open a terminal and run sudo yum install nmap or sudo dnf install nmap.
From source (for advanced users):
Download the source code archive (e.g., .tar.bz2) from nmap.org.
Extract the archive: tar -xjvf nmap-<version>.tar.bz2.
Navigate into the new directory: cd nmap-<version>.
Compile and install: Run ./configure, make, and then sudo make install. 
 3. macOS: 
Download the macOS installer from nmap.org.
Double-click the downloaded .dmg file to mount it.
Double-click the installer package (.pkg) inside the disk image to launch the installer and follow the on-screen instructions.


Command : nmap -sS -sV -Pn <TARGET_IP>
