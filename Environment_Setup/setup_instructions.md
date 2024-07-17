# Environment Setup

## Prerequisites
- VMware or VirtualBox
- Windows Server ISO
- Windows Client ISO
- (Optional) Linux ISO for additional tools

## Step-by-Step Guide

### Setting Up Virtual Machines
1. **Create a New Virtual Machine:**
   - Open VMware or VirtualBox and create a new VM.
   - Select the appropriate ISO for Windows Server.
   - Allocate resources (CPU, Memory, Disk Space) as per the requirements.

2. **Install Windows Server:**
   - Boot the VM with the Windows Server ISO.
   - Follow the installation prompts to install Windows Server.
   - Set up initial configuration (e.g., Administrator password).

### Installing Active Directory
1. **Install AD DS Role:**
   - Open Server Manager, click "Add Roles and Features".
   - Proceed through the wizard, selecting "Active Directory Domain Services".
   - Complete the installation and promote the server to a domain controller.

2. **Configure Active Directory:**
   - Follow the prompts to create a new forest and domain (e.g., `yourdomain.local`).
   - Complete the wizard and reboot if necessary.

### Setting Up a Windows Client
1. **Create a New Virtual Machine:**
   - Create another VM for the Windows client.
   - Select the appropriate ISO for Windows 10.
   - Allocate resources and install the OS.

2. **Join the Domain:**
   - On the Windows client, go to Settings > System > About > Join a domain.
   - Enter the domain (e.g., `yourdomain.local`) and credentials.
   - Restart the machine to apply changes.

### (Optional) Setting Up a Linux Machine
1. **Create a New Virtual Machine:**
   - Create a VM for the Linux machine.
   - Select the appropriate ISO (e.g., Ubuntu).
   - Allocate resources and install the OS.

2. **Install Security Tools:**
   - Update the package list: `sudo apt update`
   - Install tools: `sudo apt install nmap metasploit-framework wireshark`

## Next Steps
- Proceed to the [Securing Active Directory](../Securing_AD/security_measures.md) section to start securing your AD environment.
