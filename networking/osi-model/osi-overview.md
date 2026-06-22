# osi model overview

## what is the osi model?

- osi = open systems interconnection
- framework used to explain how devices communicate over a network
- provides a standard that allows different devices and technologies to communicate with each other
- helps organize networking into layers with specific responsibilities

## purpose of the osi model

- standardizes network communication
- allows different devices to understand data sent across a network
- breaks networking into smaller, easier-to-understand parts

## 7 layers of the osi model

1. physical
2. data link
3. network
4. transport
5. session
6. presentation
7. application

## encapsulation

- as data moves through the osi layers, information is added to it
- this process is called encapsulation
- each layer adds information needed for communication

## package delivery analogy

imagine you want to mail a package to a friend.

### layer 7 - application

- decide what message to send

### layer 6 - presentation

- format, translate, compress, or encrypt the message

### layer 5 - session

- start and maintain the conversation

### layer 4 - transport

- ensure the package arrives correctly

### layer 3 - network

- determine the route to the destination

### layer 2 - data link

- move the package between nearby locations

### layer 1 - physical

- physically transport the package

## memory trick

7. application
6. presentation
5. session
4. transport
3. network
2. data link
1. physical

all
people
seem
to
need
data
processing

## important notes

- layer 7 is closest to the user
- layer 1 is closest to the hardware
- data moves through multiple layers before reaching its destination
- each layer has a specific responsibility

## key takeaway

- the osi model divides networking into 7 layers
- each layer performs a specific job
- encapsulation adds information as data moves through the layers
- understanding the osi model helps explain how network communication works****
