#### *subnetting*
splitting one large network into smaller networks (subnets)
- helps organize devices and manage traffic
***analogy***
- one cake = one large network
- slices of cake = subnets
- subnetting decides who gets which slice

#### why use subnetting? 
- improve organization
- improve efficiency
- improve security
- give administrators more control
***example**
- accounting subnet 
- finance subnet 
- human resources subnet
instead of putting every device on one giant network.

#### subnet masks
subnet mask tells us:
- which part of an ip address is the network
- which part is the host/device
***example***
ip address:
- 192.168.1.100
subnet mask:
- 255.255.255.0
***result***:
- 192.168.1 = network
- 100 = host
###### why does 255 mean "network"?
subnet masks work in binary.
***example:***
- 255 = 11111111
	- all 1s = network bits
- 0 = 00000000
	- all 0s = host bits

###### binary subnet mask example
255.255.255.0
***becomes:***
- 11111111.11111111.11111111.00000000
***meaning:***
- network.network.network.host
###### counting hosts
to determine how many addresses a subnet can contain:
***formula***
- 2^(number of host bits)
***example***
- 255.255.255.0 (11111111.11111111.11111111.00000000
- host bits:
	- 00000000
	- 2^8 = 256 total addreses
	- 256 - 2 = 254 usable addresses 
	- 2 addreses reserved
		- network address (identifies the network itself)
		- broadcast address (used to send a message to EVERY device on the network)

#### addresses in a subnet

###### network address
- identifies network itself
- represents start of network
- tells devices which network they belong to
***example***
- 192.168.1.0
- the name of the neighborhood "Oak Street Neighborhood"
###### host address
- identifies a specific device on the network 
***example***
- 192.168.1100
- a specific house in the neighborhood
- "123 Oak Street"
###### default gateway
- device that sends traffic to other networks 
- usually the router 
- used whenever data needs to leave the local network
***example***
- 192.168.1.254
- the neighborhood exit/highway entrance
- if you're visiting another neighborhood or city, you leave through the highway entrance first
***rule***
- same network → communicate directly
- different network/internet → send to default gateway
