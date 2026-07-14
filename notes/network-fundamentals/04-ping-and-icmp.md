# ping and icmp

## ping

- network tool used to test communication between devices
- checks if another device can be reached
- measures the round-trip time for data

## icmp

ping uses icmp (internet control message protocol).

### echo request

> "are you there?"

### echo reply

> "yes, i'm here."

## ttl (time to live)

- attached to every packet
- decreases by 1 each time the packet passes through a router
- prevents packets from traveling forever
- packet is discarded when ttl reaches 0

**analogy:**

- like mailing a package with a limited number of stamps
- each router removes one stamp
- when no stamps remain, the package is thrown away

## ping examples

### local network

```bash
ping 192.168.1.254
```

- tests communication with your router
- confirms your local network is working

### internet

```bash
ping 8.8.8.8
```

- tests communication with the internet
- confirms your router and internet connection are working

## troubleshooting

if:

- ping 192.168.1.254 works
- ping 8.8.8.8 fails

then:

- local network is working
- the problem is between your router and the internet

## key takeaway

- ping tests connectivity
- ping uses icmp
- ttl prevents packets from looping forever
- local ping = test your network
- public ping = test your internet connection
