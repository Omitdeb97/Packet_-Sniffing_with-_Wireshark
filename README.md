# Packet_-Sniffing_with-_Wireshark
This project demonstrates using Wireshark on Kali Linux to capture and analyze real-time network traffic. It covers the fundamentals of packet sniffing and showcases how various protocols communicate across a network.

# Project Summary
This project demonstrates real-time network packet sniffing and analysis using Wireshark. It includes inspecting common protocols (HTTP, DNS, ICMP, TCP, OCSP) to understand how data moves across a network.

# Tools Used
- Wireshark
- Kali Linux
- Terminal commands: `ping`, `curl`

# Analysing
I captured traffic by performing common actions like visiting websites, pinging servers, and initiating DNS lookups. Then I filtered and analyzed key protocols such as:

DNS – Domain resolution queries and responses

HTTP – Website requests and headers

ICMP – Ping packets and echo replies

TCP – 3-way handshakes and port communication

OCSP – Certificate status verification during HTTPS connections

# Screenshots
![image alt](https://github.com/Omitdeb97/Packet_-Sniffing_with-_Wireshark/blob/main/http%20.png?raw=true)
HTTP request showing header with source port: 47760 and destination port: 80 
![image alt](https://github.com/user-attachments/assets/6ade7b69-96e4-48f3-b50c-10f9595a9445)
DNS query for `google.com` with source port: 54328 and destination port: 53
![image alt](https://github.com/Omitdeb97/Packet_-Sniffing_with-_Wireshark/blob/main/Icmp.png?raw=true)
Pinged Google.com and found the total length of: 20 bytes 

![image alt](https://github.com/user-attachments/assets/595ff979-1017-43fa-82cc-9f0138833a2a)
Source port: 51270 and destination port: 80 
![image alt](https://github.com/Omitdeb97/Packet_-Sniffing_with-_Wireshark/blob/main/ocsp.png?raw=true)

# Learnings
- Deep packet inspection with filters
- Understanding common protocols and their behavior
- Basics of SSL certificate validation via OCSP

