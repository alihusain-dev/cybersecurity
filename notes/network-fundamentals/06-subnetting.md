# subnetting

## what is subnetting?

- splitting one large network into smaller networks (subnets)
- improves organization, efficiency, and security

## analogy

- one cake = one large network
- cake slices = subnets
- subnetting decides who gets which slice

## why use subnetting?

- organize devices into groups
- reduce unnecessary traffic
- improve security
- make networks easier to manage

**example:**
- accounting
- finance
- human resources

## subnet masks

a subnet mask determines:

- which part of an ip address is the network
- which part is the host (device)

**example:**

ip address:
- 192.168.1.100

subnet mask:
- 255.255.255.0

result:
- network = 192.168.1
- host = 100

## binary

- 255 = network bits (11111111)
- 0 = host bits (00000000)

example:

255.255.255.0

↓

11111111.11111111.11111111.00000000

↓

network.network.network.host

## host addresses

formula:

- 2^(host bits)

example:

- /24 (255.255.255.0)
- 8 host bits
- 2⁸ = 256 total addresses
- 254 usable addresses

two addresses are reserved:

- network address
- broadcast address

## addresses in a subnet

### network address

- identifies the network

example:
- 192.168.1.0

analogy:
- neighborhood name

### host address

- identifies a specific device

example:
- 192.168.1.100

analogy:
- house address

### default gateway

- sends traffic to other networks
- usually the router

example:
- 192.168.1.254

analogy:
- neighborhood exit/highway

rule:

- same network → communicate directly
- different network → use the default gateway

## key takeaway

- subnetting divides a network into smaller networks
- subnet masks separate the network and host portions of an ip address
- network address = network
- host address = device
- default gateway = other networks
- broadcast address = every device on the subnet
