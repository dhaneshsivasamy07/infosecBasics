# Networking Basics

### Networks:

What is a network ?
- Network is a simple way of communication between devices / computers
<br>
- The machines you want to connect and the devices that are used to connect the machines will be at the `physical level`
- Individual Machines are `connected to each other` either via physically (bymeansof LAN cables, hubs, switches etc..,) or wirelessly
- Multiple machines connected are communicated using `hubs / switches`
- In large networks, each sub-network are connecte and communicate with each other via `routers`

### Firewalls:

What is a firewall ?
- A barrier between the internal network (`intranet`) and the outside world (`internet`) 
- Real essence of network is to allow communication between computers, but when the internal network is exposed to the outside world, sensitive infos, IP Crashing / Stealing sensitive infos may occur.
- Firewall is to protect the information by being stole
> FIREWALL ALONE CANNOT PROVIDE A GOOD SECURITY TO ALL YOUR DATAS

### Network and Network Architecture:

- The network interface cards(NIC's), router, switches, hubs and firewalls are the physical pieces of the network
- The way these are connected and the format they use to communicate is known as network architecture

### Data Packets

- After establishing a network connection, how do the computers communicate
	- Identify the destiation where the data has to be sent
	- Format the data for transmission
- Identify where the data has to be sent
	- Each network connected to the network has unique IPswhich is a series of `4 digit` numbers seperated by a period `.` and ranges from `0-255`.
	- [0-255].[0-255].[0-255].[0-255]
	- Eg: 192.168.51.1
- Format the data for transmission
	- The data stored in the server (`machine which is sending the data`) will be in the for of `0's and 1's`
	- These datas are `parsed` into a packets which will be less than `65kb`
	- These data packets have a header section which tells the network about the information about the packets
	- The header section tells the source, destination, data size, IP version, MAC addresses, protocol to be used and Security (TLS) header if the packet is encrypted


### IP Address:

- IP address have two major divisions based upon the version
- IPv4 & IPv6. IPv4 addresses are a series of 4 digit numbers ranging from `0-255`, mentioned above &uarr;
