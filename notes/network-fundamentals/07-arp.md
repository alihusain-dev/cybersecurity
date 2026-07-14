# arp (address resolution protocol)

## what is arp?

- finds a device's mac address using its ip address
- only works on a local network (lan)
- allows devices on the same network to communicate

## why is arp needed?

devices have two identifiers:

- ip address = where the device is
- mac address = who the device is

before sending data, a device must know the destination's mac address.

## arp cache

- stores previously learned ip-to-mac mappings
- speeds up communication
- prevents repeated arp requests

## how arp works

1. arp request
   - "who owns this ip address?"

2. arp reply
   - the correct device responds with its mac address

3. store in cache
   - save the ip-to-mac mapping for future communication

## analogy

you know someone's home address but not their phone number.

you ask:

> "who lives at 123 oak street?"

only the correct person replies.

- home address = ip address
- phone number = mac address
- contacts list = arp cache

## key takeaway

- arp links ip addresses to mac addresses
- arp only works on local networks
- arp cache stores mappings for faster communication
