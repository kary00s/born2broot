# Project README

*This project has been created as part of the 42 curriculum by <kanahiz>*.

## Description
the project _born2beroot_ introduce system administration by setting up and configuring a secure Linux virtual machine. 
The goal of this project is to understand how an operating system works at a low level, while ensuring system stability and security. Throughout the project, the system is configured with proper user and group management, secure authentication policies, firewall rules, and automated tasks

## Instructions

To set up and run this project, follow the steps below:

1. **Prerequisites:**
    - VirtualBox Virtualization software
    - Debian Linux operating system
    - SSH for secure remote access
    - UFW for firewall configuration
    - sudo for privilege management
    - Cron for task automation
    - OpenSSH service
    - PAM modules for Password policy tools
    
2. **Installation:**
    - Install a virtualization tool for me i shoose VirtualBox .
    - Create a new virtual machine and install Debian.
    - Configure disk partitions using LVM during installation.
    - Set the hostname and create a non-root user.
    - Install and configure required services (SSH, sudo, firewall, apt).
    - Apply security policies and system configurations as specified in the project requirements.
    - Reboot and verify the system setup.
3. **Running the Project:**
    - Start the virtual machine.
    - Log in using the configured non-root user.
    - Verify SSH access if enabled.
    - Check that sudo privileges are correctly configured.
    - Ensure the firewall is active and properly configured.
    - Confirm that security policies and scheduled tasks are running as expected.

## Resources

    - I created a summary for this project that includes all the necessary information and the knowledge I gained :
    > (https://www.tldraw.com/f/dvacMeqT04LIxImnlM6SK?d=v2022.4939.1528.1548.tBnjEIw-Nse3uKikr3ADP)

    - (https://www.redhat.com/en/blogpluggable-authentication-modules-pam)

### AI Usage

    - Throughout this project, I successfully set up and configured a secure Linux virtual machine. I gained hands-on experience with:

- **Virtualization and Hypervisors:** Understanding how virtual machines interact with the host system and how resources are managed.
- **System Administration:** Managing users, groups, permissions, and services like SSH and the firewall.
- **Security and Automation:** Applying security policies, configuring firewalls, and scheduling automated tasks with cron.

## Operating System Choice

    - I used Debian :
- **Debian**: Known for its stability and large community support, it’s ideal for reliable server environments. It is also lightweight, making it easier to configure for various applications.
- **Rocky Linux**: A RedHat-based distribution, providing an enterprise-level operating system with long-term support. It is best for users familiar with RedHat-based systems.

**Summary:**  
Debian is lightweight, stable, and beginner-friendly, making it ideal for learning and reliable server setups, while Rocky Linux is an enterprise-focused distribution better suited for Red Hat–based environments and long-term production use.

## AppArmor vs SELinux

    - I used AppArmor :
- **AppArmor**
- Path-based access control
- Easier to configure and understand
- Profiles are simple and human-readable
- Commonly used on **Debian/Ubuntu**
- More beginner-friendly and suitable for learning environments
- **SELinux**
- Label-based access control
- More powerful and fine-grained security
- Complex configuration and policy management
- Commonly used on **Red Hat/Rocky Linux**
- Better suited for enterprise environments

**Summary:**  
AppArmor focuses on simplicity and ease of use, making it ideal for learning and basic security needs, while SELinux provides stronger and more granular security controls, better suited for complex and enterprise environments.

## UFW vs Firewalld
    
    - I used UFW :
- **UFW (Uncomplicated Firewall):** Simple and easy to use, with straightforward command syntax. Commonly used on Debian/Ubuntu systems.
- **Firewalld:** More flexible and powerful, supports zones and dynamic rule management. Commonly used on Red Hat/Rocky Linux systems.

**Summary:** 
UFW is beginner-friendly, while Firewalld offers more advanced and dynamic firewall management.

## VirtualBox vs UTM

    - I used VirtualBox :
- **VirtualBox:** Widely used virtualization software, supports multiple operating systems, and offers advanced configuration options. Commonly used on Windows and Linux systems.
- **UTM:** Lightweight and user-friendly virtualization tool based on QEMU, mainly used on macOS, especially on Apple Silicon.

**Summary:** VirtualBox is more versatile and suitable for most systems, while UTM is a better choice for macOS users seeking simplicity and compatibility.

# Result
    - This project helped me strengthen my understanding of Linux system management, server security, and the practical use of virtualization.