# Week-1-B084K
Cybersecurity Lab setup
### Cybersecurity Lab Environment Setup
Project Overview: Successfully set up an isolated virtual penetration testing and ethical hacking laboratory on the laptop using VirtualBox.
Prerequisites Installed: Downloaded and installed 7-Zip and Oracle VirtualBox (latest version) on the host machine.
Network Configuration: Created a custom NATNetwork under the 10.0.0.0/24 subnet inside VirtualBox with DHCP enabled.
Kali Linux Import: Downloaded and imported the Kali Linux Virtual Machine into VirtualBox as the primary attacking machine.
Network Adapter Setup: Attached Adapter 1 of Kali Linux to the custom NATNetwork, set Promiscuous Mode to "Allow All", and enabled Virtual Cable Connected.
Shared Settings Enabled: Configured bi-directional Shared Clipboard and Drag 'n' Drop, and enabled shared folders linked to the host's /downloads folder.
Static IP Configuration: Assigned a manual IPv4 address of 10.0.0.2/24, Gateway 10.0.0.1, and DNS 8.8.8.8 to Kali Linux, and verified full internet access.
Troubleshooting Applied: Ran network manager commands (sudo nmcli connection modify "Wired connection 1" ipv4.dad-timeout 0) to resolve connectivity if needed.
Snapshot Saved: Successfully took a snapshot of the working virtual machine state for future lab use.
