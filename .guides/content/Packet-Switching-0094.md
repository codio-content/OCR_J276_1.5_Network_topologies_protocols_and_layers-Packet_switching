This is how it works:

![](.guides/img/mapp.png)

## A
- The source computer splits the file into packets and addresses them with the recipient’s IP address.
- The file is split because the transmission of a large file would consume all the bandwidth and slow the network.

## B

- These packets are then sent onto the network using cables or microwaves as in a wireless network.
- Routers on the network inspect each packet and decide the most efficient path for the packet to take on the next stage of its journey.
- In order to do this, each router has a configuration table containing information about which connections lead to particular groups of addresses.
- The routers can balance the load across the network on a millisecond-by millisecond basis.
- If there is a problem with one part of the network while a message is being transferred, packets can be routed around the problem, ensuring the delivery of the entire message.
- The final router can direct the packet to the correct recipient.

## C
- The packets may not arrive in the correct order but the receiving computer can reassemble them consecutively using the information added to each one.

In packet switching the same line can carry parts of billions of communications at the same time and if there is a problem or the line is full, then another route can be quickly found.


Have a look at this incredible video explaining how packet switching is used for the journey of data across the internet – a web page from a server in North America to a computer browser in England.

<iframe width="560" height="315" src="https://www.youtube.com/embed/WwyJGzZmBe8" frameborder="0" allowfullscreen></iframe>
