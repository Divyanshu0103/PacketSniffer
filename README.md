# Network Packet Sniffer

# Overview
The Network Packet Sniffer Project aims to develop a versatile and comprehensive tool for monitoring and troubleshooting communication networks. A tool that captures and analyzes packets of data as they travel over a network. This tool are commonly used for network troubleshooting, security analysis, and monitoring network activity.

# Objective

The primary objective of a network packet sniffer is to capture, analyze, and interpret individual data packets flowing through a computer network in real-time. These are the following objectives:

1. Capture and analyze individual data packets in real-time. 

2. Offer a user-friendly interface for easy interaction and customization by administrators. 

3. Facilitate proactive troubleshooting and issue resolution to maintain network reliability and performance


## Methodology

**PacketContents.java File:** 
1. Define packet content details for UDP, ICMP, and TCP packets.
2. Store packet contents as a list of objects using an ArrayList.

**jpcap_thread Class:** 
1. Ensure sequential storage of packets using threads in Java.
2. Implement methods for capturing and storing packets.

**InterfacesWindow.java File:** 
1. Create logic for opening the interfaces window.
2. Display available network interfaces for packet capturing.

**Sniffer.java File:** 
1. Implement the main logic and functionalities of the packet sniffer application.
2. Display packet details such as source/destination IP, port numbers, etc.
3. Include options for selecting packet types (TCP, UDP, ICMP).
4. Manage packet capturing and storage using jpcap_thread.

**Mavern File SnifferApp.java File:**
1. Initialize Pcap4J to capture packets from the selected network interface.
2. Pass captured packets to jpcap for further processing within the Java program.
   
# Flow of Working:

1. **Run Sniffer.java:** Start the packet sniffer application.
2. **Click on "List Interfaces" Option:** Open the interfaces window to view available network interfaces.
3. **Choose an Interface:** Select the desired network interface from the list.
4. **Choose Packet Type:** Select TCP, UDP, or ICMP packet capturing option.
5. **Click on "Capture":** Begin capturing packets on the selected interface and of the chosen type.
6. **Capture Packets:** Sequentially store captured packets using jpcap_thread. Display packet details such as source/destination IP, port numbers, etc.
7. **Stop Capturing:** option to stop packet capturing if needed.

# Application  
The Network Analyzer project has real-life applications across various sectors and industries, including: 

1. Information Technology (IT) and Telecommunications 
2. Financial Services 
3. Healthcare 
4. Manufacturing and Industrial Automation 
5. Government and Defense 
6. Education 
7. Retail and E-commerce 

# Dependencies 

1. Jpcap librabry with jdk 1.8(32-bit)
2. Pcap librabry (WinPcap)
3. NetBeans



