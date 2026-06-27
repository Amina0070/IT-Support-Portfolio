# Basic Network Commands

## Objective

To learn how basic Windows networking commands can be used to gather information about a computer and diagnose network connectivity issues.

---

## Why These Commands Matter

Command Prompt provides built-in tools that IT Support Technicians use every day to troubleshoot devices, identify network problems and collect system information.

---

## Commands Practised

### hostname

Displays the name of the computer on a network.

---

### whoami

Displays the currently signed-in user account.

---

### ipconfig

Displays the computer's IP configuration, including its IPv4 address and default gateway.

---

### ping

Tests whether another device or website can be reached across the network.

---

### nslookup

Queries the Domain Name System (DNS) to find the IP address associated with a website.

---

## Practical Exercise

During this exercise, I used several built-in Windows Command Prompt tools to gather information about my laptop and test its network connectivity.

I used:

- `hostname` to identify my computer's name.
- `whoami` to identify the currently signed-in user.
- `ipconfig` to view my IPv4 address and default gateway.
- `ping google.com` to test whether my laptop could successfully communicate with an external website.
- `nslookup google.com` to confirm that the Domain Name System (DNS) could successfully resolve a website name into an IP address.

The ping test completed successfully with an average response time of approximately **10 ms**, indicating a stable internet connection during testing.

The `nslookup` command also completed successfully and showed that my router (192.168.1.1) was acting as the DNS server for my network.

---

## Key Learning

This exercise introduced me to several essential networking commands commonly used by IT Support Technicians.

I learnt that:

- `hostname` displays the computer's name on a network.
- `whoami` identifies the currently signed-in user.
- `ipconfig` provides important network configuration information, including the IPv4 address and default gateway.
- `ping` tests whether another device or website can be reached across the network.
- `nslookup` checks whether DNS is correctly translating website names into IP addresses.

Running these commands helped me understand how IT technicians quickly gather information when investigating network connectivity problems.

I also learnt that my home router is currently providing DNS services for my network.

---

## Example Troubleshooting Scenario

### Problem

A user reports that they cannot access any websites on their computer.

### Investigation

An IT technician runs commands such as `ipconfig`, `ping` and `nslookup` to determine whether the issue is caused by the local network, internet connection or DNS resolution.

### Possible Resolution

- Verify the computer has a valid IP address.
- Confirm the default gateway is reachable.
- Test internet connectivity using `ping`.
- Check DNS resolution using `nslookup`.
- Restart the network adapter or router if required.

---

## Screenshot

<img width="1920" height="424" alt="hostname and ipconfig" src="https://github.com/user-attachments/assets/c8bf7190-1a59-4ae0-9e00-98761c951c8b" />

