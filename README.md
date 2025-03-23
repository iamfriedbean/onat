# ONAT - OPN Network Audit Tool

## Overview
ONAT is a comprehensive penetration testing toolkit designed for conducting a variety of network attacks. It's equipped to handle wireless and wired network attacks, offering tools for both basic and advanced users.

## Requirements
- A compatible wireless network adapter with support for monitoring mode.
- A compatible wired network adapter.
- Privileged access on the host machine.

## Installation
1. Clone the repository:
2. Move into directory
3. Run the program

## Main Menu
ONAT presents the following core capabilities:

### Wireless Basic
1. **Scan for Wireless Networks:** Detects nearby wireless networks.
2. **Capture and Crack WPA/WPA2:** Captures handshake data and attempts to crack WPA/WPA2 passwords.

### Wireless Advanced
3. **Deauthentication Attack:** Disconnects clients from a network.
4. **Beacon Flood Attack:** Overwhelms networks with fake beacon frames.
5. **WIDS Confusion Attack:** Manipulates Wireless Intrusion Detection Systems.
6. **Evil Twin Attack:** Creates a fake access point to intercept network traffic.

### Other Attacks
7. **Run Network Isolation Scan:** Identifies isolated network segments.
8. **Launch Protocol Attacks:** Access further protocol-based attacks (see below).
9. **ARP Poisoning:** Performs ARP cache poisoning to intercept traffic.

### Utilities
- **Wi-Fi Site Survey (96):** Conducts a detailed survey of available networks.
- **Enable Wireless Monitor Mode (97):** Switches the network adapter to monitor mode.
- **Stop Monitor Mode (98):** Reverts the adapter to its default mode.
- **Exit (99):** Exits the application.

## Launch Protocol Attacks Submenu
1. **STP TCN Attack (DOS):** Disrupts Spanning Tree Protocol with Topology Change Notifications.
2. **STP CONF Attack (DOS):** Attacks STP via Configuration BPDUs.
3. **STP Claim Root Role:** Asserts the attacking device as the STP root.
4. **STP Claim Root Role with MITM:** Converts the attack into a Man-in-the-Middle attack.
5. **CDP Flood Attack (Cisco Devices Only):** Overloads Cisco Discovery Protocol.
6. **DHCP Rogue Server:** Sets up a fake DHCP server to supply malicious IP configurations.
7. **DHCP Starvation Attack (Discover DOS):** Exhausts the DHCP server's IP pool.
8. **DTP Enable Trunking (Cisco Devices Only):** Forces trunking mode on a switch port.
9. **Exit (99):** Returns to the main menu.

## Disclaimer
ONAT must only be used in environments where you have explicit permission to test. Unauthorized access or attacks on networks where you are not permitted could result in legal consequences. Ensure you follow ethical guidelines and legal requirements.

