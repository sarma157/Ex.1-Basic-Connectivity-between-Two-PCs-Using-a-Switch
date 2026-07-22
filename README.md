## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 		

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="983" height="767" alt="Screenshot 2026-07-22 112233" src="https://github.com/user-attachments/assets/1878aab3-5c94-4794-838e-4e9bface879f" />

________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results)
<img width="1081" height="677" alt="Screenshot 2026-07-22 112244" src="https://github.com/user-attachments/assets/8fdf073e-9ead-4d47-8068-9c906a5c8d8b" />
<img width="1367" height="840" alt="Screenshot 2026-07-22 112308" src="https://github.com/user-attachments/assets/190d9fff-fac6-4b57-a4fd-5b11fdbbc9a6" />
<img width="1918" height="1132" alt="Screenshot 2026-07-22 112429" src="https://github.com/user-attachments/assets/4cee778d-5f71-4ea6-ad5e-b1d2bbcdb280" />




Insert screenshots showing ping success, configuration, or simulation results.
________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
