# dhcp (dynamic host configuration protocol)

## what is dhcp?

- automatically assigns ip addresses to devices
- prevents manual ip configuration
- usually runs on your home router

## why is dhcp important?

without dhcp:

- every device needs a manual ip address
- easy to assign duplicate ip addresses
- slower to manage

with dhcp:

- devices receive an available ip address automatically
- reduces errors
- simplifies network management

## dora process

### discover

- device asks for an ip address

### offer

- dhcp server offers an available ip address

### request

- device accepts the offered ip address

### acknowledge (ack)

- dhcp server confirms the assignment

## dhcp lease

- temporary permission to use an ip address
- device renews the lease before it expires

## analogy

checking into a hotel:

- discover = "do you have any rooms?"
- offer = "room 210 is available."
- request = "i'll take room 210."
- acknowledge = "it's yours."

## key takeaway

- dhcp automatically assigns ip addresses
- dora = discover → offer → request → acknowledge
- ip addresses are leased, not permanently assigned
