# ***Network ARP Scanner***

---

## ***📋 Description***

A simple Python script that scans a local network using ARP requests to discover active devices.

---

## ***🚀 Features***

- Validates user input for proper CIDR notation (e.g., `192.168.1.0/24`)
- Sends ARP broadcasts to the entire network range
- Discovers all active devices on the network
- Returns IP and MAC addresses of responding hosts

---

## ***🔧 Prerequisites***

### Required Packages
- **Python 3.x**
- **Scapy** - Network packet manipulation library

### ⚠️ Important: Root/Sudo Permissions Required

This script requires **root privileges** to send and receive raw network packets. On Linux systems, you must run it with `sudo`:

```bash
sudo python3 network_scanner.py
