
# 🔐 NetworkWalks B083 – Week 2: Windows 10 Virtual Machine Setup

This repository documents my **Week 1** project for the **NetworkWalks Cybersecurity Internship**.

The objective of this project was to create a Windows 10 virtual machine using Oracle VirtualBox, configure networking, assign a static IP address, and verify network connectivity.

---

# 📌 Project Overview

In this lab, I successfully downloaded the Windows 10 ISO, created a new virtual machine in Oracle VirtualBox, installed Windows 10, connected the virtual machine to a NAT Network, configured a static IP address, and verified network connectivity.

This Windows 10 virtual machine will serve as a target machine for future cybersecurity labs involving networking, vulnerability assessment, and penetration testing.

---

# 🎯 Objectives

- Download the Windows 10 ISO.
- Create a new Windows 10 virtual machine.
- Install Windows 10.
- Configure the virtual machine settings.
- Connect the VM to a NAT Network.
- Configure a static IP address.
- Verify network connectivity.
- Prepare the Windows VM for future cybersecurity labs.

---

# 🛠️ Tools Used

- Oracle VirtualBox
- Windows 10 ISO
- Windows 11 (Host OS)

---

# 🪜 Lab Setup Procedure

## Step 1 – Download the Windows 10 ISO

I Downloaded the official Windows 10 ISO image which was used to install Windows inside Oracle VirtualBox.


---

## Step 2 – Create a New Virtual Machine

I Created a new Windows 10 virtual machine in Oracle VirtualBox.

---

## Step 3 – Attach the ISO and Install Windows 10

I Attached the downloaded Windows 10 ISO to the virtual machine and completed the installation process successfully.


---

## Step 4 – Configure the Network

I Configured the virtual machine to use the existing **NAT Network** created in VirtualBox.

---

## Step 5 – Configure a Static IP Address

Configured a static IPv4 address inside Windows 10.

### Static IP Configuration

```text
IP Address      : 10.0.0.10
Subnet Mask     : 255.255.255.0
Default Gateway : 10.0.0.1
Preferred DNS   : 8.8.8.8
```

---

## Step 6 – Verify Network Connectivity

Verified that the Windows virtual machine could communicate over the configured NAT Network.

### Commands Used

Open **Command Prompt** and run:

```cmd
ping 10.0.0.1
```

```cmd
ping 8.8.8.8
```

*Successful responses confirmed that the network configuration was working correctly*



# ⚠️ Challenges Encountered

During the installation and configuration process, I encountered minor networking and VirtualBox configuration challenges.

### Solutions

- Verified VirtualBox network settings.
- Configured the correct NAT Network.
- Assigned the correct static IP configuration.
- Tested connectivity using Windows networking tools.

---

**All screenshots are available in the in this repository.**

---

GitHub: https://github.com/akim-idara-abasi-joseph

LinkedIn: https://www.linkedin.com/in/akim-idara-abasi-joseph


# 🏁 Conclusion

This project marks the successful completion of my Week 2 cybersecurity lab. I successfully created a Windows 10 virtual machine, installed the operating system, configured networking with a NAT Network, assigned a static IP address, and verified connectivity. This setup provides a solid foundation for future cybersecurity, networking, and ethical hacking practicals.
