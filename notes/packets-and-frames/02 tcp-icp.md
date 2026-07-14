# tcp

## what is tcp?

- transmission control protocol
- connection-based protocol
- establishes a connection before sending data
- guarantees data is received correctly and in order

## advantages

- reliable
- checks for errors
- data arrives in the correct order
- retransmits lost data

## disadvantages

- slower than udp
- requires more processing
- connection must be maintained

## key terms

### source port

- port sending the data

### destination port

- port receiving the data

### source ip

- ip address of the sender

### destination ip

- ip address of the receiver

### checksum

- verifies data integrity
- helps detect corruption

### sequence number

- tracks the order of packets

### acknowledgement number

- confirms data was received

## three-way handshake

tcp establishes a connection using:

### 1. syn

client says:
- "can we connect?"

### 2. syn/ack

server says:
- "yes, i received your request"

### 3. ack

client says:
- "great, connection established"

connection is now ready to send data.

## closing a connection

### fin

- requests a graceful connection close

### ack

- confirms the request

### rst

- immediately terminates the connection

## analogy

like making a phone call

### syn

"hello?"

### syn/ack

"yes, i can hear you"

### ack

"great, let's talk"

data can now be exchanged.

## key takeaway

- tcp = reliable communication
- uses the three-way handshake
- guarantees delivery and order
- slower than udp because of extra reliability
