## Why Layering
Approach to designing/discussing complex systems
- Explicit structure allows identification of relationships of system's pieces
- Modularization eases maintenance and updating of the system
## Layers
- [[Application Layer]]: Supporting network applications
	- [[HTTP]], [[IMAP]], [[SMTP]], [[DNS]]
	- Application exchanges messages to implement some application service using services of transport layer
- [[Transport Layer]]: process-process data transfer
	- [[TCP]], [[UDP]]
	- Transport layer protocol transfers M from one process to another using services of network layer
	- Transport Layer protocol encapsulates application-layer message M, with transport layer-layer header $H_t$ to create a transport-layer segment
		- $H_t$ is used by transport layer protocol to implement its service
- [[Network Layer]]: routing of [[Datagram]] from source to destination
	- [[IP]], [[Routing Protocol]]s
	- Network-layer protocol transfers transport-layer segment \[$H_t$ | M] from one [[Internet Host]] to another, using link layer services
	- Network-layer protocol encapsulates transport layer segment \[$H_t$, | M] with network layer-layer header $H_n$ to create a network-layer [[Datagram]]
		- $H_n$ used by network layer protocol to implement its service
- [[Link]]: data transfer between neighboring network elements
	- [[Ethernet]], [[Wifi]], [[PPP]]
	- Link Layer protocol transfers datagram \[$H_n$ | \[$H_t$ | M]] from host to neighboring host, using network layer services
	- Link layer protocol encapsulates network datagram \[$H_n$ | \[$H_t$ | M]] with link-layer header $H_l$ to create a [[Link Layer Frame]] 
- Physical: bits "on the wire"

![[Drawing 2023-09-25 16.16.14.excalidraw|700]]

![[Pasted image 20230925162412.png]]
