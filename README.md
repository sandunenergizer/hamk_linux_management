# Linux Management
This repository is for tracking the weekly progress of the Linux Management course in ICT Robotics (BEIRP24A6).

## Assignment 1: Setting Up an Azure Virtual Machine

### Initial Configuration
- Used my existing GitHub account.
- Added my HAMK student email to my GitHub account under Settings > Emails.

### Azure Account Configuration
- Signed up for an Azure account using my HAMK student email at [portal.azure.com](https://portal.azure.com).
- Activated the Azure for Students subscription to gain extra credits.

### Virtual Machine Setup
- **Machine Details:**
  - Image: Ubuntu Server 24.04 LTS gen 2 (Canonical)
  - Name: Ubuntu1-Energizer
  - Size: Standard_B2ls_v2
  - Authentication: SSH key
  - Network: Created a new resource group and subnet
  - Security: Set up to allow SSH traffic from a specific IP

  ![Azzure VM](Images/w1_energizer_vm.png)

### Establishing SSH Connection with Terminal 
- **Connecting via SSH:**
  - Entered to the Native SSH in the Azure portal to connect with the VM
  - Copied the SSH key location to Azzure  and created connecting links using Azure.
  - Launched Terminal.
  - Entered the VM's private key link.
  - Successfully connected to the VM with the specified username.

  ![SSH Connection](Images/w1_energizer_ssh_connection.png)

### Verifying the Connection
- Logged into the Ubuntu VM shell successfully.
- Confirmed system access and basic functionality.
- Left system settings at their defaults as instructed.

### Notes
- VM created according to the specifications of the Microsoft Azure course.
- Followed all security best practices.
- Used SSH key authentication for enhanced security.

## Assignment 2: List and append

- Selected five level 2 directories and save their contents in one file, "listing.md"

```sudo ls /etc/{security,selinux,systemd,sos,ssh} > listing.md```

- Listed the files

```cat listing.md```

![List and append](Images/w2_energizer_list_and_append_01.png)

## Assignment 3: User management and file system access

![List and append](Images/w3_1.png)

![List and append](Images/w3_2.png)

![List and append](Images/w3_3.png)

![List and append](Images/w3_4.png)

![List and append](Images/w3_5.png)

![List and append](Images/w3_6.png)

![List and append](Images/w3_7.png)

![List and append](Images/w3_8.png)

