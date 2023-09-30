### Vanilla [[TCP]] and [[UDP]] Sockets:
- No encryption
- Cleartext passwords sent into socket and traverse internet in cleartext

### [[Transport Layer Security]] ([[TLS]])
- Provides encrypted TCP connections
- Data integrity
- end-point authentication
#### [[TLS]] implemented in [[Application Layer]]
- Apps use [[TLS Library]]s, that use TCP in turn
- cleartext sent into "socket" traverses internet encrypted