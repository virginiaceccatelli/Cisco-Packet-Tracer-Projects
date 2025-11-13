# Cisco-Packet-Tracer-Projects

## 1. SOHO Network Project 
Small Office, Home Office Network Configuration on Cisco Packet Tracer Platform. 
	One  router and one  switch to be used (all CISCO products).
	3 departments (Admin/IT, Finance/HR and Customer service/Reception).
	Each department is required to be in different VLANS.
	Each department is required to have a wireless network for the users.
	Host devices in the network are required to obtain IPv4 address automatically.
	Devices in all the departments are required to communicate with each other.
	Assume the ISP gave out a base network of 192.168.1.0.

### Subnetting: 
	
Base Network: 192.168.1.0

Subnets: 3 → 2^n = 3 → need n = 2

Class C: 

	Mask: 255.255.255.0 → 11111111.11111111.11111111.00000000

	Subnet Mask (borrow n = 2): 11111111.11111111.11111111.11000000 → 255.255.255.192, Block size = 64

1st Subnet: 

	Network ID: 192.168.1.0

	Broadcast ID: 192.168.1.63

	Host range: 192.168.1.1 - 192.168.1.62

2nd Subnet: 

	Network ID: 192.168.1.64

	Broadcast ID: 192.168.1.127

	Host range: 192.168.1.65 - 192.168.1.126

3rd Subnet: 

	Network ID: 192.168.1.128

	Broadcast ID: 192.168.1.191

	Host range: 192.168.1.129 - 192.168.1.190
