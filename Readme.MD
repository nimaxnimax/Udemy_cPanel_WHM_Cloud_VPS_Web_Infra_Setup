![Alt text](image.png)


Udemy Course >> cPanel WHM Cloud VPS Web Hosting Server Infrastructure Setup

**********

Complete Crash Course - cPanel WHM Setup on Azure Cloud or VPS - Apache Web Server & SSL/TLS DNS MySQL Wordpress SMTP Mail Hosting Infrastructure Deployment (Installation and Configuration) >> Ubuntu 20.04 (Focal)

You Can Install on AWS or GCP or Digital Ocean or Any Public Cloud >> Ubuntu 20.04 (Focal)

**********

Tips/Tricks/Notes/Commands URL Link: https://github.com/nimaxnimax/Udemy_cPanel_WHM_Cloud_VPS_Web_Infra_Setup

Instructor & Courses >> https://www.udemy.com/user/adrian-fischer-infotech/

**********

![Alt text](image-1.png)


cPanel and WHM (Web Host Manager) are software solutions designed to simplify the process of website hosting and server management. They are widely used in the web hosting industry to provide a user-friendly interface for managing websites, domains, email accounts, and various server configurations. 

1. **cPanel:**
   - **User Interface:** cPanel is a web-based control panel that allows website owners to manage various aspects of their hosting account through a graphical interface. It is designed to be user-friendly and provides a range of tools for website management.
   - **Features:** cPanel offers features such as file management, domain management, email configuration, database management, security settings, and more. Users can easily install applications, manage backups, and monitor website statistics.
   - **Compatibility:** cPanel is compatible with various web hosting platforms and is often used in shared hosting environments.

2. **WHM (Web Host Manager):**
   - **Server Management:** WHM is the administrative interface used by hosting providers to manage the server itself. It allows hosting providers to create and manage multiple cPanel accounts, allocate resources, and configure server-wide settings.
   - **Reseller Hosting:** WHM facilitates reseller hosting, where users can create and manage their own cPanel accounts. This is useful for individuals or businesses that want to offer hosting services to others.
   - **Security and Monitoring:** WHM includes tools for server security and monitoring. Administrators can configure firewalls, set up security policies, and monitor server performance.

3. **Key Functions:**
   - **Account Management:** Both cPanel and WHM allow for the creation, modification, and deletion of hosting accounts. cPanel manages individual accounts, while WHM oversees the server as a whole.
   - **DNS Management:** Both panels provide tools for managing Domain Name System (DNS) settings, allowing users to configure domain names and associated records.
   - **Email Configuration:** Users can set up email accounts, configure email settings, and manage email-related features such as spam filtering through the interfaces.
   - **File Management:** cPanel allows users to upload, download, and manage files on the server. It includes a file manager for easy navigation and manipulation of files.

4. **Updates and Support:**
   - Both cPanel and WHM receive regular updates to add new features, improve security, and address any issues. Users and administrators can also access support resources and communities for assistance.

It's important to note that cPanel and WHM are typically provided by hosting providers, and users may not have direct access to these interfaces unless they purchase hosting services that include them. The features and interfaces may also vary slightly between different hosting providers.

**********

![Alt text](image-2.png)


It is possible to install cPanel and WHM on various cloud platforms like Azure, AWS (Amazon Web Services), GCP (Google Cloud Platform), and on VPS (Virtual Private Servers). cPanel, however, is a commercial product, and you'll need to have a valid license to use it. 

Here's a general overview of the installation process on a Linux server, and using Ubuntu 20.04 as an example:

1. **System Requirements:**
   - Ensure that your server meets the minimum system requirements for cPanel. This includes having a clean installation of the supported operating system, sufficient RAM, and available disk space.

2. **Operating System:**
   - cPanel officially supports CentOS, CloudLinux, and Red Hat Enterprise Linux (RHEL). While it's possible to install cPanel on Ubuntu, it may require additional steps.

3. **Installation Process:**
   - The installation process involves running a script provided by cPanel on a clean server. This script will automatically download and install the necessary packages.
   - For supported systems like CentOS, the process is more straightforward. For Ubuntu, additional considerations and adjustments may be needed.

4. **Licensing:**
   - Ensure that you have a valid cPanel license. You can obtain a license directly from cPanel or through a hosting provider that offers cPanel-based hosting services.

5. **Cloud Platforms (AWS, Azure, GCP):**
   - When deploying cPanel on cloud platforms, be sure to configure security groups, firewalls, and other network settings to allow necessary traffic.
   - Consider the scalability and resource requirements based on your expected workload.

It's important to check cPanel's official documentation for the most up-to-date information and specific instructions for your chosen operating system. Always follow best practices for security and consult the documentation provided by your cloud provider for any platform-specific considerations.

**********

![Alt text](image-3.png)


Here are the minimum and recommended server requirements for cPanel and WHM. Keep in mind that these specifications can change with updates and new versions, so it's always a good idea to check the official cPanel documentation for the latest information.

Minimum Server Requirements:

#### Processor:
- 1 GHz single-core processor.

#### Memory (RAM):
- 1 GB RAM (but 2 GB or more is recommended).

#### Disk Space:
- 20 GB of disk space (but more space is recommended for hosting accounts and data).

#### Operating System:
- Ubuntu 20 or CentOS 7 or CloudLinux 7.

#### Network:
- A stable network connection.

Recommended Server Requirements:

#### Processor:
- Dual or Quad-core processors, 2 GHz or more.

#### Memory (RAM):
- 4 GB RAM or more.

#### Disk Space:
- 40 GB of free disk space or more.

#### Operating System:
- Ubuntu 20 or CentOS 7 or CloudLinux 7.

#### Network:
- A stable and high-speed network connection.

Additional Recommendations:
- Use SSDs (Solid State Drives) for improved disk I/O performance.
- Allocate additional disk space based on the number and size of hosted websites, email accounts, and databases.
- Consider having a separate disk partition for the /home directory where user data is stored.
- Plan for regular backups to ensure data integrity and recovery options.

Keep in mind that these are general guidelines, and your specific requirements may vary based on factors such as the number of hosted websites, the amount of traffic, and the types of applications running on the server.

Before installation, it's crucial to check the latest documentation on the cPanel website for any updates or changes to the system requirements. Always refer to the documentation corresponding to the specific cPanel and WHM versions you are planning to install.

**********

![Alt text](image-4.png)


cPanel and WHM offer a variety of advantages, particularly for individuals and organizations involved in web hosting, server management, and website administration. Here are some key advantages:

1. **User-Friendly Interface:**
   - cPanel provides a graphical user interface (GUI) that is intuitive and user-friendly. This makes it easy for users, even those without extensive technical knowledge, to manage their websites and hosting accounts.

2. **Comprehensive Feature Set:**
   - cPanel includes a wide range of features for managing websites, domains, email accounts, databases, and server configurations. Users can perform tasks such as file management, email configuration, and database administration through a centralized interface.

3. **Automation and Scripting:**
   - Automation features within cPanel make it easy to perform routine tasks and streamline administrative processes. Users can set up cron jobs, automate backups, and use scripts to simplify complex operations.

4. **Email Management:**
   - cPanel provides robust email management capabilities, allowing users to create and manage email accounts, set up forwarding and autoresponders, configure spam filters, and more.

5. **One-Click Application Installation:**
   - cPanel includes tools like Softaculous, which allows users to install popular web applications, content management systems (CMS), and scripts with just a few clicks. This simplifies the process of deploying web applications.

6. **Security Features:**
   - cPanel and WHM offer security features such as firewalls, SSL certificate management, and security policies to help protect websites and servers from potential threats.

7. **Multi-User and Reseller Support:**
   - WHM, the administrative component, enables hosting providers to create and manage multiple cPanel accounts. This is particularly useful for reseller hosting, allowing individuals or businesses to offer hosting services to their clients.

8. **Resource Management:**
   - WHM allows administrators to manage server resources efficiently, allocate quotas to individual accounts, and monitor resource usage to ensure optimal performance.

9. **Scalability:**
   - cPanel and WHM are scalable solutions, suitable for small websites as well as larger enterprises. The ability to manage multiple hosting accounts and domains makes them versatile for various hosting scenarios.

10. **Documentation and Community Support:**
    - cPanel has extensive documentation and an active user community, providing resources for troubleshooting, learning, and getting assistance with common issues.

11. **Regular Updates:**
    - cPanel and WHM receive regular updates to introduce new features, improve security, and address any issues. Staying updated helps ensure the stability and security of the hosting environment.

While cPanel and WHM offer numerous benefits, it's essential to consider specific needs and requirements, especially when choosing an operating system and understanding licensing costs associated with cPanel. Additionally, users should keep abreast of any changes or updates in the software's features and system requirements.

**********

![Alt text](image-5.png)


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
WHM & cPanel Installation - Ubuntu 20.04 (Focal) Commands

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
sudo bash latest
sudo whmlogin
```

Linux Command >>
```bash
sudo apt install iftop iotop -y
top
sudo iftop
ip addr
df -h
free -h
sudo cat /proc/meminfo
sudo cp /proc/meminfo .
sudo chmod +w meminfo
sudo vi meminfo
sudo mount --bind meminfo /proc/meminfo
sudo umount /proc/meminfo
free
```

**********
Note: To test and verify >> for fake and test domains:
- On Linux >> Example >> Add cpanel1.domain.local & domain.local with Private or Public IP in >> /etc/hosts >> to Test and Verify FQDN and Domain
- On Windows >> Example >> Add cpanel1.domain.local & domain.local with Private or Public IP in >> c:\windows\system32\drivers\etc\hosts >> to Test and Verify FQDN and Domain

Installation Guide and System Requirements >> https://docs.cpanel.net/installation-guide/system-requirements-ubuntu/

