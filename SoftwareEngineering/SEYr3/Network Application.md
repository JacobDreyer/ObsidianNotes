### Examples
- Social Networking
- Web
- Text Messaging
- E-mail
- Multi-user Network Games
- Streaming Stored Video (YouTube, Hulu, Netflix)
- [[P2P File Sharing]] 
- Voice over IP (Skype)
- Real-time video conferencing (Zoom)
- Internet Search
- Remote Login

### Creating a Network App
Write programs that:
- Run on different end systems
- Communicate over network

No need to write software for network-core devices
- Network core devices do not run user applications
- applications on end systems allows for rapid development and propagation
#### Client-Server Paradigm
Server:
- always-on host
- permanent IP address
- often in [[Data Center]]s, for scaling

Clients:
- Contact and communicate with server
- May be intermittently connected
- May have dynamic IP address
- Do not communicate directly with each other
- Examples: HTTP, IMAP, FTP
#### Peer-Peer Architecture
- no always-on server
- arbitrary end systems directly communicate
- peers request service from other peers, provide service in return to other peers
	- self scalability - new peers bring new service capacity, as well as new service demands
- peers are intermittently connected and change IP addresses
	- complex management
#### Processes Communicating
[[Process]]: program running within a host
[[Client Process]]: process that initiates communication
[[Server Process]]: process that waits to be contacted
- Within same host, two processes communicate using inter-process communication (defined by OS)
- Processes in different hosts communicate by exchanging messages
- Note: applications with P2P architectures have client processes and server processes
- To receive messages, processes must have an identifier
- Host device has unique 32-bit IP address or
- identifier includes both IP addresses and port numbers associated process on host
#### Sockets
- Process sends/receives messages to/from its [[socket]]
- socket analogous to a door
	- sending process shoves message out of the door
	- sending process relies on transport infrastructure on other side of door to deliver message to socket at receiving process
	- two sockets involved: one on each side
