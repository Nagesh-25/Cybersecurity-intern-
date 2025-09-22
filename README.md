# Cybersecurity Internship Task 1: Local Network Port Scan

## Objective
The objective of this task was to scan my local network to discover active devices and identify their open ports using Nmap.

## Tools Used
* **Nmap**: For performing the port scan.
* **Windows Command Prompt**: For executing the commands.

## Process
1. I first identified my local network's IP range (`192.168.X.X/24`) using the `ipconfig` command.
2. I then ran an Nmap TCP SYN scan using the command: `nmap -sS <my-ip-range>`.
3. I analyzed the results to identify open ports and the services running on them.
4. The full scan results are saved in the `scan_results.txt` file in this repository.

## Key Findings & Security Risks
* I discovered [X number] of devices on my network.
* Device [IP Address] had port [Port Number] open, which runs [Service Name]. This could be a potential risk because...
* (Add another finding or two).

## What I Learned
Through this task, I gained hands-on experience with network reconnaissance and learned the importance of closing unnecessary ports to reduce a network's attack surface.
