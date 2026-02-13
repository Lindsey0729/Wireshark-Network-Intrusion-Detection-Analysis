# Wireshark-Network-Intrusion-Detection-Analysis
## 📌 Project Overview
This project demonstrates hands-on network traffic analysis using Wireshark to capture, filter, and investigate packet-level network communications. The objective was to identify traffic associated with specific IP addresses and analyze TCP and HTTP streams to detect potentially suspicious or unauthorized activity.

The project was created to mirrors real-world Security Operations Center (SOC) investigative workflows, focusing on packet capture analysis, session reconstruction, and traffic inspection.

## 🎯Objectives

- Capture live network traffic and generate PCAP files

- Identify and isolate traffic related to specific IP addresses

- Analyze TCP and HTTP streams for suspicious behavior

- Investigate accessed web resources and communication patterns

- Strengthen foundational SOC and network security skills

## 🔍 Project Methodology

1. Packet Capture

- Used Wireshark to capture live network traffic.![WireShark Capture 1](https://github.com/user-attachments/assets/e7ca556e-7b4d-41c2-a7fc-9af6b93e5a9d)


- Generated PCAP files containing packet-level data transferred over the network.

2. Connection & IP Identification

- Analyzed Conversations within Wireshark to identify active network connections.![WireShark Capture Conversations](https://github.com/user-attachments/assets/dd8657da-1490-411f-99d0-a98371c383f5)


- Verified local system IP addresses using:

- ipconfig /all
![cmd prompt ipconfig](https://github.com/user-attachments/assets/8600f0d7-d392-408c-85fa-22980d5af54f)

- System Ethernet network settings

3. Traffic Filtering

- Applied Wireshark display filters to isolate traffic related to a specific IP address.
![WireShark Ip Filtering](https://github.com/user-attachments/assets/6fbd7ab3-8760-4d02-bf5c-405a6793e682)

- Monitored inbound and outbound communications associated with the selected host.

4. TCP Stream Analysis

- Followed TCP streams to reconstruct full communication sessions.

- Examined transmitted data and reviewed fields highlighted by Wireshark as potentially significant or anomalous.![Wireshark following http ip address](https://github.com/user-attachments/assets/5c98ff61-1550-4e26-8f88-7c8a91397a49)


5. HTTP Stream Investigation![WireShark following tcp stream](https://github.com/user-attachments/assets/3dcba1fe-eaa9-4ff4-95e0-da3e03f0f61d)


- Followed HTTP streams associated with a suspicious IP address.

- Identified accessed websites, request/response behavior, and potential indicators of risk or unauthorized browsing activity.

## 📈 Findings & Outcomes

- Successfully isolated and analyzed traffic related to a targeted IP address.

- Reconstructed TCP and HTTP communication sessions for deeper inspection.

- Identified accessed web resources and evaluated traffic patterns for potential risk.

- Gained practical experience aligned with entry-level SOC analyst responsibilities.

### Skills Learned

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- Wireshark

- TCP/IP, HTTP

- Windows Networking Tools

- ipconfig

- ipconfig /all

- PCAP Analysis

## 👨‍💻 Author

Lindsey Phillips
Aspiring SOC Analyst | Cybersecurity Professional
Certifications: CompTIA Security+, A+, Data+
