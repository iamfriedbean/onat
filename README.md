# ONAT - OPN Network Attack Tool

## Overview
ONAT is a comprehensive penetration testing toolkit designed for conducting a variety of network attacks. It's equipped to handle wireless and wired network attacks, offering tools for both basic and advanced users. Designed to facilitate network audits, it integrates various tools to perform tasks and simplifies the process by providing a command-line interface to interact with these tasks in a structured manner. 

## Requirements
- A compatible wireless network adapter with support for monitoring mode.
- A compatible wired network adapter.
- Privileged access on the host machine.

## Installation
1. Clone the repository
2. Move into directory (maintain file structure)
3. You may also need adding permission to each executable: e.g., chmod +x onat, chmod +x bin/*)
4. Optionally, you can compile the src files with gcc if you're having compatibility issues
5. Run the main program 'sudo ./onat' 

```
git clone https://github.com/iamfriedbean/onat.git
cd onat
chmod u+x onat
chmod u+x bin/*
sudo ./onat
``` 

## Functionalities and Use Cases

1. **Scan for Wireless Networks**
   - **Function:** Identifies nearby wireless networks.
   - **Use Case:** Provides reconnaissance to outline potential targets for penetration testing.

2. **Capture and Crack WPA/WPA2**
   - **Function:** Captures network handshakes and attempts to crack WPA/WPA2 passwords.
   - **Use Case:** Exploits weak security configurations to verify access vulnerabilities.

3. **Deauthentication Attack**
   - **Function:** Disconnects clients from networks.
   - **Use Case:** Creates disruption or forces clients to reconnect to capture handshake data.

4. **Beacon Flood Attack**
   - **Function:** Sends numerous fake access point signals.
   - **Use Case:** Obfuscates legitimate networks and tests network monitoring capabilities.

5. **WIDS Confusion Attack**
   - **Function:** Generates false alarms within Wireless Intrusion Detection Systems.
   - **Use Case:** Assesses the reliability and response of WIDS to spoofed data.

6. **Evil Twin Attack**
   - **Function:** Creates a rogue access point that mimics legitimate networks.
   - **Use Case:** Captures user credentials and tests susceptibility to phishing attacks.

7. **Run Network Isolation Scan**
   - **Function:** Detects isolated network segments.
   - **Use Case:** Identifies weaknesses in network segmentation policies.

8. **Launch Protocol Attacks**
   - **Function:** Engages in attacks on various network protocols, such as STP, CDP, and DHCP.
   - **Use Case:** Exploits potential misconfigurations, particularly in Cisco environments.

9. **ARP Poisoning**
   - **Function:** Intercepts or alters network communications by corrupting ARP tables.
   - **Use Case:** Facilitates man-in-the-middle attacks or disrupts network traffic.

10. **Wi-Fi Site Survey**
    - **Function:** Conducts in-depth analysis of wireless networks in the area.
    - **Use Case:** Provides insights into network configuration and potential vulnerabilities.

11. **Enable Wireless Monitor Mode**
    - **Function:** Switches the wireless adapter into monitor mode.
    - **Use Case:** Enables packet capture and in-depth traffic analysis for security testing.

12. **Stop Monitor Mode**
    - **Function:** Reverts the wireless adapter to managed mode.
    - **Use Case:** Ensures normal operation after testing activities are completed.
## Disclaimer
ONAT must only be used in environments where you have explicit permission to test. Unauthorized access or attacks on networks where you are not permitted could result in legal consequences. Ensure you follow ethical guidelines and legal requirements.

