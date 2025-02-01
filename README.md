# Network-Traffic-Analysis-with-Wireshark

## Overview
This project used WireShark to analyze my home network traffic, identify potential security risks, and optimize my network performance.

## Tools Used
- **Wireshark**: Packet capturing and analysis
- **Python**: Log analysis and automation

## Key Findings
- Detected excessive UDP traffic from additional network devices.
- Identified an IoT device often pinging an external server.
- Used WireSharks built in Firewall Access Control List (ACL) to better regualte internet traffic.
- Output results to a txt file for easier analysis using Python script.

## How to Replicate
1. Install **Wireshark**.
2. Capture traffic using `tcpdump` or Wireshark.
3. Apply filters (e.g., `tcp.port == 80`) to analyze HTTP traffic.
4. Export data and review patterns.
