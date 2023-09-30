#### 1. User types URL
#### 2. Browser looks up server name
#### 3. Open a network socket to this [[Network Endpoint]]
#### 4. Write messages to this socket in [[HTTP Protocol]]
#### 5. Read replies from [[Network Socket]]

```ad-success
title: Advantages

Offload processing to client machines

Browser can respond more rapidly to user events

[[JavaScript]] can interact with the downloaded [[HTML]] in a way that the server cannot, creating a user experience more like desktop software than simple HTML ever could
```

```ad-fail
title: Disadvantages

No garuntee that the client has JavaScript enabled

What works in one browser may not work in another

JavaScript heavy web applications can be complicated to debug and maintain
```

