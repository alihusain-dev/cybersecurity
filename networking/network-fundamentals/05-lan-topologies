#### *topology*
the layout/design of a network

#### types of topology
###### star topology
- all devices connect to a central switch/router
- each device has its own separate connection
- efficient and scalable
- if the central device dies, all communication stops
###### bus topology
- all devices share one backbone cable
- cheap because less cabling/hardware is needed
- bottlenecks happen because every device shares the same path
- if the backbone cable breaks, the whole network breaks
###### ring topology
- devices form a loop
- data travels around the ring device-to-devic
- if one cable/device breaks, communication can stop for the whole ring


#### network devices
##### hub: 
* sends packets to EVERY device 
* devices ignore packets not meant for them 
* creates unnecessary traffic 
##### switch: 
* smarter than a hub remembers 
* which device is connected to which port 
* sends packets only to the correct device 
* mainly handles local network 
###### switch confusion
- a switch is not “only used when devices talk to each other” 
- the switch is basically the entry point into the local network itself
- so even if your laptop is only trying to reach youtube:
	- laptop → local network/switch → router → internet
	- your laptop STILL enters the local network first.
***then:***
- if traffic stays inside the network:
	- switch handles it
- if traffic needs internet/another network:
	- switch forwards it to the router
	- router sends it outward
##### traffic router: 
- connects DIFFERENT networks together 
- routes packets between networks 
- sends traffic from your home network to the internet

#### local vs non-local traffic
###### local traffic
- same network
- usually handled by switch
***example***
- phone → printer
###### non-local traffic
- different network/internet
- router handles it
***example***
- phone → youtube server

#### network concepts
###### scalability
- how easy a network is to expand 
- star topology scales better because each device has its own connection to the switch
###### bottleneck
- too much traffic sharing one path causing slowdown r
###### redundancy
- backup devices/paths in case something fails (like having 2 bridges to a city if one falls) 
- most home networks have little to no redundancy:
	- usually only one router/path 
	- businesses use much more redundancy because downtime matters more
