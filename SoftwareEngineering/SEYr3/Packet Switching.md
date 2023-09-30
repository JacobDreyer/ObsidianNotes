[[Packet Transmission Delay]]: takes L/R seconds to transmit (push out) L-bit package into link at R bps

Store-and-Forward: ==entire== packet must arrive at [[router]] before it can be transmitted on next link

Queuing: occurs when work arrives faster than it can be serviced

Packet Queuing and Loss: if arrival rate (in bps) to link exceeds transmission rate (bps) of link for some period of time:
- packets will queue, waiting to be transmitted on output link
- packets can be dropped (lost) if memory (buffer) in router fills up

great for "bursty" data - sometimes has data to send, but at other times not
- resource sharing
- simpler, no call setup

Excessive congestion possible: packet delay and loss due to buffer overflow
- protocols needed for reliable data transfer, congestion control

### [[Packet Delay]]
![[Packet Delay]]
