# **Module 2: Server Administration Basics**

Welcome to Module 2, where we'll dive into the world of server administration. As an IT professional, understanding how servers fit into your organization's infrastructure is crucial for effective management and troubleshooting. In this module, you'll learn about the different types of servers, basic server administration tasks, and gain a solid foundation in Windows and Linux operating systems.

By completing this course, you'll gain a solid foundation in server administration basics, including understanding Windows and Linux operating systems. This knowledge will enable you to effectively manage and troubleshoot servers within your organization's IT infrastructure.

## Definition of a server and its role in an IT infrastructure

* **Definition:** A server is a computer that provides services or resources to other computers over a network.
* **Role in IT Infrastructure:** Servers play a vital role in an organization's IT infrastructure by providing shared access to files, printers, databases, and applications. They enable communication between devices, facilitate data sharing, and support business operations.

## Types of Servers:

1. File servers (e.g., NAS, Samba)
2. Print servers (e.g., printer sharing)
3. Web servers (e.g., Nginx, IIS)
4. Database servers (e.g., MySQL, MongoDB)
5. Application servers (e.g., Java, .NET)
6. Domain Controller (e.g., Active Directory, FreeIPA)

**Homework:** Research and identify three different types of servers used in VRChat.

## Basic Server Administration Tasks

* **Installation:** Learn the process of installing a server operating system, including Windows and Linux.
* **Configuration:** Understand how to configure basic settings such as network interfaces, user accounts, and security options.
* **Troubleshooting:** Develop skills for troubleshooting common issues like connectivity problems, disk errors, and service failures.

**Hands-on Exercise:** *(self study, hard to do while in VR)*

1. Install a virtual machine with either Windows or Linux.
2. Configure the server's network settings and create a test user account.
3. Set-up a basic web server that you can reach through your browser.

**Discussion Questions:**

<details> 
<summary><b>1. What are some common issues that can occur during server installation?</b></summary>
<ol>
<li><b>Disk space limitations</b>: Insufficient disk space to complete the installation process or store necessary files and data.</li>
<li><b>Hardware compatibility</b>: Incompatibility between the installed operating system (OS) and hardware components like network cards, sound cards, or graphics cards.</li>
<li><b>Boot loader problems</b>: Issues with the boot loader (e.g., GRUB or LILO) preventing the OS from loading properly.</li>
<li><b>Corrupted installation media</b>: Damaged or faulty installation CDs/DVDs/ISO files preventing a successful installation.</li>
<li><b>Partitioning and formatting errors</b>: Incorrect partitioning or formatting of disks, leading to data loss or corruption.</li>
</ol>
</details>

<details> 
<summary><b>2. How do you troubleshoot common server issues?</b></summary>
<ol>
<li><b>Identify the issue</b>: Determine what's not working.</li>
<li><b>Check logs</b>: Review system logs (e.g., Windows Event Viewer, Linux syslog)</li>
<li><b>Verify connectivity</b>: Ping other systems on the network.</li>
<li><b>Test services</b>: Try accessing specific services like HTTP, FTP, SSH, or RDP.</li>
<li><b>Consult resources</b>: Check documentation and online forums related to your environment (e.g., Windows Server, Linux distributions).</li>
<li><b>Escalate if needed</b>: If you can't resolve the issue, consult with experts or escalate to support.</li>
</ol>
</details>


## Windows Operating System Fundamentals

* **Overview:** Learn about the history, key features, and components of Windows operating systems.
* **Hands-on Exercise:** Install a virtual machine with Windows. Explore the desktop environment and basic system settings. *(self study, hard to do while in VR)*


## Linux Operating System Fundamentals

* **Overview:** Learn about the history, evolution, and fundamental concepts of Linux operating systems.
* **Hands-on Exercise:** Install a virtual machine with Linux (or use [Windows Subsystem for Linux](https://learn.microsoft.com/en-us/training/modules/wsl-introduction)). Explore the command-line interface and basic system settings. *(self study, hard to do while in VR)*

**Discussion Questions:**
<details> 
<summary><b>What are some key differences between popular Linux server distributions (e.g., Ubuntu, CentOS) and Windows Server?</b></summary>
<ol>
<li><b>Licensing</b>: 
            <ul>
                <li>Linux distributions (Ubuntu, CentOS) are open-source and free.</li>
                <li>Windows Server requires a license fee.</li>
            </ul>
</li>
<li><b>Package Management</b>: 
            <ul>
                <li>Ubuntu uses APT (Advanced Packaging Tool).</li>
                <li>CentOS uses YUM (Yellowdog Updater, Modified).</li>
                <li>Windows Server uses the Windows Update service or PowerShell (winget) for package management.</li>
            </ul>
</li>
<li><b>File System Structure</b>: 
            <ul>
                <li>Linux distributions use ext4 or XFS by default.</li>
                <li>Windows Server uses NTFS as its primary file system.</li>
            </ul>
</li>
<li><b>Desktop Environment</b>: 
            <ul>
                <li>Linux servers are typically used as a server-only operating system without a graphical interface.</li>
                <li>Windows Server is also primarily used as a server-only OS, but it has some basic GUI features.</li>
            </ul>
</li>
<li><b>Hardware Support</b>: 
            <ul>
                <li>Both Linux and Windows support most modern hardware configurations.</li>
                <li>Some devices might require specific drivers or configuration files for optimal functionality on either platform.</li>
            </ul>
</li>
<li><b>Security Features</b>: 
            <ul>
                <li>Linux servers have built-in security features like e.g., SELinux (Security-Enhanced Linux) or AppArmor.</li>
                <li>Windows Server has its own set of security features, including Firewall with Advanced Security and Windows Defender.</li>
            </ul>
</li>
<li><b>Scripting Languages</b>: 
            <ul>
                <li>Linux servers use Bash as the default shell scripting language.</li>
                <li>Windows Server primarily uses PowerShell for scripting.</li>
            </ul>
</li>
<li><b>Support and Community</b>: 
            <ul>
                <li>Both platforms have dedicated communities and support resources, but Linux's open-source nature means users can modify and contribute to the code themselves.</li>
                <li>Microsoft provides commercial support for Windows Server through various channels (e.g., phone, email, online forums).</li>
            </ul>
</li>
</ol>
</details>

## **Additional Resources**

* **Online resources:**
	+ Microsoft Windows Server documentation [[Link]](https://learn.microsoft.com/en-us/windows-server/get-started/get-started-with-windows-server)
	+ Linux Foundation: Introduction to Linux [[Link]](https://training.linuxfoundation.org/training/introduction-to-linux/)