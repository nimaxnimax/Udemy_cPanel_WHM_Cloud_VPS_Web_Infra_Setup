![Alt text](image.png)


Udemy Course >> cPanel WHM Cloud VPS Web Hosting Server Infrastructure Setup

**********

Complete Crash Course - cPanel WHM Setup on Azure Cloud or VPS - Apache Web Server & SSL/TLS DNS MySQL Wordpress SMTP Mail Hosting Infrastructure Deployment (Installation and Configuration) >> Ubuntu 20.04 (Focal)

You Can Install on AWS or GCP or Digital Ocean or Any Public Cloud >> Ubuntu 20.04 (Focal)

**********

Tips/Tricks/Notes/Commands URL Link: https://github.com/nimaxnimax/Udemy_cPanel_WHM_Cloud_VPS_Web_Infra_Setup

Instructor & Courses >> https://www.udemy.com/user/adrian-fischer-infotech/

**********



**********

Cloud Network Security/Firewall >> Allow Protocols
- ICMP >> Optional
- cPanel and WHM >> TCP >> 2082, 2083, 2087, 2096
- DNS >> TCP and UDP >> 53
- HTTP and HTTPS >> 80 and 443
- SSH >> Default Port 22 >> Limit Access to SSH Per Source IP Addresses or Range >> or Change SSH Port From 22 to Another Port Number
- Mail Service >> IMAP (Internet Message Access Protocol) Port 143 (non-encrypted) & Port 993 (encrypted with SSL/TLS)
- Mail Service >> POP3 (Post Office Protocol version 3) Port 110 (non-encrypted) & Port 995 (encrypted with SSL/TLS)
- Mail Service >> SMTP (Simple Mail Transfer Protocol) Port 25 (non-encrypted, but may be blocked by some ISPs) & Port 587 (non-encrypted, Submission - used for email client-to-server communication with STARTTLS encryption) & Port 465 (encrypted with SSL/TLS)

If You Have Any Problem >> More Information >> 

cPanel and WHM (Web Host Manager) use various ports for different services. Here are the commonly used ports for cPanel and WHM:

1. **cPanel Ports:**
   - Web (HTTP): Port 2082 (non-SSL), Port 2083 (SSL)
   - Webmail (HTTP): Port 2095 (non-SSL), Port 2096 (SSL)
   - FTP: Port 21
   - SSH (Secure Shell): Port 22
   - cPanel DNSONLY: Port 2087 (non-SSL), Port 2087 (SSL)
   - MySQL/MariaDB: Port 3306

2. **WHM Ports:**
   - WHM (Web Host Manager): Port 2086 (non-SSL), Port 2087 (SSL)
   - WHM (Web Host Manager - Transfer Tool): Port 2082 (non-SSL), Port 2083 (SSL)
   - cPanel DNSONLY: Port 2087 (non-SSL), Port 2087 (SSL)
   - SSH (Secure Shell): Port 22

Ensure that these ports are open in your server's firewall to allow the necessary traffic. Additionally, consider implementing security best practices such as restricting access to these ports based on IP addresses and keeping your server software up to date with the latest security patches.

**********
Ubuntu 20.04 (Focal) Commands

Linux Command >>
```bash
sudo apt update -y && sudo apt upgrade -y
sudo lsb_release -a
sudo apt install screen -y
```

Linux Command >>
```bash
sudo fallocate -l 4G /swapfile
ls -anp /swapfile
sudo chmod 600 /swapfile
sudo mkswap /swapfile
sudo swapon /swapfile
echo '/swapfile none swap sw 0 0' | sudo tee -a /etc/fstab
```

Linux Command >>
```bash
sudo iptables-save > ~/firewall.rules
sudo systemctl stop ufw.service
sudo systemctl disable ufw.service
sudo sudo apt update -y
sudo sudo apt upgrade -y
sudo hostname
sudo hostnamectl set-hostname new-hostname
sudo hostnamectl set-hostname yourserver.domain.local
hostnamectl
cat /etc/hosts
sudo vi /etc/hosts
# example >> add Public IP and yourserver.domain.local >> in /etc/hosts 
cat /etc/hosts
sudo reboot now
```

Linux Command >>
```bash
screen
pwd
cd /home
sudo curl -o latest -L https://securedownloads.cpanel.net/latest
ls -anp
bash sh latest
```

Linux Command >>
```bash
sudo cp /proc/meminfo .
sudo chmod +w meminfo
sudo vi meminfo
sudo mount --bind meminfo /proc/meminfo
sudo umount /proc/meminfo
free
```

