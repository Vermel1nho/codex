nmap -sn

Description:

Performs a ping scan, which is used to discover which hosts (devices) are active on a network.
This mode does not scan ports, it only checks if the host responds to ping (or other detection methods).

Syntax:

nmap -sn <IP-OR-RANGE>

Example:
nmap -sn 192.168.0.0/24

Tips and Notes:

Useful for quickly mapping who is connected to your local network.

Can be combined with -v for more details (verbose mode).

Does not require root privileges on most systems.

Equivalent to the old command: ping sweep.


