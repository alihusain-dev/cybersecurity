# tcp

## what is tcp?

- transmission control protocol
- connection-based protocol
- establishes a connection before sending data
- guarantees data is delivered correctly and in order

## key features

- reliable
- error checking
- retransmits lost data
- slower than udp

## key terms

### source port

- port sending the data

### destination port

- port receiving the data

### checksum

- verifies data integrity

### sequence number

- keeps packets in the correct order

### acknowledgement (ack)

- confirms data was received

## three-way handshake

1. **syn**
   - client requests a connection

2. **syn/ack**
   - server accepts the request

3. **ack**
   - client confirms the connection

connection is now established.

## ending a connection

- **fin** = closes the connection normally
- **rst** = immediately ends the connection

## analogy

like making a phone call.

- syn = "hello?"
- syn/ack = "i can hear you."
- ack = "great, let's talk."

## key takeaway

- tcp is reliable and connection-based
- uses the three-way handshake
- guarantees delivery and packet order
- slower than udp because it verifies data
