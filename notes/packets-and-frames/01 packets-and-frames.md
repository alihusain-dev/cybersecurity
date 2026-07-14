# packets and frames

## what are packets and frames?

- data is broken into smaller pieces before being sent across a network
- these pieces are called packets and frames

## packet

- layer 3 (network layer)
- location based
- uses ip addresses
- routed between networks

### packet header

contains information such as:

- source ip
- destination ip
- ttl
- checksum

## frame

- layer 2 (data link layer)
- device based
- uses mac addresses
- delivers data on the local network

## encapsulation

- a frame contains a packet
- layer 2 adds mac address information around the packet

## analogy

sending a letter:

- packet = the letter
- frame = the envelope

the envelope helps deliver the letter locally, while the letter contains the information.

## key terms

### ttl (time to live)

- limits how long a packet can travel
- decreases at each router
- discarded when it reaches 0

### checksum

- checks whether data was corrupted during transmission

## key takeaway

- packet = layer 3 = ip addresses = where
- frame = layer 2 = mac addresses = who
- frames encapsulate packets
