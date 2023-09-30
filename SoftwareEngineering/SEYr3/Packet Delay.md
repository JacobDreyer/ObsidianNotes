- packets queue in router buffers, waiting for their turn in transmission. queue length grows when arrival rate to link (temporarily) exceeds output link capacity
- [[Packet Loss]] occurs when memory to hold queued packets fills up

### 4 Sources:
$$ d_{nodal} = d_{proc} + d_{queue} + d_{trans} + d_{prop} $$
##### [[Nodal Processing]]
- check bit errors
- determine output link
- typically < microsecs
##### [[Queuing Delay]]
- Time waiting at output link for transmission
- depends on congestion level of [[router]]
##### [[Packet Transmission Delay]]
- L: packet length (bits)
- R: link transmission rate (bps)
- $d_{trans} = L/R$

##### [[Propagation Delay]]
- $d$: length of physical link
- $s$: propagation speed
- $d_{prop} = d/s$

### Real Internet Delays and Routes
- [[Traceroute]] program: provides delay measurement from source to router along end-end internet path towards destination. for all i:
	- sends 3 packets that will reach router i on path towards destination (with time-to-live field value of i)
	- router i will return packets to sender
	- sender measures time interval between transmission and replay
