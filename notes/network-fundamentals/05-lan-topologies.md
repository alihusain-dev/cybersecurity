# lan topologies and networking devices

## topology

- the layout or design of a network

## types of topology

### star

- all devices connect to a central switch or router
- efficient and easy to expand
- if the central device fails, communication stops

### bus

- all devices share one cable
- inexpensive
- bottlenecks can occur
- if the backbone cable fails, the network fails

### ring

- devices form a loop
- data travels from device to device
- one failure can stop communication

## networking devices

### hub

- sends data to every device
- creates unnecessary traffic

### switch

- sends data only to the correct device
- remembers which device is connected to each port
- handles local network traffic

### router

- connects different networks
- routes traffic between networks
- sends traffic from your network to the internet

## local vs non-local traffic

### local traffic

- same network
- handled by a switch

**example:**

- phone → printer

### non-local traffic

- different network or internet
- handled by a router

**example:**

- phone → youtube

## network concepts

### scalability

- how easy a network is to expand
- star topology is the most scalable

### bottleneck

- too much traffic sharing one path

### redundancy

- backup devices or paths in case something fails

**analogy:**

- two bridges leading into a city

## key takeaway

- topology = network layout
- hub = sends to everyone
- switch = local communication
- router = different networks
- star = scalable
- bus = shared cable
- ring = loop
