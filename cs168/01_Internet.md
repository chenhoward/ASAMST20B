# The Internet

## Delays

### Processing Delay
The time that it takes to examine a packet's header and figure out where to send it.  It can include
the time to error check the bits. After that it sends it to the queue.  Microseconds.

### Queuing Delay
How long the packet waits on the queue.  In the order of micro to milliseconds.

### Transmission Delay
L bits in a packet.  R bits/second from router A to router B.
Transmission Delay = time to push all bits in a packet into a link = L / R
in the order of micro to milliseconds.

### Propagation Delay
THe time to propage from beginning of link to destination router.  Propagates between
2 * 10 ^8 to 3 * 10 ^ 8 meters per second. If d = distance and s = speed, propagation delay is
d/s

### End to End Delay
Delay from one end system to another.
