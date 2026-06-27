# Device Manager

## Objective

To understand how Device Manager is used to view and manage the hardware installed on a Windows computer.

---

## What is Device Manager?

Device Manager is a built-in Windows tool that allows users and IT support technicians to view the hardware installed on a computer and check whether each device is working correctly.

It can also be used to update drivers, disable or enable devices, and troubleshoot hardware-related issues.

---

## Practical Exercise

Today I explored Device Manager on my laptop and examined several categories of hardware, including my display adapter, disk drive, network adapters and processors.

This helped me understand how Windows organises hardware devices and where an IT technician can investigate hardware problems.

---

## Hardware I Explored

### Display Adapters

- AMD Radeon™ Vega 8 Graphics
- Virtual Display Device

The display adapter is responsible for processing graphics and displaying images on the screen. I noticed that my laptop uses AMD Radeon Vega 8 integrated graphics.

---

### Disk Drive

- WDC PC SN730 SDBPNTY-256G-1027

This is the internal solid-state drive (SSD) used to store Windows, applications and personal files. SSDs generally provide faster boot times and application loading than traditional hard disk drives.

---

### Network Adapters

- Bluetooth Device (Personal Area Network)
- Realtek 8822CE Wireless LAN 802.11ac PCI-E NIC
- TAP-ProtonVPN Windows Adapter V9
- WAN Miniport adapters

I observed several different network adapters. The Realtek adapter is used for wireless internet connectivity, while the WAN Miniport adapters support different networking and VPN protocols.

---

### Processors

Device Manager displayed eight processor entries for my AMD Ryzen 5 3500U.

Although my laptop has four physical CPU cores, Windows displays eight logical processors because the processor supports simultaneous multithreading (SMT).

---

## Key Learning

During this exercise, I learnt how Windows organises computer hardware within Device Manager and how each category represents a different component of the system.

I also learnt that Device Manager allows IT technicians to quickly identify hardware problems, check whether drivers are installed correctly and investigate devices that are not functioning as expected.

One observation that interested me was that Windows displayed eight processor entries, even though my laptop's processor has four physical cores. After researching this, I learnt that my processor uses simultaneous multithreading (SMT), allowing Windows to recognise eight logical processors.

This exercise improved my understanding of how Windows manages hardware and where technicians begin diagnosing hardware-related issues.

---

## Why This Matters

Device Manager is one of the first tools an IT Support Technician uses when diagnosing hardware problems, missing drivers or devices that are not working correctly.

---

## Example Troubleshooting Scenario

### Problem

A user reports that they cannot connect to Wi-Fi after a Windows update.

### Investigation

An IT technician opens Device Manager and checks the **Network adapters** section to see whether the wireless adapter is missing, disabled or showing a warning icon.

### Possible Resolution

- Enable the adapter if it is disabled.
- Update or reinstall the driver.
- Restart the computer.
- Test the Wi-Fi connection again.

---

## Screenshot

<img width="1920" height="1080" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/9a49fbb8-9a1d-4832-982c-0a059dbfc5ae" />
