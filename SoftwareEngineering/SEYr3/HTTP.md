## Overview
HTTP: [[Hypertext Transfer Protocol]]
- Web's [[Application Layer Protocol]]
- Client/Server Model:
	- Client: browser that requests, receives, (using HTTP protocol) and displays web objects
	- Server: Web server sends (using HTTP protocol) objects in response to requests

HTTP uses [[TCP]]:
- Client initiates TCP connection (creates [[socket]]) to server, port 80
- Server accepts TCP connection from client
- HTTP messages (application-layer protocol messages) exchanged between browser (HTTP client) and web server (HTTP server)
- TCP connection closed

HTTP is "stateless"
- server maintains no information about past client requests

## 2 Types of Connections
##### Non-Persistent HTTP
1. TCP connection opened
2. At most one object sent over TCP connection
3. TCP connection closed
Downloading multiple objects requires multiple connections. Connection is opened just long enough to make request/transfer before being closed?

```ad-note
title: [[RTT]]

Time for a small packet to travel from client to server and back
```

HTTP response time (per object):
- one RTT to initiate TCP connection
- one RTT for HTTP request and first few bytes of HTTP response to return
- object/file transmission time

```ad-failure
title: Disadvantages
- Requires 2 RTTs per object
- OS overhead for each TCP connection
- Browsers often open multiple parallel TCP connections to fetch referenced objects in parallel
```
##### Persistent HTTP
- TCP connection opened to server
- multiple objects can be sent over single TCP connection between client, and that server
- TCP connection closed

- Server leaves connection open after sending response
- subsequent HTTP messages between same client and server sent over open connection
- client sends requests as soon as it encounters a referenced object
- as little as one RTT for all the referenced objects (cutting response time in half)

## 2 Types of HTTP Messages
##### HTTP Request Messages:
- [[ASCII]] (human-readable format)

![[Pasted image 20230925182603.png|500]]
###### POST Method:
- web page often includes form input
- user input sent from client to server in entity body of HTTP POST request message
###### GET Method (for sending data to server):
- Include user data in URL field of HTTP GET request message (following a '?')
###### HEAD Method:
- Requests headers (only) that would be returned if specified URL were requested with an HTTP GET method
###### PUT Method:
- Uploads new file (object) to server
- Completely replaces file that exists at specified URL with content in entity body of POST HTTP request message



